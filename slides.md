---
# You can also start simply with 'default'
theme: apple-basic
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Case Study
info: |
  ## Healthcare Academy
  Speaker: Tina Chen

# apply unocss classes to the current slide
class: p-0
# https://sli.dev/features/drawing
layout: full
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-up
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
---

<div class="flex flex-row items-center justify-center h-full gap-24 px-32 py-14">
  <div class="relative w-1/2">
    <div class="absolute z-10 -left-4 -top-8 w-52">
      <ChatBubble />
    </div>
    <img
    ref="image"
    src="https://i.imgur.com/XiOOKB4.jpeg"
    class="object-cover object-top shadow-lg  rounded-[64px] aspect-square"
  />
  </div>
  <div class="w-full">
    <p class="text-lg font-black">
      I am a UI/UX designer with 3 years of experience and a background in Business Administration.
    </p>
    <ul class="text-sm">
      <li>Passion-Driven</li>
      <li>Curious-Minded</li>
      <li>Quick Learner</li>
    </ul>
  </div>
</div>

<!--
大家好，我是 Tina，擁有三年的 UI/UX 設計經驗，並具備<span style="color:red;">***企業管理碩士學位***</span>。

在這段經歷中，我培養了一些<span style="color:red;">***人格特質***</span>，讓我能夠<span style="color:red;">***勝任這份工作並為團隊創造價值***</span>：

1. 熱情驅動 – 對設計的熱愛讓我持續精進，投入每個專案都全力以赴。
2. 充滿好奇心 – 我樂於探索<span style="color:red;">***新技術與趨勢***</span>，並會將<span style="color:red;">***創新思維***</span>應用於設計中。
3. 快速學習能力 – 能迅速<span style="color:red;">***掌握新工具與技能***</span>，應對多變的專案需求。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-col h-full gap-20 text-center py-14">
  <p class="text-4xl font-black">Work Experiences</p>
  <div class="flex items-center w-full px-6 py-4 bg-blue-50/70 dark:bg-blue-900">
    <Timeline />
  </div>
</div>

<!--
接下來，我想與大家分享我的工作經歷。

我曾在「中經院」擔任研究員，這段經歷讓我培養了<span style="color:red;">***資料分析與市場洞察的能力***</span>。同年，我也在 TCA 擔任 PM，負責行動支付的專案管理，與 Line Pay、街口支付等業者合作，進一步提升了我<span style="color:red;">***跨部門溝通的能力***</span>。

後續職涯中，我轉職成為 UI/UX 設計師，目前於「諾亞克科技」任職，在這個職位中，我更專注於<span style="color:red;">***跨團隊協作與大型專案的執行***</span>。

這些多元的經歷，豐富了我的專業能力，也讓我能夠以更全面的角度理解<span style="color:red;">***使用者需求***</span>與<span style="color:red;">***產品開發流程***</span>。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-col h-full gap-24 px-24 text-center py-14">
  <p class="text-4xl font-black">Work Evaluation</p>
  <div class="grid items-start grid-cols-3 gap-8">
    <div class="flex flex-col items-center">
      <img
        ref="image"
        src="https://i.imgur.com/ou5dOxS.png"
        class="object-cover object-center w-1/2 bg-blue-200 rounded-full aspect-square"
      />
      <div>
        <p class="text-sm italic">
          “She is highly efficient and well-organized, with excellent planning skills.”
        </p>
        <p class="text-xs font-normal text-gray-400">
          Freda · TCA
        </p>
      </div>
    </div>
    <div class="flex flex-col items-center">
      <img
        ref="image"
        src="https://i.imgur.com/rhHzi3H.png"
        class="object-cover object-center w-1/2 bg-blue-200 rounded-full aspect-square"
      />
      <div>
        <p class="text-sm italic">
          “Her work capabilities make the team feel secure and dependable.”
        </p>
        <p class="text-xs font-normal text-gray-400">
          Paul · JING WEI Co.
        </p>
      </div>
    </div>
    <div class="flex flex-col items-center">
      <img
        ref="image"
        src="https://i.imgur.com/tVS42jr.png"
        class="object-cover object-center w-1/2 bg-blue-200 rounded-full aspect-square"
      />
      <div>
        <p class="text-sm italic">
          “She is capable of taking on tasks independently and completing them with high quality.”
        </p>
        <p class="text-xs font-normal text-gray-400">
          Andy · UARK
        </p>
      </div>
    </div>
  </div>
</div>

<!--
在過往工作經驗中，主管們對我的評價是：
1. 我做事效率高且有條理
2. 能夠獨立承擔並以高品質完成工作
3. 讓團隊感到安心可靠
-->

---
transition: slide-left
class: p-0
layout: full
---

<div class="flex flex-col h-full gap-24 px-24 text-center py-14">
  <p class="text-4xl font-black">About Me</p>
  <div class="grid items-center grid-cols-4 gap-8">
    <div >
      <img
        ref="image"
        src="https://i.imgur.com/gHSQpym.png"
        class="object-cover object-center shadow  rounded-[64px] aspect-square"
      />
      <p>
        Travel
      </p>
    </div>
    <div>
      <img
        ref="image"
        src="https://i.imgur.com/FmfJSWq.jpeg"
        class="object-cover object-center shadow  rounded-[64px] aspect-square"
      />
      <p>
        Game
      </p>
    </div>
    <div>
      <a href="https://cafe2-ecru.vercel.app/" target="_blank" class="">
        <img
          ref="image"
          src="https://i.imgur.com/v9ocHR9.jpeg"
          class="object-cover object-center shadow rounded-[64px] aspect-square"
        />
      </a>  
      <p>
        Cafe
      </p>
    </div>
    <div>
      <a href="https://www.figma.com/community/plugin/1420953914431407843/shape-mask" target="_blank" class="">
        <img
          ref="image"
          src="https://cdn-images-1.medium.com/max/1600/1*VUK2az0HJHzilzN0Rpgv0A.png"
          class="object-cover object-center shadow rounded-[64px] aspect-square"
        />
      </a>  
      <p>
        Plugin
      </p>
    </div>
  </div>
</div>

<style>
.slidev-layout a {
  border-style: none;
}
</style>

<!--
在我的個人生活中，我喜歡旅行、看影集和打電動。

假日裡，我會去探索不同的咖啡廳，這也讓我開發了一個「咖啡廳尋店」的專案。
主要目標是為了幫助用戶<span style="color:red;">***更快速找到適合的咖啡廳***</span>。

此外，我獨自開發了一個 Figma 插件，並且在上架不久後，受到了 Adobe 團隊的開發邀請。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="relative flex flex-row items-center h-full py-24 px-14">
  <div class="space-y-8 z-1">
    <div class="flex flex-row items-center gap-3">
      <span class="relative flex w-3 h-3">
        <span class="absolute inline-flex w-full h-full bg-green-400 rounded-full opacity-75 animate-ping"></span>
        <span class="relative inline-flex w-3 h-3 bg-green-500 rounded-full"></span>
      </span>
      <p class="text-sm text-gray-400">
        In Progress
      </p>
    </div>
    <div>
      <p class="pb-8 text-6xl font-black">Healthcare<br><br><br>Academy</p>
      <p class="text-base tracking-wider">
        Taiwan International Medical Education
      </p>
    </div>
  </div>
  <div class="z-1">
    <img
    ref="image"
    src="https://i.imgur.com/2MygSlS.png"
    class="origin-right scale-90"
  />
  </div>
  <!-- Circle -->
  <div 
    v-motion
    :initial="{ x: 200 }"
    :enter="final"
    class="absolute -z-10 bg-blue-50 dark:bg-blue-900 rounded-full w-[700px] aspect-square -top-1/12 -translate-y-1/2 -right-1/5">
  </div>
