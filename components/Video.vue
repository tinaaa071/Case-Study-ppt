<template>
  <div
    class="overflow-hidden relative mx-auto w-full rounded-2xl cursor-pointer"
    @click="togglePlay"
  >
    <video
      ref="video"
      class="w-full h-auto"
      autoplay
      muted
      loop
      playsinline
    >
      <source :src="src" type="video/mp4" />
    </video>
  </div>
</template>

<script setup>
import { ref, defineProps } from 'vue';

// 接收來自父元件的影片來源
defineProps({
  src: {
    type: String,
    required: true,
  },
});

const video = ref(null);

// 點擊切換播放或暫停
const togglePlay = () => {
  if (video.value.paused) {
    video.value.play();
  } else {
    video.value.pause();
  }
};
</script>

<style scoped>
video {
  outline: none;
}
</style>
