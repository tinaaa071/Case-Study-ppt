<template>
    <div>
      <p
        class="cursor-pointer"
        @click="toggleText"
        :class="[
          'transition-opacity duration-500', 
          {
            'text-gray-900 hover:text-gray-500': currentText === initialText,
            'text-emerald-500': currentText === toggledText,
            'opacity-0': isToggling,
          }
        ]"
        v-html="currentText" 
      />
    </div>
  </template>
  
  <script>
  export default {
    props: {
      initialText: {
        type: String,
        required: true,
      },
      toggledText: {
        type: String,
        required: true,
      },
    },
    data() {
      return {
        currentText: this.initialText,
        isToggling: false,
      };
    },
    methods: {
      toggleText() {
        this.isToggling = true;
  
        setTimeout(() => {
          this.currentText =
            this.currentText === this.initialText
              ? this.toggledText
              : this.initialText;
          this.isToggling = false;
        }, 180); // 等待 500ms，確保漸隱效果完成
      },
    },
  };
  </script>
  
  <style scoped>
    .slidev-layout p {
        margin-top: 0;
        margin-bottom: 0;
    }
  </style>
  