</div>

<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>

<!--
接下來，我想與大家分享這次的專案——《海外醫事人員培訓平台》。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-row items-center justify-start h-full gap-64 px-32 py-14"> 
  <p class="text-6xl font-black">Agenda</p>
  <ol class="text-sm list-decimal">
    <li>Background</li>
    <li>Research & Define</li>
    <li>Design System</li>
    <li>Feature Demo</li>
  </ol>
  <!-- Circle -->
  <div 
    v-motion
    :initial="{ x: -200 }"
    :enter="final"
    class="absolute -z-10 bg-blue-50 dark:bg-blue-900 rounded-full w-[700px] aspect-square -top-[1/13] -translate-y-1/2 -left-1/5">
  </div>
</div>

<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>

<!--
這是今天的議程，我將帶領大家了解這項專案的設計歷程。

1. 從「專案背景」開始，了解這個專案的<span style="color:red;">***需求與動機***</span>。

2. 接著，在「研究定義階段」的<span style="color:red;">***重點發現與專案目標***</span>。

3. 之後，我將介紹我們的「設計系統」。

4. 最後，透過一些「功能演示」來展示這項專案的成果。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-col justify-between h-full p-14"> 
  <div class="space-y-2">
    <p class="text-xl font-black">Background</p>
    <p class="text-sm">
      This platform is designed to provide a comprehensive overview of Taiwan's medical and health training courses and achievements for foreign medical professionals. It also offers more complete training information and application services through the platform.
    </p>
  </div>
  <div class="grid grid-cols-4 gap-6">
    <div class="space-y-2">
      <p class="text-xl font-black">Role</p>
      <ul class="text-xs">
        <li>UI/UX Designer</li>
        <li>Product Roadmap</li>
      </ul>
    </div>
    <div class="space-y-2">
      <p class="text-xl font-black">Team</p>
      <ul class="text-xs">
        <li>1 Product Designer</li>
        <li>1 Product Manager</li>
        <li>1 Systems Analysis</li>
        <li>1 Front-end Developer</li>
        <li>3 Back-end Developer</li>
      </ul>
    </div>
    <div class="space-y-2">
      <p class="text-xl font-black">Timeline</p>
      <p class="text-xs">
        More than 1 year
        <br>
        <span class="text-gray-400">
          (2023.10 - Now)
        </span>
      </p>
    </div>
    <div class="space-y-2">
      <p class="text-xl font-black">Company</p>
      <p class="text-xs">
        Joint Commission of Taiwan
      </p>
    </div>
  </div>
</div>

<!--
這項專案由隸屬於衛福部的「醫策會」委託，主要目的是為了<span style="color:red;">***提供台灣醫療資源給海外醫療專業人員，促進彼此間的學習交流***</span>。

專案涵蓋前台與後台的設計規劃，今天我將專注於分享前台的設計部分。

***

在這個專案中，我擔任 UI/UX 設計師，負責<span style="color:red;">***功能規劃與介面設計***</span>的工作。

我與跨領域的團隊密切合作，包括專案經理、系統分析師與工程師。

此專案自 2023 年 10 月啟動至今，已歷經一年多的開發歷程，並將持續迭代改進。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-col justify-between h-full p-14"> 
  <div class="space-y-2">
    <p class="text-xl font-black">Design Flow</p>
    <p class="text-sm">
      In this project, I focused on designing the overall website architecture to ensure users could browse courses and complete the application process. My primary responsibility was to plan an online course application system that is user-friendly and allows users to verify their application results. 
      <br>
      <br>
      The goal of the platform is to foster closer medical exchange and collaboration with other countries, promoting the bidirectional sharing of knowledge and skills.
    </p>
  </div>
  <div class="grid grid-cols-4 gap-6">
    <div class="space-y-2">
      <p class="text-xl font-black">Research</p>
      <ul class="text-xs">
        <li>Website IA</li>
        <li>Course Information Display Requirements</li>
        <li>Course Registration and Review System</li>
      </ul>
    </div>
    <div class="space-y-2">
      <p class="text-xl font-black">Define</p>
      <ul class="text-xs">
        <li>Website Design Specifications</li>
        <li>Registration system for different roles</li>
        <li>Online Course Application Workflow</li>
        <li>Online Course Application Review Process</li>
      </ul>
    </div>
    <div class="space-y-2">
      <p class="text-xl font-black">Design</p>
      <ul class="text-xs">
        <li>Component Design</li>
        <li>Website UI Design</li>
        <li>Responsive Website Compatibility</li>
      </ul>
    </div>
    <div class="space-y-2">
      <p class="text-xl font-black">Test & Iteration</p>
      <ul class="text-xs">
        <li>Testing & Collect Feedback</li>
      </ul>
    </div>
  </div>
</div>

<!--
我們深入研究<span style="color:red;">***用戶需求***</span>，專注打造<span style="color:red;">***直覺且友善***</span>的網站，確保使用者能輕鬆瀏覽課程並順利完成報名。

我們的設計流程，包含了<span style="color:red;">***用戶研究到功能設計***</span>，以及後續的設計迭代。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-col justify-between h-full p-14"> 
  <p class="text-xl font-black">
  ☹️ User Pain Point
  </p>
  <div class="grid grid-cols-3 gap-y-2 gap-x-12">
    <div class="">
      <p class="text-lg font-black">1. Hospital publicity is weak</p>
      <p class="text-xs">
        The hospital's authoritative departments are fully equipped but take a more low-profile approach in promotion.
      </p>
    </div>
    <div class="">
      <p class="text-lg font-black">2. Insufficient training information</p>
      <p class="text-xs">
        Training information is insufficient, making it difficult to clearly understand the overall application process.
      </p>
    </div>
    <div class="">
      <p class="text-lg font-black">3. Training results and evaluations</p>
      <p class="text-xs">
        Overseas personnel find it difficult to access training results and evaluations, making it challenging to showcase training achievements externally.
      </p>
    </div>
    <div class="">
      <p class="text-lg font-black">4. Issues with document resubmission</p>
      <p class="text-xs">
        The process of submitting supplementary documents is time-consuming, labor-intensive, and disorganized.
      </p>
    </div>
    <div class="">
      <p class="text-lg font-black">5. Customized training programs</p>
      <p class="text-xs">
        Overseas healthcare personnel have clear learning goals and require customized training programs.
      </p>
    </div>
  </div>
</div>

<!--
在研究過程中，我們發現了幾個使用者痛點。

**1. 許多醫院在宣傳上薄弱。**

儘管台灣的醫院在醫療資源都非常完備，但在宣傳與推廣方面卻較為低調，造成<span style="color:red;">***參與者對課程的了解不足***</span>。

***

**2.培訓資訊不足。**

