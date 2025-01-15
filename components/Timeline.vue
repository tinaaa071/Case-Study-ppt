<template>
    <div class="flex relative gap-28 items-center left-1/12">
      <div
        v-for="(event, index) in events"
        :key="index"
        class="flex relative flex-col items-center space-y-4"
      >
        <!-- 上方的時間 -->
        <div class="text-center">
          <p class="text-sm font-medium text-gray-400">{{ event.time }}</p>
        </div>
  
        <!-- 圓點 -->
        <div
          class="w-4 h-4 bg-blue-500 rounded-full ring-4 ring-blue-200 ring-offset-2 animate-ring-blink"
        ></div>
  
        <!-- 下方的事件內容 -->
        <div>
          <p class="text-sm font-black">{{ event.work }}</p>
          <p class="text-xs font-semibold text-blue-500 dark:text-blue-300">{{ event.content }}</p>
        </div>
  
        <!-- 水平線 -->
        <div
          class="absolute top-16 w-32 h-0.5 bg-blue-300 rounded-full transform translate-x-1/2 left-1/9"
          v-if="index < events.length - 1"
        ></div>
  
        <!-- 最後一個圓點右方的虛線水平線 -->
        <div
          v-if="index === events.length - 1"
          class="absolute top-16 w-32 border-t-2 border-orange-300 border-dashed transform translate-x-1/2 left-1/9"
        ></div>
  
        <!-- 右側箭頭 -->
        <div
          v-if="index === events.length - 1"
          class="absolute top-[56px] left-[200px] text-orange-300"
        >
          <svg
            class="w-4 h-4 text-orange-300"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 320 512"
            fill="currentColor"
          >
            <path
              d="M310.6 233.4c12.5 12.5 12.5 32.8 0 45.3l-192 192c-12.5 12.5-32.8 12.5-45.3 0s-12.5-32.8 0-45.3L242.7 256 73.4 86.6c-12.5-12.5-12.5-32.8 0-45.3s32.8-12.5 45.3 0l192 192z"
            />
          </svg>
        </div>
      </div>
    </div>
  </template>
  
  <script setup>
  defineProps({
    events: {
      type: Array,
      required: true,
      default: () => [
        { time: "2021", work: "Researcher", content: "CIER" },
        { time: "2021", work: "Project Manager", content: "TCA" },
        { time: "2022", work: "UI/UX Designer", content: "JING WEI Co." },
        { time: "2023", work: "UI/UX Designer", content: "UARK" },
      ],
    },
  });
  </script>
  
  <style scoped>
  /* 自定義 Tailwind CSS 動畫 */
  @keyframes ring-blink {
    0%, 100% {
      opacity: 1;
      transform: scale(1);
    }
    50% {
      opacity: 0.8;
      transform: scale(1.2);
    }
  }
  .animate-ring-blink {
    animation: ring-blink 1.5s infinite ease-in-out;
  }
  </style>
  