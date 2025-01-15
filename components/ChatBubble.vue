<template>
    <div class="relative px-1 py-2 mb-2 text-left bg-blue-50 rounded-3xl transition-all ease-in-out dark:bg-blue-900 chat-bubble before:absolute before:w-0 before:h-0 before:-bottom-3.5 before:left-8 hover:-rotate-3 before:border-t-12">
        <div class="overflow-hidden w-full">
        <div class="flex items-center p-1 whitespace-nowrap marquee-content w-[200%]  font-semibold  text-sm">
            <span class="inline-block">
                {{ spacedText }}{{ spacedText }}
            </span>
            <span class="inline-block">
                {{ spacedText }}{{ spacedText }}
            </span>
        </div>
    </div>
    </div>
  </template>
  
  <script>
    export default {
    computed: {
        spacedText() {
        const text = 'Hello! Nice to meet you 👋🏻'; // Get the localized message
        const repeatedText = Array(10).fill(text).join('\u00A0\u00A0\u00A0\u00A0'); // Using non-breaking spaces
        return repeatedText;
        }
    }
    };
    </script>
  
  <style scoped>  
  .chat-bubble::before {
    border-left: 10px solid transparent;
    border-right: 10px solid transparent;
    border-top: 16px solid #EFF6FF;
  }
  .marquee-content {
    animation: marquee-slide 10s linear infinite;
    animation-timing-function: linear; /* Ensure smooth continuous scrolling */
  }
  
  @keyframes marquee-slide {
    0% {
        transform: translateX(0);
    }
    100% {
        transform: translateX(-100%);
    }
  }
  </style>
  