資訊混雜，使用者難以理解相關<span style="color:red;">***課程內容及申請流程***</span>，進而影響他們的參與意願。

***

**3. 缺乏課程培訓成果與評價。**

海外醫療人員很難獲取相關課程的<span style="color:red;">***回饋***</span>，這使得他們在<span style="color:red;">***尋找適合課程***</span>時遇到困難。

***

**4. 文件重新提交的問題。**

使用者在報名過程中常常需要<span style="color:red;">***提交各種資料***</span>，這個過程既耗時又費力，尤其是專業醫療人員的資格審核也相對嚴格，過程不順利會影響他們的報名意願。

***

**5. 客製化的培訓計劃。**

醫療人員的進修常常會需要<span style="color:red;">***特定的課程規劃***</span>，以幫助他們有效地達成學習目標。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid items-center h-full grid-cols-2 p-14"> 
  <p class="text-6xl font-black">Our Goal</p>
  <ol class="text-sm list-decimal">
    <li>Establish a <strong>registration system</strong> that includes authentication</li>
    <li><strong>Integrate course resources</strong> from national medical institutions</li>
    <li>Provide <strong>multi-language</strong> switch for the website</li>
    <li>Provide course <strong>classification and filtering functions</strong></li>
    <li>Provide <strong>individual and group application functions</strong> for courses</li>
    <li>Allow participants to view the <strong>application review results</strong></li>
    <li>Students can <strong>consult</strong> with the course provider online</li>
  </ol>
</div>

<!--
我們的目標：
1. 建立一個包含<span style="color:red;">***身份驗證***</span>的註冊系統。
2. <span style="color:red;">***整合***</span>全國醫療機構的課程資源。
3. 提供網站的<span style="color:red;">***多語言切換***</span>功能，確保不同語言使用者的可訪問性。
4. 提供課程<span style="color:red;">***分類與過濾***</span>功能，幫助使用者輕鬆找到相關課程。
5. 提供<span style="color:red;">***個人和團體報名***</span>功能，滿足不同學習者的需求。
6. 讓參與者查看<span style="color:red;">***報名審核結果***</span>。
7. 學生可以在線上進行<span style="color:red;">***諮詢***</span>，獲得支援與指導。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid items-center h-full grid-cols-2 p-14"> 
  <p class="text-6xl font-black">Solution</p>
  <ol class="text-sm list-decimal">
    <li>Design a document upload and <strong>automatic verification</strong> system</li>
    <li>Provide course information and <strong>filtering functions</strong></li>
    <li>Display course training <strong>evaluation results</strong></li>
    <li>Establish a <strong>multilingual</strong> frameworks</li>
    <li>Create a <strong>dual application mode</strong> with dynamic forms</li>
    <li>Develop a application <strong>status tracking</strong> feature</li>
    <li>Build an <strong>online consultation system</strong> to provide real-time assistance</li>
  </ol>
</div>

<!--
有了用戶**痛點**和**目標**後，我們提出了解決方案：
1. 在身份驗證功能上，設計<span style="color:red;">***自動驗證系統***</span>，提升效率。
2. 提供課程資訊與<span style="color:red;">***篩選功能***</span>，幫助使用者輕鬆找到符合需求的課程。
3. 顯示課程培訓<span style="color:red;">***回饋結果***</span>，讓使用者能夠清楚了解課程評價。
4. 建立<span style="color:red;">***多語言框架***</span>，使平台能夠服務來自不同國家的使用者。
5. 創建<span style="color:red;">***雙重報名模式***</span>，適應個人與團體報名需求。
6. 開發<span style="color:red;">***報名狀態追蹤***</span>功能，讓使用者能隨時查看其報名進度與審核結果。
7. 建立<span style="color:red;">***線上諮詢系統***</span>，提供即時的協助。
-->

---
transition: slide-left
class: p-0
layout: full
---

<div class="grid items-center h-full grid-cols-2"> 
  <div class="space-y-2 p-14">
    <p class="text-2xl font-black">💬 Challenges in the Project</p>
    <ol class="text-sm list-decimal">
      <li>
        <ToggleText 
        :initialText="'The client was unable to provide <strong>clear requirements</strong>'" 
        :toggledText="'Refer to the features of <strong>mature products</strong> in the market and plan based on existing functionalities'" 
        />
      </li>
      <li>
        <ToggleText 
        :initialText="'The project <strong>architecture was extensive</strong>'" 
        :toggledText="'Break down into modules and <strong>prioritize</strong> key components'" 
        />
      </li>
      <li>
        <ToggleText 
        :initialText="'The development <strong>timeline was tight</strong>'" 
        :toggledText="'Streamline workflows, and focus on <strong>essential features</strong>'" 
        />
      </li>
    </ol>
  </div>
  <img
    ref="image"
    src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?q=80&w=2940&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
    class="object-cover object-center h-full"
  />
</div>

<script setup>
import { ref } from 'vue';

const message = ref('點擊我來更換文字');
</script>

<!--
專案中的一些挑戰：
1. 客戶未能提供<span style="color:red;">***明確的需求***</span>，這使得我們在設計過程中需要更多的溝通與確認。

👉🏻 解決：參考市面上成熟之產品功能，並針對既有功能規劃

***

2. 專案<span style="color:red;">***架構較為龐大***</span>，包含了前後台的設計，涉及的功能與設計需求較為複雜。

👉🏻 解決：分解模組並確定關鍵功能的優先順序。

***

3. 開發<span style="color:red;">***時間緊迫***</span>，我們需要在有限的時間內高效完成設計與開發工作。

👉🏻 解決：簡化工作流程，並專注於基本功能。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid items-center h-full grid-cols-2 p-14"> 
  <p class="text-6xl font-black leading-loose">Research<br><br><br>&<br><br><br>Define</p>
  <div>
    <p>
      After analyzing user needs and the functional architecture, I set 2 design directions for the project:
    </p>
    <ol class="text-sm list-decimal">
      <li>
        Target Audience-Oriented
        <br>
        <span>
          <ul class="text-gray-500">
            <li>Courses categorized by professional fields.</li>
            <li>The color selection is composed of stable and medical tones.</li>
          </ul>
        </span>
      </li>
      <li>
        Enhancing User Experience
        <br>
        <span>
          <ul class="text-gray-500">
            <li>Provide custom search and filter options.</li>
            <li>A application process that is easy to complete.</li>
            <li>Convenient visibility of the review status.</li>
          </ul>
        </span>
      </li>
    </ol>
  </div>
</div>

<!--
在深入分析<span style="color:red;">***使用者需求和功能架構***</span>後，我設定了兩個關鍵的設計方向。

1. 第一個方向是<span style="color:red;">***以目標受眾為導向***</span>

a. 確保課程根據**專業領域**進行分類

b. 並在色彩選擇上使用**醫療相關的色調**，以增強專業性和信任感

***

2. 第二個方向則<span style="color:red;">***強調使用者體驗***</span>，著重在<span style="color:red;">***功能流程***</span>的設計

a. 針對課程提供自訂搜尋和過濾選項

b. 簡便的註冊和報名流程

c. 清楚的課程審核狀態
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-col items-center h-full gap-16 text-center p-14"> 
  <p class="text-2xl font-black">Training Course Categories</p>
  <Course />
</div>

<!--
為了幫助各位更加了解這個專案的設計邏輯，我簡單介紹我們的課程分類。

課程分類會影響的功能有：<span style="color:red;">***課程篩選、課程報名、報名審核***</span>，也是我們專案的幾個核心功能。

***

X 軸的分類為：「一般課程」和「臨床培訓」課程。

Y 軸的分類為：「醫療專業」和「醫務應用」。

***

若分類是「臨床培訓＆醫療專業」的課程（右上角），對於<span style="color:red;">***課程報名的資格***</span>會比較嚴格，需要<span style="color:red;">***上傳更多專業的醫事人員執照***</span>，並且會對於<span style="color:red;">***團體報名***</span>的功能有限制。
-->

---
transition: slide-left
class: p-0
layout: full
---

<div class="flex flex-col justify-between h-full p-14"> 
  <div class="space-y-2">
    <p class="text-xl font-black">Competitive Analysis</p>
    <p class="text-sm">
      I researched products on the market with similar course application features but did not find a suitable example.
    </p>
  </div>
  <div class="grid grid-cols-3 gap-y-6 gap-x-32">
    <div class="space-y-3 text-center">
      <div class="overflow-hidden border border-gray-100 rounded-2xl aspect-video">
        <img
          ref="image"
          src="https://i.imgur.com/7VlO2nB.png"
          class="transition-all duration-200 ease-in-out hover:scale-110"
        />
      </div>
      <p class="text-sm font-black">Hahow</p>
    </div>
    <div class="space-y-3 text-center">
      <div class="overflow-hidden border border-gray-100 rounded-2xl aspect-video">
        <img
          ref="image"
          src="https://i.imgur.com/IZHmUjI.png"
          class="transition-all duration-200 ease-in-out hover:scale-110"
        />
      </div>
      <p class="text-sm font-black">Udemy</p>
    </div>
    <div class="space-y-3 text-center">
      <div class="overflow-hidden border border-gray-100 rounded-2xl aspect-video">
        <img
          ref="image"
          src="https://i.imgur.com/BM5WXVl.png"
          class="transition-all duration-200 ease-in-out hover:scale-110"
        />
      </div>
      <p class="text-sm font-black">Coursera</p>
    </div>
    <div class="space-y-3 text-center">
      <div class="overflow-hidden border border-gray-100 rounded-2xl aspect-video">
        <img
          ref="image"
          src="https://i.imgur.com/G2pCFYH.png"
          class="transition-all duration-200 ease-in-out hover:scale-110"
        />
      </div>
      <p class="text-sm font-black">Future Learn</p>
    </div>
    <div class="space-y-3 text-center">
      <div class="overflow-hidden border border-gray-100 rounded-2xl aspect-video">
        <img
          ref="image"
          src="https://i.imgur.com/mHWGOe8.png"
          class="transition-all duration-200 ease-in-out hover:scale-110"
        />
      </div>
      <p class="text-sm font-black">Techable</p>
    </div>
    <div class="space-y-3 text-center">
      <div class="overflow-hidden border border-gray-100 rounded-2xl aspect-video">
        <img
          ref="image"
          src="https://i.imgur.com/IL9zMOt.png"
          class="transition-all duration-200 ease-in-out hover:scale-110"
        />
      </div>
      <p class="text-sm font-black">Klook</p>
    </div>
  </div>
</div>

<!--
在<span style="color:red;">***功能設計***</span>時，因為我們專案的時程較緊迫，我選擇對市場上幾個成熟的平台進行了深入研究。

我們的功能需求涵蓋<span style="color:red;">***個人及團體報名，以及不同角色的資格審核***</span>。

***

我研究了類似功能的平台包括 Hahow、Udemy、Coursera 和 Klook 等。

1. Hahow
提供了豐富的課程選擇，但它的報名系統主要偏重個人報名，且缺乏團體報名的功能，並且他們是針對線上課程運作的平台。

2. Udemy 
擁有廣泛的國際課程選擇，但同樣未針對團體報名做出專門設計，以及同樣是線上課程的平台。

3. Future Learn 和 Coursera 
提供了相對完善的學習平台和多樣化的課程，儘管它們有一定的報名功能，但在團體註冊的支持上不夠靈活，且整體的報名流程較為繁瑣。

4. Techable 
以科技與創新課程為主，支持部分報名功能，但缺少個人化與團體報名的選項，無法滿足多樣化需求。

5. Klook 
提供的是旅遊和體驗型課程，報名流程更偏向活動註冊，而非完整的學習管理，無法提供足夠的課程分類與報名選項。

***

雖然它們都是市場上成熟的產品，但都未能完全滿足我們專案的需求。這也讓我們發現，<span style="color:red;">***我們專案開發的功能是比較創新的***</span>，但也因為沒有前例的參考，這會是一個比較困難的挑戰。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-row items-center justify-between h-full"> 
  <p class="text-4xl font-black px-14">Information<br><br>Architecture</p>
  <img
    ref="image"
    src="https://i.imgur.com/E3rF3z9.png"
    class="object-center h-full object-fit"
  />
</div>

<!--
在搜集了相關資訊後，我規劃了資訊架構，讓我們可以更瞭解<span style="color:red;">***彼此頁面及功能之間的關聯性***</span>。

並且我也將<span style="color:red;">***相關的元件***</span>使用顏色做區分，在檢視上可以更加便利。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="h-full text-center"> 
  <img
    ref="image"
    src="https://i.imgur.com/RiAO6LO.png"
    class="w-full mt-4 mb-20 bg-white"
  />
  <p class="text-2xl font-black">User flow for applying for a course</p>
</div>

<!--
接下來是使用者流程圖的說明，我以<span style="color:red;">***課程報名功能***</span>為範例。

在這個過程中，我們設計了多個決策點，<span style="color:red;">***根據使用者的回應，提供他們選擇合適的選項***</span>。

並且針對報名功能採用<span style="color:red;">***動態適應設計***</span>，分為「個人及團體報名」。

這個功能是指，在報名的流程中，會有兩套不同的版型，如何區分採用哪一套的版型，則是取決於課程報名的<span style="color:red;">***人數***</span>，若是報名人數大於 1，則會自動轉換為團體報名的模板。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-row items-center justify-start h-full gap-64 px-32 py-14"> 
  <p class="text-6xl font-black">Design<br><br><br>System</p>
  <ul class="text-sm">
    <li>Variable settings</li>
    <li>Multilingual settings</li>
    <li>Figma design files</li>
    <li>Storybook management</li>
  </ul>
  <!-- Circle -->
  <div 
    v-motion
    :initial="{ x: -200 }"
    :enter="final"
    class="absolute -z-10 bg-blue-50 dark:bg-blue-900 rounded-full w-[700px] aspect-square -top-[1/13] -translate-y-1/2 -left-1/5">
  </div>
</div>

<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>

<!--
在設計系統上我定義了以下幾個項目，使我們的團隊可以<span style="color:red;">***保持一致的設計***</span>。
1. 針對變數進行設置
2. 多語言設定
3. Figma 設計文件管理
4. Storybook 文件管理
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">01</span><br><br>Variable<br><br>Settings</p>
    <p class="text-xs text-gray-500">
      The project is developed using <span v-mark.circle.orange>Tailwind</span>. 
      <br>
      <br>
      I set up the variables in the files, allowing engineers to directly view the relevant class settings during development.
    </p>
  </div>
  <div class="flex items-center h-full col-span-3 px-10 bg-gray-200">
    <!-- 右邊內容 -->
    <img
      ref="image"
      src="https://i.imgur.com/HkDOiYr.png"
      class="w-full"
    />
  </div>
</div>

<!--
在變數設定的部分，我們專案使用 Tailwind 開發，所以我也將相關的變數直接納入設計中。

我們對各種變數進行了設定，包括間距、圓角等。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">01</span><br><br>Variable<br><br>Settings</p>
    <p class="text-xs text-gray-500">
      The project is developed using Tailwind. 
      <br>
      <br>
      I set up the variables in the files, allowing engineers to directly view the relevant class settings during development.
    </p>
  </div>
  <div class="flex items-center h-full col-span-3 px-10 bg-gray-200">
    <!-- 右邊內容 -->
    <Video
      src="https://tinaaa071.github.io/Case-Study-ppt/video1.mp4"
    />
  </div>
</div>

<!--
有了剛剛的設定，已設定的變數會直接顯示在元件上，便於開發人員快速參考。

側邊欄也會即時顯示<span style="color:red;">***變數名稱***</span>，如間距、圓角、顏色等。

這樣不僅提高<span style="color:red;">***設計與開發的一致性***</span>，也大大提高了開發的效率。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">02</span><br><br>i18n<br><br>Settings</p>
    <p class="text-xs text-gray-500">
      I set up multilingual variables, allowing for direct switching and viewing in the files during development.
    </p>
  </div>
  <div class="flex items-center h-full col-span-3 px-10 bg-gray-200">
    <!-- 右邊內容 -->
    <img
      ref="image"
      src="https://i.imgur.com/3huTlpN.png"
      class="w-full"
    />
  </div>
</div>

<!--
另外，我也設置了多語系變數，使得<span style="color:red;">***切換和查看不同語言的內容***</span>變得更加便捷。

表格中展示了中英文的變數。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">02</span><br><br>i18n<br><br>Settings</p>
    <p class="text-xs text-gray-500">
      I set up multilingual variables, allowing for direct switching and viewing in the files during development.
    </p>
  </div>
  <div class="flex items-center h-full col-span-3 px-10 bg-gray-200">
    <!-- 右邊內容 -->
    <Video
      src="https://tinaaa071.github.io/Case-Study-ppt/video2.mp4"
    />
  </div>
</div>

<!--
從影片中可以看到，在設計面板上，我們可以<span style="color:red;">***直接設定語系的切換***</span>，這樣畫面就能即時更新為不同語言版本。

讓開發人員可以方便地<span style="color:red;">***參考各種語系的樣式***</span>。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">03</span><br><br>Figma<br><br>Design<br><br>Files</p>
    <p class="text-xs text-gray-500">
      I defined the design system and components in the file, including their usage scenarios and states.
    </p>
  </div>
  <div class="flex items-center h-full col-span-3 px-10 bg-gray-200">
    <!-- 右邊內容 -->
    <Video
      src="https://tinaaa071.github.io/Case-Study-ppt/video3.mp4"
    />
  </div>
</div>

<!--
我製作了 Figma Library 檔案，定義了<span style="color:red;">***完整的「設計系統」以及各種「元件」***</span>，並標註了每個元件的使用情境、狀態與細節，這些元件依功能分類，方便查找。

設計系統能在<span style="color:red;">***大型文件更新***</span>時提升工作效率。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">03</span><br><br>Figma<br><br>Design<br><br>Files</p>
    <p class="text-xs text-gray-500">
      I showcased the dimensions of different pages in the files and defined various scenarios and workflows.
    </p>
  </div>
  <div class="flex items-center h-full col-span-3 px-10 bg-gray-200">
    <!-- 右邊內容 -->
    <Video
      src="https://tinaaa071.github.io/Case-Study-ppt/video4.mp4"
    />
  </div>
</div>

<!--
我將<span style="color:red;">***不同使用情境的頁面***</span>進行了分類，並依照<span style="color:red;">***流程***</span>進行排序。

此外，我也展示了 RWD 畫面設計，呈現各個頁面在不同裝置下的呈現。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">04</span><br><br>Storybook</p>
    <p class="text-xs text-gray-500">
      I used Storybook as a platform for visual guidelines and component demonstrations, assisting the development team in referencing concrete design standards during implementation.
    </p>
  </div>
  <div class="flex items-center h-full col-span-3 px-10 bg-gray-200">
    <!-- 右邊內容 -->
    <a href="https://main--6758f1bddc4388960f8ac32f.chromatic.com/?path=/story/guides-color--color-list" target="_blank" class="overflow-hidden transition-all duration-300 ease-in-out rounded-2xl group hover:shadow-lg">
      <img
        ref="image"
        src="https://i.imgur.com/6pMAdyR.png"
        class="w-full transition-all duration-300 ease-in-out group-hover:scale-110"
      />
    </a>
  </div>
</div>

<style>
.slidev-layout a {
  border-style: none;
}
</style>

<!--
在此專案中，我也使用了 Storybook 管理元件。

Storybook 加強了設計人員與開發人員之間的協作，確保設計與開發的一致性。

像是在畫面中，我們可以直接複製樣式，或是直接在畫面上輸入資料查看更多細節的設定，以及<span style="color:red;">***參考元件使用的程式碼***</span>，讓我和工程團隊溝通更流暢。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-row items-center justify-start h-full gap-64 px-32 py-14"> 
  <p class="text-6xl font-black">Feature<br><br><br>Demo</p>
  <ul class="text-sm">
    <li>Signup</li>
    <li>Course Categories</li>
    <li>Course Page</li>
    <li>Course Application</li>
    <li>Apply Review Progress</li>
    <li>Online Consultation</li>
  </ul>
  <!-- Circle -->
  <div 
    v-motion
    :initial="{ x: -200 }"
    :enter="final"
    class="absolute -z-10 bg-blue-50 dark:bg-blue-900 rounded-full w-[700px] aspect-square -top-[1/13] -translate-y-1/2 -left-1/5">
  </div>
</div>

<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>

<!--
接下來，我們將展示平台的主要功能：

1. 註冊
2. 課程分類
3. 課程頁面
4. 課程報名
5. 報名審核進度
6. 線上諮詢
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">01</span><br><br>Signup</p>
    <p class="text-xs text-gray-500">
      Use <span v-mark.underline.orange>dynamic switching</span> to toggle between different forms, catering to different user registrations while maintaining a unified design and reducing additional development efforts.
    </p>
  </div>
  <div class="flex items-center justify-center h-full col-span-3 px-10 py-12 bg-gray-200">
    <!-- 右邊內容 -->
    <img
      ref="image"
      src="https://i.imgur.com/p981WCv.png"
      class="w-3/4 rounded-2xl"
    />
  </div>
</div>

<!--
註冊的頁面中，我們通過<span style="color:red;">***動態切換***</span>來適應<span style="color:red;">***不同的使用者類型***</span>，分為「一般使用者」及「開課單位」。

這種方法不僅保持了<span style="color:red;">***設計的一致性***</span>，還<span style="color:red;">***減少了開發成本***</span>。

此外，用戶可以選擇使用 Google 或 Facebook 帳戶進行註冊，讓註冊過程更加便捷。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">01</span><br><br>Signup</p>
    <p class="text-xs text-gray-500">
      Dynamically display fields based on different options.
    </p>
  </div>
  <div class="overflow-hidden bg-cover bg-center bg-no-repeat flex col-span-3 justify-center items-center h-full bg-gray-200 bg-[url('https://i.imgur.com/kxCbId4.png')]">
    <!-- 右邊內容 -->
    <img
      v-click
      ref="image"
      src="https://i.imgur.com/EdWAeho.png"
      class=""
    />
    <img
      v-click
      ref="image"
      src="https://i.imgur.com/iy4pMl8.png"
      class="absolute origin-right scale-[0.46]"
    />
  </div>
</div>

<!--
另外，因為對象是針對<span style="color:red;">***專業醫療人員***</span>，使用者需要根據自己的<span style="color:red;">***專業***</span>選擇不同的選項，系統會根據這些選擇<span style="color:red;">***動態調整顯示的欄位***</span>。

我也在設計檔案中同步附上了<span style="color:red;">***各種選項所產生的結果***</span>，提供工程團隊<span style="color:red;">***參考樣式變化***</span>。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">01</span><br><br>Signup</p>
    <p class="text-xs text-gray-500">
      Integrate API data to enable real-time validation, reducing manual review time.
    </p>
  </div>
  <div class="flex items-center justify-center h-full col-span-3 px-10 py-12 bg-gray-200">
    <!-- 右邊內容 -->
    <img
      ref="image"
      src="https://i.imgur.com/KuVaTU4.png"
      class="w-4/5 rounded-2xl"
    />
  </div>
</div>

<!--
由於註冊的人員多為<span style="color:red;">***專業領域的人員***</span>，對於<span style="color:red;">***身份審核上較嚴格***</span>，會有較多欄位需要填寫及上傳相關執照。

透過<span style="color:red;">***API 資料整合***</span>，系統能進行<span style="color:red;">***即時驗證***</span>，顯示<span style="color:red;">***錯誤訊息提示***</span>，這有助於他們快速修正問題，也減少了<span style="color:red;">***人工審核***</span>的需要。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">02</span><br><br>Course<br><br>Categories</p>
    <p class="text-xs text-gray-500">
      Provide a collapsible filter that allows filtering by different criteria.
      <br>
      <br>
      Courses are designed in card format, with key information displayed, allowing users to easily view required items in real time.
    </p>
  </div>
  <div class="flex items-center h-full col-span-3 px-10 bg-gray-200">
    <!-- 右邊內容 -->
    <Video
      src="https://tinaaa071.github.io/Case-Study-ppt/video5.mp4"
    />
  </div>
</div>

<!--
針對課程分類頁面，包含一個<span style="color:red;">***可折疊的篩選器***</span>，使用者可以根據各種選項對課程進行篩選和排序。

課程以卡片形式呈現，基本資訊一目了然，讓使用者能夠快速找到所需的課程。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <div class="flex flex-col">
      <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">03</span><br><br>Course<br><br>Page</p>
      <p class="text-xl font-black text-blue-500">Key Design</p>
    </div>
    <p class="text-xs text-gray-500">
      Users can instantly switch between information for easy and quick content search.
    </p>
  </div>
  <div class="flex items-center h-full col-span-3 px-10 bg-gray-200">
    <!-- 右邊內容 -->
    <Video
      src="https://tinaaa071.github.io/Case-Study-ppt/video6.mp4"
    />
  </div>
</div>

<!--
在課程詳細頁面，由於內容較為豐富，我們將資訊分為<span style="color:red;">***不同區塊***</span>來呈現。

並且加入了<span style="color:red;">***切換按鈕***</span>，讓使用者能<span style="color:red;">***快速跳轉***</span>到相關區塊，避免一一瀏覽冗長的內容。

右邊的固定式卡片包含了<span style="color:red;">***報名及諮詢***</span>按鈕，在瀏覽的同時可以隨時進行操做。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <div class="flex flex-col">
      <span class="mb-2 text-4xl font-extrabold text-blue-300">04</span>
      <span class="px-2 py-1 text-xs text-white bg-gray-400 rounded-full w-fit">
        Personal
      </span>
      <p class="text-4xl font-black">Course<br><br>Application</p>
      <p class="text-xl font-black text-blue-500">Key Design</p>
    </div>
    <p class="text-xs text-gray-500">
      Displays the application stage with a <span v-mark.underline.orange>progress bar</span>, dividing the steps to avoid a lengthy filling process.
    </p>
  </div>
  <div class="flex items-center h-full col-span-3 px-10 bg-gray-200">
    <!-- 右邊內容 -->
    <Video
      src="https://tinaaa071.github.io/Case-Study-ppt/video7.mp4"
    />
  </div>
</div>

<!--
在課程報名的部分，我設計了<span style="color:red;">***進度條***</span>來顯示報名的<span style="color:red;">***各個階段***</span>，讓使用者知道還有幾步。

另外報名系統是<span style="color:red;">***動態適應設計***</span>，根據<span style="color:red;">***選擇的人數***</span>會決定使用的是「個人報名」還是「團體報名」的模板，這個頁面是以個人報名為例，根據選擇的課程會需要填寫多項資格證明文件。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <div class="flex flex-col">
      <span class="mb-2 text-4xl font-extrabold text-blue-300">04</span>
      <span class="px-2 py-1 text-xs text-white bg-gray-400 rounded-full w-fit">
        Group
      </span>
      <p class="text-4xl font-black">Course<br><br>Application</p>
      <p class="text-xl font-black text-blue-500">Key Design</p>
    </div>
    <p class="text-xs text-gray-500">
      Dynamically adjust the fields to a group application mode based on the <span v-mark.underline.orange>number</span> of selected courses.
    </p>
  </div>
  <div class="flex items-center h-full col-span-3 px-10 bg-gray-200">
    <!-- 右邊內容 -->
    <Video
      src="https://tinaaa071.github.io/Case-Study-ppt/video8.mp4"
    />
  </div>
</div>

<!--
在團體報名部分，選擇人數大於 1 時，系統會動態調整填寫欄位，切換為「團體報名」的表單。

這種設計避免了開發兩套系統的複雜性，符合<span style="color:red;">***彈性設計原則***</span>。

另外團體報名在新增成員時使用<span style="color:red;">***抽屜式設計***</span>，會於右側跳出成員的填寫資料，對於需<span style="color:red;">***同時檢視和填寫資料***</span>上提升效率。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">05</span><br><br>Apply<br><br>Review<br><br>Progress</p>
    <p class="text-xs text-gray-500">
      Students can switch between different statuses to view the approval progress of their applied courses. Clicking on the card will display detailed information.
    </p>
  </div>
  <div class="flex items-center h-full col-span-3 px-10 bg-gray-200">
    <!-- 右邊內容 -->
    <Video
      src="https://tinaaa071.github.io/Case-Study-ppt/video9.mp4"
    />
  </div>
</div>

<!--
在完成報名後，學員可於「會員中心」檢視報名的審核進度。

學生可以<span style="color:red;">***依照狀態***</span>點擊切換按鈕，檢視各種狀態的課程。

點擊課程卡片後，可以查看該課程的詳細資訊。

並且在<span style="color:red;">***團體報名***</span>的課程中，主要報名者可以查看到所有成員的審核狀態以及詳細資料。
-->

---
transition: fade-out
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <div class="flex flex-col">
      <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">06</span><br><br>Online<br><br>Consult</p>
      <p class="text-xl font-black text-blue-500">Key Design</p>
    </div>
    <p class="text-xs text-gray-500">
      We provide an online consultation system, allowing students to instantly contact the course organizers to address related issues.
    </p>
  </div>
  <div class="flex items-center h-full col-span-3 px-10 bg-gray-200">
    <!-- 右邊內容 -->
    <Video
      src="https://tinaaa071.github.io/Case-Study-ppt/video10.mp4"
    />
  </div>
</div>

<!--
對於線上諮詢功能，列表中可以查看所有對話過的開課單位，並且也支援上傳檔案。

這項功能確保學生能即時<span style="color:red;">***獲得他們所需的資源及協助***</span>。
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-row items-center justify-start h-full gap-64 px-32 py-14"> 
  <p class="text-6xl font-black">Data <br><br><br>Analyst</p>
  <ul class="text-sm">
    <li>Google Analytics</li>
    <li>Funnel Analysis</li>
  </ul>
  <!-- Circle -->
  <div 
    v-motion
    :initial="{ x: -200 }"
    :enter="final"
    class="absolute -z-10 bg-blue-50 dark:bg-blue-900 rounded-full w-[700px] aspect-square -top-[1/13] -translate-y-1/2 -left-1/5">
  </div>
</div>

<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-col h-full py-8 px-14"> 
  <div class="space-y-2">
    <p class="text-xl font-black">Funnel Analysis (Member Registration)</p>
    <p class="text-sm">
      Out of 124 users who visited the registration page, 94 successfully completed the sign-up process, resulting in a 76% conversion rate. The most significant drop-off occurred at the “Fill in Form Fields” stage, where 10 users exited the process. This indicates potential friction due to form complexity or user hesitation. Further improvements to form design and field clarity could help optimize the completion rate.
    </p>
  </div>
  <div class="mx-auto mt-6 overflow-hidden border border-gray-300 w-2xl rounded-xl">
    <table class="w-full text-xs">
      <thead class="text-center bg-gray-100">
        <tr>
          <th class="px-4 py-2 text-center">步驟</th>
          <th class="px-4 py-2 text-center">事件名稱</th>
          <th class="px-4 py-2 text-center">使用者數</th>
          <th class="px-4 py-2 text-center">完成數</th>
          <th class="px-4 py-2 text-center">流失數</th>
          <th class="px-4 py-2 text-center">留存率</th>
        </tr>
      </thead>
      <tbody>
        <tr class="text-center">
          <td class="px-4 py-2">開啟註冊頁</td>
          <td class="px-4 py-2"><code>view_signup_page</code></td>
          <td class="px-4 py-2">124</td>
          <td class="px-4 py-2">124</td>
          <td class="px-4 py-2">-</td>
          <td class="px-4 py-2">100%</td>
        </tr>
        <tr class="text-center bg-gray-50">
          <td class="px-4 py-2">輸入 Email</td>
          <td class="px-4 py-2"><code>input_email</code></td>
          <td class="px-4 py-2">124</td>
          <td class="px-4 py-2">115</td>
          <td class="px-4 py-2">9</td>
          <td class="px-4 py-2">92.7%</td>
        </tr>
        <tr class="text-center">
          <td class="px-4 py-2">發送驗證碼</td>
          <td class="px-4 py-2"><code>send_verification_code</code></td>
          <td class="px-4 py-2">115</td>
          <td class="px-4 py-2">110</td>
          <td class="px-4 py-2">5</td>
          <td class="px-4 py-2">88.7%</td>
        </tr>
        <tr class="text-center bg-gray-50">
          <td class="px-4 py-2">填寫表單欄位</td>
          <td class="px-4 py-2"><code>complete_form_fields</code></td>
          <td class="px-4 py-2">110</td>
          <td class="px-4 py-2">100</td>
          <td class="px-4 py-2">10</td>
          <td class="px-4 py-2">80.6%</td>
        </tr>
        <tr class="text-center">
          <td class="px-4 py-2">勾選同意條款</td>
          <td class="px-4 py-2"><code>agree_terms</code></td>
          <td class="px-4 py-2">100</td>
          <td class="px-4 py-2">98</td>
          <td class="px-4 py-2">2</td>
          <td class="px-4 py-2">79.0%</td>
        </tr>
        <tr class="text-center bg-gray-50">
          <td class="px-4 py-2">點擊註冊按鈕</td>
          <td class="px-4 py-2"><code>click_signup</code></td>
          <td class="px-4 py-2">98</td>
          <td class="px-4 py-2">96</td>
          <td class="px-4 py-2">2</td>
          <td class="px-4 py-2">77.4%</td>
        </tr>
        <tr class="text-center">
          <td class="px-4 py-2">註冊成功</td>
          <td class="px-4 py-2"><code>signup_success</code></td>
          <td class="px-4 py-2">96</td>
          <td class="px-4 py-2">94</td>
          <td class="px-4 py-2">2</td>
          <td class="px-4 py-2">76.0%</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-col h-full py-8 px-14"> 
  <div class="space-y-2">
    <p class="text-xl font-black">Funnel Analysis (Course Registration)</p>
    <p class="text-sm">
      This funnel analysis compares user behavior between the "Before Optimization" and "After Optimization" course registration processes.
      <br>
      By splitting the registration into multiple steps and adding a save-draft feature, user drop-off during the form-filling stage was significantly reduced, resulting in an increase in final registration completion rate from 44.4% to 65.4%.
    </p>
  </div>
   <ToggleTable />
</div>

<style>
  .slidev-layout th {
    text-align: center;
  }
</style>

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-col h-full py-8 px-14"> 
  <div class="space-y-2">
    <p class="text-xl font-black">Funnel Analysis (Course Registration)</p>
    <p class="text-sm">
      This funnel analysis compares user behavior between the "Before Optimization" and "After Optimization" course registration processes.
      <br>
      By splitting the registration into multiple steps and adding a save-draft feature, user drop-off during the form-filling stage was significantly reduced, resulting in an increase in final registration completion rate from 44.4% to 65.4%.
    </p>
  </div>
  <div class="w-full mx-auto mt-12 overflow-hidden border border-gray-300 rounded-xl">
    <table class="w-full text-xs">
      <thead class="text-center bg-gray-100">
        <tr>
          <th class="px-4 py-2 text-center">項目</th>
          <th class="px-4 py-2 text-center">事件名稱</th>
          <th class="px-4 py-2 text-center bg-blue-100">暫存<br>使用者數</th>
          <th class="px-4 py-2 text-center bg-blue-100">暫存<br>完成數</th>
          <th class="px-4 py-2 text-center bg-blue-100">暫存<br>流失數</th>
          <th class="px-4 py-2 text-center bg-blue-100">暫存<br>留存率</th>
          <th class="px-4 py-2 text-center bg-green-100">未暫存<br>使用者數</th>
          <th class="px-4 py-2 text-center bg-green-100">未暫存<br>完成數</th>
          <th class="px-4 py-2 text-center bg-green-100">未暫存<br>流失數</th>
          <th class="px-4 py-2 text-center bg-green-100">未暫存<br>留存率</th>
        </tr>
      </thead>
      <tbody>
        <tr class="text-center">
          <td class="px-4 py-2">填寫個人資料表</td>
          <td class="px-4 py-2"><code>fill_personal_info</code></td>
          <td class="px-4 py-2 bg-blue-50">20</td>
          <td class="px-4 py-2 bg-blue-50">15</td>
          <td class="px-4 py-2 bg-blue-50">5</td>
          <td class="px-4 py-2 bg-blue-50">75.0%</td>
          <td class="px-4 py-2 bg-green-50">38</td>
          <td class="px-4 py-2 bg-green-50">35</td>
          <td class="px-4 py-2 bg-green-50">3</td>
          <td class="px-4 py-2 bg-green-50">92.1%</td>
        </tr>
        <tr class="text-center">
          <td class="px-4 py-2">填寫上傳文件表</td>
          <td class="px-4 py-2"><code>fill_upload_documents</code></td>
          <td class="px-4 py-2 bg-blue-50">18</td>
          <td class="px-4 py-2 bg-blue-50">17</td>
          <td class="px-4 py-2 bg-blue-50">1</td>
          <td class="px-4 py-2 bg-blue-50">94.4%</td>
          <td class="px-4 py-2 bg-green-50">35</td>
          <td class="px-4 py-2 bg-green-50">31</td>
          <td class="px-4 py-2 bg-green-50">4</td>
          <td class="px-4 py-2 bg-green-50">88.6%</td>
        </tr>
        <tr class="text-center">
          <td class="px-4 py-2">送出報名表單</td>
          <td class="px-4 py-2"><code>submit_registration</code></td>
          <td class="px-4 py-2 bg-blue-50">17</td>
          <td class="px-4 py-2 bg-blue-50">15</td>
          <td class="px-4 py-2 bg-blue-50">2</td>
          <td class="px-4 py-2 bg-blue-50">88.2%</td>
          <td class="px-4 py-2 bg-green-50">31</td>
          <td class="px-4 py-2 bg-green-50">29</td>
          <td class="px-4 py-2 bg-green-50">2</td>
          <td class="px-4 py-2 bg-green-50">93.5%</td>
        </tr>
        <tr class="text-center">
          <td class="px-4 py-2">報名成功頁</td>
          <td class="px-4 py-2"><code>registration_success</code></td>
          <td class="px-4 py-2 bg-blue-50">15</td>
          <td class="px-4 py-2 bg-blue-50">15</td>
          <td class="px-4 py-2 bg-blue-50">0</td>
          <td class="px-4 py-2 bg-blue-50">100.0%</td>
          <td class="px-4 py-2 bg-green-50">29</td>
          <td class="px-4 py-2 bg-green-50">27</td>
          <td class="px-4 py-2 bg-green-50">2</td>
          <td class="px-4 py-2 bg-green-50">93.1%</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<style>
  .slidev-layout th {
    text-align: center;
  }
</style>

---
transition: fade-out
class: p-0
layout: full
---

<div class="grid items-center h-full grid-cols-2 p-14"> 
  <p class="text-5xl font-black leading-loose">Continuous<br><br><br>Optimization</p>
  <ol class="space-y-8 text-base">
      <li class="font-black">
        <span class="flex items-center gap-3">
          <span class="relative flex w-3 h-3">
            <span class="absolute inline-flex w-full h-full rounded-full opacity-75 bg-sky-400 animate-ping"></span>
            <span class="relative inline-flex w-3 h-3 rounded-full bg-sky-500"></span>
          </span>
          Course Feature Expansion
        </span>
        <p class="text-xs font-normal">
          We plan to develop an online course system in the future to enhance the platform's usability and meet various needs.
        </p>
      </li>
      <li class="font-black">
        <span class="flex items-center gap-3">
          <span class="relative flex w-3 h-3">
            <span class="absolute inline-flex w-full h-full rounded-full opacity-75 bg-sky-400 animate-ping"></span>
            <span class="relative inline-flex w-3 h-3 rounded-full bg-sky-500"></span>
          </span>
          Improvement of the Course Application Process
        </span>
        <p class="text-xs font-normal">
          I am still working on improving the course application process design, particularly in providing users with a smooth experience for handling large amounts of data input.
        </p>
      </li>
      <li class="font-black">
        <span class="flex items-center gap-3">
          <span class="relative flex w-3 h-3">
            <span class="absolute inline-flex w-full h-full rounded-full opacity-75 bg-sky-400 animate-ping"></span>
            <span class="relative inline-flex w-3 h-3 rounded-full bg-sky-500"></span>
          </span>
          Online Consultation System
        </span>
        <p class="text-xs font-normal">
          Currently relying on manual responses, we aim to provide some basic intelligent customer support to alleviate issues caused by insufficient staff.
        </p>
      </li>
    </ol>
</div>

<!--
未來我們也將持續優化提升平台的功能。

***

1. 我們計劃擴展<span style="color:red;">***線上課程系統***</span>

提升平台的應用性，以更好地滿足用戶需求。

***

2. 目前，我們持續改進課程報名流程

為<span style="color:red;">***大量資料輸入***</span>的用戶提供更加流暢的體驗，預計提供批次資料上傳。

***

3. 此外，我們還計劃實施<span style="color:red;">***常見問答系統***</span>

提供基本的智慧客服支持，以解決人力不足的問題，進一步提升整體服務質量。
-->

---
class: p-0
layout: full
---

<div class="relative flex flex-col items-center justify-center h-full p-14"> 
  <p class="text-3xl font-black leading-loose">Thank You</p>
  <div class="text-sm tracking-wide text-gray-400">
    <a href="https://tinachen-portfolio.vercel.app/" target="_blank" class="">
      Portfolio
    </a>
    <span>|</span>
    <a href="https://medium.com/@tina.uiux" target="_blank" class="">
      Medium
    </a>
    <span>|</span>
    <a href="https://www.figma.com/community/plugin/1420953914431407843/shape-mask" target="_blank" class="">
      Figma Plugin
    </a>
  </div>
  <!-- Circle -->
  <div 
    v-motion
    :initial="{ x: 200 }"
    :enter="final"
    class="absolute -z-10 bg-blue-50 dark:bg-blue-900 rounded-full w-[700px] aspect-square -top-[1/13] -translate-y-1/2 -right-1/5">
  </div>
  <div 
    v-motion
    :initial="{ x: -200 }"
    :enter="final"
    class="absolute -z-10 bg-blue-50 dark:bg-blue-900 rounded-full w-[700px] aspect-square -top-[1/13] -translate-y-1/2 -left-1/5">
  </div>
</div>

<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>

<style>
.slidev-layout a {
  border-style: none;
  transition: color 0.3s ease-in-out;
}

.slidev-layout a:hover {
  color: #60a5fa;
}
</style>

<!--
感謝大家今天的參與！


如果您對其他內容感興趣，歡迎隨時查看我的作品集。
-->
