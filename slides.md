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
    class="object-cover object-top shadow-lg  rounded-[32px] aspect-[3/4]"
  />
  </div>
  <div class="w-full">
    <p class="text-2xl font-black">
      Hi teams! It's me,
    </p>
    <p class="pb-6 text-6xl font-black">
      Tina Chen
    </p>
    <p class="pb-4 text-sm tracking-wide text-gray-500 ">
      A <span class="font-extrabold">UI/UX designer</span> with 3 years of experience, integrating diverse expertise in UX research and UI design, combined with software development and business administration to create impactful product designs.
    </p>
    <div class="flex gap-3 text-xs tracking-wide ">
      <p class="px-4 py-2 text-blue-400 bg-blue-100 rounded-full"># Passion Driven</p>
      <p class="px-4 py-2 text-blue-400 bg-blue-100 rounded-full"># Curious-Minded</p>
      <p class="px-4 py-2 text-blue-400 bg-blue-100 rounded-full"># Fast Learner</p>
    </div>
  </div>
</div>

<style>
  .slidev-layout p {
    line-height: unset;
    margin: 0;
}
</style>

<!--
Hi everyone, I’m Tina.

I’m a UI/UX designer with 3 years of experience, and I also have a Master’s degree in Business Administration.

I focus on creating designs that are not only user-friendly but also enjoyable to interact with.
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
Next, I’d like to share my work experience.

Before becoming a UI/UX designer, I worked as a <span style="color:red;">**researcher and a PM**</span>. These roles helped me build skills in <span style="color:red;">**data analysis, market research, and cross-team communication**</span>.

I’m now a UI/UX designer at UARK, where I work on end-to-end product design. 

And I team up with engineers, PMs, and other departments to make sure our designs are not only user-friendly but also practical to build.
-->

---
transition: slide-up
class: p-0
layout: full
hide: true
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
    <div class="flex flex-col items-center">
      <img
        ref="image"
        src="https://i.meee.com.tw/SYdgcm7.png"
        class="object-cover object-center shadow  rounded-[64px] aspect-square"
      />
      <p>
        Learning
      </p>
    </div>
    <div class="flex flex-col items-center">
      <a href="https://cafe2-ecru.vercel.app/" target="_blank" class=" shadow rounded-[64px] overflow-hidden">
        <img
          ref="image"
          src="https://i.imgur.com/v9ocHR9.jpeg"
          class="object-cover object-center transition-all duration-200 aspect-square hover:scale-110"
        />
      </a>  
      <p>
        Cafe
      </p>
    </div>
    <div class="flex flex-col items-center">
      <a href="https://www.figma.com/community/plugin/1420953914431407843/shape-mask" target="_blank" class=" shadow rounded-[64px] overflow-hidden">
        <img
          ref="image"
          src="https://cdn-images-1.medium.com/max/1600/1*VUK2az0HJHzilzN0Rpgv0A.png"
          class="object-cover object-center transition-all duration-200 aspect-square hover:scale-110"
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
In my leisure time, I enjoy traveling, watching movies, and learning new things.

I also built a Figma plugin on my own, and after releasing it, I was invited by the Adobe team for a possible collaboration. 

I’d be happy to share more about that later if we have time.
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
      <p class="text-base tracking-wider text-gray-400">
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
Next, I will introduce our project – “Health Academy”.
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-row items-center justify-start h-full gap-64 px-32 py-14"> 
  <p class="text-6xl font-black">Agenda</p>
  <ol class="list-decimal text-md">
    <li><a href="7" class="transition-colors duration-200">Background</a></li>
    <li><a href="13" class="transition-colors duration-200">Research & Define</a></li>
    <li><a href="18" class="transition-colors duration-200">Design System</a></li>
    <li><a href="26" class="transition-colors duration-200">Feature Demo</a></li>
    <li><a href="36" class="transition-colors duration-200">Data Analyst</a></li>
  </ol>
  <!-- Circle -->
  <div 
    v-motion
    :initial="{ x: -200 }"
    :enter="final"
    class="absolute -z-10 bg-blue-50 dark:bg-blue-900 rounded-full w-[700px] aspect-square -top-[1/13] -translate-y-1/2 -left-1/5">
  </div>
</div>

<style>
a, a:hover {
  border-style: none;
}
a:hover {
  color: #93c5fd;
}
</style>

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
Here’s today’s agenda. 

I’ll walk through the design process of this project.
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-col justify-between h-full p-14"> 
  <div class="space-y-2">
    <p class="text-2xl font-black text-blue-400">Background</p>
    <p class="text-sm">
      This platform is designed to provide a comprehensive overview of Taiwan's medical and health training courses and achievements for <span class="text-blue-300 underline underline-offset-4 ">foreign medical professionals</span>. It also offers more complete training information and application services through the platform.
    </p>
  </div>
  <div class="grid grid-cols-4 gap-6 px-6 pb-3 bg-blue-50 rounded-2xl">
    <div class="space-y-2">
      <p class="text-xl font-black text-blue-400">Role</p>
      <ul class="text-xs">
        <li>UI/UX Designer</li>
        <li>Product Roadmap</li>
      </ul>
    </div>
    <div class="space-y-2">
      <p class="text-xl font-black text-blue-400">Team</p>
      <ul class="text-xs">
        <li>1 Product Designer</li>
        <li>1 Product Manager</li>
        <li>1 Systems Analysis</li>
        <li>1 Front-end Developer</li>
        <li>3 Back-end Developer</li>
      </ul>
    </div>
    <div class="space-y-2">
      <p class="text-xl font-black text-blue-400">Timeline</p>
      <p class="text-xs">
        More than 1 year
        <br>
        <span class="text-gray-400">
          (2023.10 - Now)
        </span>
      </p>
    </div>
    <div class="space-y-2">
      <p class="text-xl font-black text-blue-400">Company</p>
      <p class="text-xs">
        Joint Commission of Taiwan
      </p>
    </div>
  </div>
</div>

<!--
This project main goal is to share Taiwan’s medical resources with international healthcare professionals and encourage learning and collaboration.

The project includes both front-end and back-end design, but today I’ll focus on the front-end part.

In this project, I worked as the UI/UX designer.

I closely collaborated with a cross-functional team — including the project manager, system analyst, and engineers.
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-col justify-between h-full p-14"> 
  <div class="space-y-2">
    <p class="text-2xl font-black text-blue-400">Design Flow</p>
    <p class="text-sm">
      In this project, I focused on designing the overall <span class="text-blue-300 underline underline-offset-4 ">website architecture</span> to ensure users could <span class="text-blue-300 underline underline-offset-4 ">browse courses and complete the application process</span>. My primary responsibility was to plan an online course application system that is user-friendly and allows users to verify their application results. 
      <br>
      <br>
      The goal of the platform is to foster closer medical exchange and collaboration with other countries, promoting the bidirectional sharing of knowledge and skills.
    </p>
  </div>
  <div class="grid grid-cols-4 gap-6 px-6 pb-3 bg-blue-50 rounded-2xl">
    <div class="space-y-2">
      <p class="text-xl font-black text-blue-400">Research</p>
      <ul class="text-xs">
        <li>Website IA</li>
        <li>Course Information Display Requirements</li>
        <li>Course Application and Review System</li>
      </ul>
    </div>
    <div class="space-y-2">
      <p class="text-xl font-black text-blue-400">Define</p>
      <ul class="text-xs">
        <li>Website Design Specifications</li>
        <li>Registration system for different roles</li>
        <li>Online Course Application Workflow</li>
        <li>Online Course Application Review Process</li>
      </ul>
    </div>
    <div class="space-y-2">
      <p class="text-xl font-black text-blue-400">Design</p>
      <ul class="text-xs">
        <li>Component Design</li>
        <li>Website UI Design</li>
        <li>Design System</li>
        <li>Responsive Website Compatibility</li>
      </ul>
    </div>
    <div class="space-y-2">
      <p class="text-xl font-black text-blue-400">Test & Iteration</p>
      <ul class="text-xs">
        <li>Usability Testing</li>
        <li>Collect Feedback</li>
        <li>Data Analyst</li>
      </ul>
    </div>
  </div>
</div>

<!--
Our goal was to create a website that feels intuitive and friendly, so users can easily browse courses and complete their registration.

Our design process included user research, feature planning, and ongoing design iterations to keep improving the experience.
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-col h-full py-8 px-14"> 
  <p class="text-2xl font-black">
  ☹️ User Pain Point
  </p>
  <div class="grid grid-cols-3 gap-6 mt-4">
    <div class="px-4 py-1 bg-blue-100 rounded-2xl">
      <p class="px-2 py-1 text-sm font-black text-blue-400 bg-white rounded-md">1. Hospital publicity is weak</p>
      <p class="text-xs">
        The hospital's authoritative departments are fully equipped but <span class="text-blue-400 underline underline-offset-4 ">take a more low-profile approach in promotion</span>.
      </p>
    </div>
    <div class="px-4 py-1 bg-blue-100 rounded-2xl">
      <p class="px-2 py-1 text-sm font-black text-blue-400 bg-white rounded-md">2. Insufficient training information</p>
      <p class="text-xs">
        Training information is insufficient, making it <span class="text-blue-400 underline underline-offset-4 ">difficult to clearly understand the overall application process</span>.
      </p>
    </div>
    <div class="px-4 py-1 bg-blue-100 rounded-2xl">
      <p class="px-2 py-1 text-sm font-black text-blue-400 bg-white rounded-md">3. Training results and evaluations</p>
      <p class="text-xs">
        Overseas personnel find it <span class="text-blue-400 underline underline-offset-4 ">difficult to access training results and evaluations</span>, making it challenging to showcase training achievements externally.
      </p>
    </div>
    <div class="px-4 py-1 bg-blue-100 rounded-2xl">
      <p class="px-2 py-1 text-sm font-black text-blue-400 bg-white rounded-md">4. Issues with document resubmission</p>
      <p class="text-xs">
        The process of submitting supplementary documents is <span class="text-blue-400 underline underline-offset-4 ">time-consuming, labor-intensive, and disorganized</span>.
      </p>
    </div>
    <div class="px-4 py-1 bg-blue-100 rounded-2xl">
      <p class="px-2 py-1 text-sm font-black text-blue-400 bg-white rounded-md">5. Customized training programs</p>
      <p class="text-xs">
        Overseas healthcare personnel have <span class="text-blue-400 underline underline-offset-4 ">clear learning goals and require customized training programs</span>.
      </p>
    </div>
  </div>
</div>

<!--
Through user feedback and interviews, we identified several key pain points for users:

<span style="color:red;">**1. Hospital publicity is weak**</span>

Although Taiwan’s hospitals offer strong medical resources, they often keep a low profile in promotion. As a result, users don’t get enough information about the available courses.

<span style="color:red;">**2. Lack of clear training information**</span>

The information is scattered and unclear. Users find it hard to understand the course details and application process, which affects their willingness to participate.

<span style="color:red;">**3. No feedback or reviews from past courses**</span>

Overseas professionals have difficulty finding course results or participant feedback. This makes it hard for them to choose the right training program.

<span style="color:red;">**4. Repeated document submission**</span>

Users often need to submit many documents, especially for professional qualification checks. The process is time-consuming and frustrating, which lowers their motivation to apply.

<span style="color:red;">**5. Need for personalized training plans**</span>

Medical professionals usually look for specific course plans to meet their learning goals, but current options don’t support this level of customization.
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid items-center h-full grid-cols-2 p-14"> 
  <p class="text-6xl font-black">Our Goal</p>
  <div class="grid grid-cols-1 gap-1.5 tracking-wide">
    <div class="px-4 rounded-lg bg-blue-50">
      <p class="text-xs tracking-wide">
        1. Establish a<span class="text-blue-400 underline underline-offset-4 "> registration system</span>that includes authentication
      </p>
    </div>
    <div class="px-4 rounded-lg bg-blue-50">
      <p class="text-xs tracking-wide">
        2. <span class="text-blue-400 underline underline-offset-4 ">Integrate course resources</span> from national medical institutions
      </p>
    </div>
    <div class="px-4 rounded-lg bg-blue-50">
      <p class="text-xs tracking-wide">
        3. Provide<span class="text-blue-400 underline underline-offset-4 "> multi-language</span> switch for the website
      </p>
    </div>
    <div class="px-4 rounded-lg bg-blue-50">
      <p class="text-xs tracking-wide">
        4. Provide course<span class="text-blue-400 underline underline-offset-4 "> classification and filtering functions</span>
      </p>
    </div>
    <div class="px-4 rounded-lg bg-blue-50">
      <p class="text-xs tracking-wide">
        5. Provide<span class="text-blue-400 underline underline-offset-4 "> individual and group application functions</span> for courses
      </p>
    </div>
    <div class="px-4 rounded-lg bg-blue-50">
      <p class="text-xs tracking-wide">
        6. Allow participants to view the<span class="text-blue-400 underline underline-offset-4 "> application review results</span>
      </p>
    </div>
    <div class="px-4 rounded-lg bg-blue-50">
      <p class="text-xs tracking-wide">
        7. Students can<span class="text-blue-400 underline underline-offset-4 "> consult</span> with the course provider online
      </p>
    </div>
  </div>
</div>

<!--
Here are some goals of this project, like:
1. Build a registration system with identity verification.
2. Integrate course resources from medical institutions across Taiwan.
3. Provide a multilingual website, so users from different regions can access it easily.
4. Offer course categories and filters to help users quickly find what they need.
5. Support both individual and group registration, to meet different learning needs.
6. Allow users to track their application status after signing up.
7. Enable online consultation, so students can get support and guidance when needed.
-->

---
transition: slide-up
class: p-0
layout: full
hide: true
---

<div class="grid items-center h-full grid-cols-2 p-14"> 
  <p class="text-6xl font-black">Solution</p>
  <div class="grid grid-cols-1 gap-1.5 tracking-wide">
    <div class="px-4 rounded-lg bg-blue-50">
      <p class="text-xs tracking-wide">
        ✅  Design a document upload and<span class="text-blue-400 underline underline-offset-4 "> automatic verification</span> system
      </p>
    </div>
    <div class="px-4 rounded-lg bg-blue-50">
      <p class="text-xs tracking-wide">
        ✅  <span class="text-blue-400 underline underline-offset-4 ">Provide course information and</span> filtering functions
      </p>
    </div>
    <div class="px-4 rounded-lg bg-blue-50">
      <p class="text-xs tracking-wide">
        ✅  Display course training<span class="text-blue-400 underline underline-offset-4 "> evaluation results</span>
      </p>
    </div>
    <div class="px-4 rounded-lg bg-blue-50">
      <p class="text-xs tracking-wide">
        ✅  Establish a<span class="text-blue-400 underline underline-offset-4 "> multilingual</span> frameworks
      </p>
    </div>
    <div class="px-4 rounded-lg bg-blue-50">
      <p class="text-xs tracking-wide">
        ✅  Create a<span class="text-blue-400 underline underline-offset-4 "> dual application mode</span> with dynamic forms
      </p>
    </div>
    <div class="px-4 rounded-lg bg-blue-50">
      <p class="text-xs tracking-wide">
        ✅  Develop a application<span class="text-blue-400 underline underline-offset-4 "> status tracking</span> feature
      </p>
    </div>
    <div class="px-4 rounded-lg bg-blue-50">
      <p class="text-xs tracking-wide">
        ✅  Build an<span class="text-blue-400 underline underline-offset-4 "> online consultation system</span> to provide real-time assistance
      </p>
    </div>
  </div>
</div>

<!--
Based on the user pain points and project goals, we came up with the following solutions:
1. Designed an automated identity verification system to improve efficiency.
2. Added course information and filtering tools to help users easily find what fits their needs.
3. Displayed feedback and results from past training courses, so users can better understand course quality.
4. Built a multilingual framework to support users from different countries.
5. Created a dual registration mode to support both individual and group sign-ups.
6. Developed a status tracking feature, so users can check their registration progress and approval results at any time.
7. Set up an online consultation system to provide real-time help and support.
-->

---
transition: slide-left
class: p-0
layout: full
hide: true
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
          <ul class="text-gray-400">
            <li>Courses categorized by <span class="text-blue-300 underline underline-offset-4 ">professional fields</span>.</li>
            <li>The color selection is composed of stable and <span class="text-blue-300 underline underline-offset-4 ">medical</span> tones.</li>
          </ul>
        </span>
      </li>
      <li>
        Enhancing User Experience
        <br>
        <span>
          <ul class="text-gray-400">
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
After analyzing user needs, I set two key design directions.

The first is audience-focused:

a. Make sure courses are categorized by professional fields.

b. Choose colors that convey professionalism and trust.

***

The second focuses on user experience, especially the workflow, like:

a. Provide customizable search and filter options for courses.

b. Keep the application process simple.

c. Show clear course review status.
-->

---
transition: slide-up
class: p-0
layout: full
hide: true
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

<div class="flex flex-col h-full p-14"> 
  <div class="space-y-2">
    <p class="text-xl font-black text-blue-400">Competitive Analysis</p>
    <p class="text-sm">
      I researched products on the market with similar course application features but did not find a suitable example.<br> We found the functions in this project to be very <span class="text-blue-300 underline underline-offset-4 ">creative</span>, which makes it a <span class="text-blue-300 underline underline-offset-4 ">challenge</span> for our team.
    </p>
  </div>
  <div class="grid grid-cols-3 mt-6 gap-y-6 gap-x-32">
    <div class="space-y-3 text-center">
      <div class="overflow-hidden border border-gray-100 rounded-2xl aspect-video">
        <img
          ref="image"
          src="https://i.imgur.com/7VlO2nB.png"
          class="w-full h-full transition-all duration-200 ease-in-out hover:scale-110"
        />
      </div>
      <p class="text-sm font-black">Hahow</p>
    </div>
    <div class="space-y-3 text-center">
      <div class="overflow-hidden border border-gray-100 rounded-2xl aspect-video">
        <img
          ref="image"
          src="https://i.imgur.com/IZHmUjI.png"
          class="w-full h-full transition-all duration-200 ease-in-out hover:scale-110"
        />
      </div>
      <p class="text-sm font-black">Udemy</p>
    </div>
    <div class="space-y-3 text-center">
      <div class="overflow-hidden border border-gray-100 rounded-2xl aspect-video">
        <img
          ref="image"
          src="https://i.imgur.com/BM5WXVl.png"
          class="w-full h-full transition-all duration-200 ease-in-out hover:scale-110"
        />
      </div>
      <p class="text-sm font-black">Coursera</p>
    </div>
    <div class="space-y-3 text-center">
      <div class="overflow-hidden border border-gray-100 rounded-2xl aspect-video">
        <img
          ref="image"
          src="https://i.imgur.com/G2pCFYH.png"
          class="w-full h-full transition-all duration-200 ease-in-out hover:scale-110"
        />
      </div>
      <p class="text-sm font-black">Future Learn</p>
    </div>
    <div class="space-y-3 text-center">
      <div class="overflow-hidden border border-gray-100 rounded-2xl aspect-video">
        <img
          ref="image"
          src="https://i.imgur.com/mHWGOe8.png"
          class="w-full h-full transition-all duration-200 ease-in-out hover:scale-110"
        />
      </div>
      <p class="text-sm font-black">Techable</p>
    </div>
    <div class="space-y-3 text-center">
      <div class="overflow-hidden border border-gray-100 rounded-2xl aspect-video">
        <img
          ref="image"
          src="https://i.imgur.com/IL9zMOt.png"
          class="w-full h-full transition-all duration-200 ease-in-out hover:scale-110"
        />
      </div>
      <p class="text-sm font-black">Klook</p>
    </div>
  </div>
</div>

<!--
Since our timeline was tight, I focused on researching several well-established platforms to guide our feature design.

Our project needed to support both individual and group application, as well as qualification review — which made the requirements more complex.
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
I created the information architecture to map out how pages and features are connected.
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
Here’s the user flow, using the course application process as an example.

In this flow, we used a dynamic layout system that adapts depending on whether the user is registering as an individual or a group.

If the number of participants is more than one, the system will automatically switch to the group registration layout.
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
For the design system, I defined a few key areas to help our team stay consistent, like:
1. Variable settings
2. Multilingual settings
3. Figma design files
4. Storybook management
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
    <p class="text-xs text-gray-500 ">
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
For variable settings, since our project uses Tailwind CSS, I included related variables directly in the design.

Like spacing, border radius, and more to keep the design consistent.
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
    <p class="text-xs text-gray-500 ">
      You can click directly on the component in the interface to view the related values and variable names.
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
The variables we defined show up directly on the components, making it easy for developers to reference them quickly.
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
    <p class="text-xs text-gray-500 ">
      I’ve set up multilingual variables and organized them by component/page.
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
I also set up multilingual variables to make switching and viewing content in different languages easier.
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
    <p class="text-xs text-gray-500 ">
      In the development process, switching views within the file with a single click helps improve efficiency.
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
As you can see in the video, we can switch languages directly from the design panel.

It makes it easy for developers to reference the styles for each language.
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
    <p class="text-xs text-gray-500 ">
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
I also created a Figma Library file where we defined a complete design system and various components.

Each component is labeled with its use case, states, and details.

Having this design system helps improve efficiency, especially when updating large files.
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
    <p class="text-xs text-gray-500 ">
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
I organized the pages by different use cases and arranged them according to the user flow.

In addition, I presented responsive designs to show how each page looks on different devices.
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
    <p class="text-xs text-gray-500 ">
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
In this project, I also used Storybook to manage components.

Storybook really improves collaboration between designers and developers, making sure design and development stay consistent.

For example, in the interface, we can copy styles directly, input data to see more detailed settings, and check the code used by components.

This makes communication with the engineering team much smoother.
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
Next, I’ll show you the main features of the platform:

1. Registration
2. Course categories
3. Course page
4. Course application
5. Application review progress
6. Online consultation
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
    <p class="text-xs text-gray-500 ">
      Use <span v-mark.underline.orange>dynamic switching</span> to toggle between different forms, catering to different user registrations while maintaining a <span v-mark.underline.orange>unified design</span> and reducing additional development efforts.
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
On the registration page, we use dynamic switching to adapt to different user types: general users and course providers.

This approach keeps the design consistent and helps reduce development costs.

Plus, users can register easily using their Google or Facebook accounts, making the sign-up process quicker and smoother.
-->

---
transition: slide-up
class: p-0
layout: full
hide: true
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">01</span><br><br>Signup</p>
    <p class="text-xs text-gray-500 ">
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
    <p class="text-xs text-gray-500 ">
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
With API data integration, the system can verify information in real time and show error messages.

This helps users quickly fix issues and reduces the need for manual review.
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
    <p class="text-xs text-gray-500 ">
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
On the course categories page, there’s a collapsible filter where users can sort and filter courses based on different options.

Courses are displayed as cards, showing the key information, so users can quickly find what they need.
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <div class="flex flex-col gap-2">
      <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">03</span><br><br>Course<br><br>Page</p>
      <span class="px-3 py-2 text-xs font-black text-white bg-blue-500 rounded-full w-fit">⭐️ Key Design</span>
    </div>
    <p class="text-xs text-gray-500 ">
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
On the course detail page, since there’s a lot of information, we divided the content into different sections.

We also added tabs so users can quickly jump to the parts they want, without scrolling through everything.

On the right side, there’s a fixed card, so users can take action anytime while browsing.
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <div class="flex flex-col gap-2">
      <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">04</span><br><br><span class="underline underline-offset-4 decoration-dashed decoration-2 decoration-blue-300">Personal</span><br><br>Course<br><br>Application</p>
      <span class="px-3 py-2 text-xs font-black text-white bg-blue-500 rounded-full w-fit">⭐️ Key Design</span>
    </div>
    <p class="text-xs text-gray-500 ">
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
For the course application, I designed a progress bar to show the steps, so users always know how many steps are left.

And the registration system is dynamic — it switches between individual and group registration templates depending on the number of people.
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <div class="flex flex-col gap-2">
      <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">04</span><br><br><span class="underline underline-offset-4 decoration-dashed decoration-2 decoration-blue-300">Group</span><br><br>Course<br><br>Application</p>
      <span class="px-3 py-2 text-xs font-black text-white bg-blue-500 rounded-full w-fit">⭐️ Key Design</span>
    </div>
    <p class="text-xs text-gray-500 ">
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
When adding members in group registration, we use a drawer-style panel that slides in from the right, allowing users to view and fill out member information efficiently
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
    <p class="text-xs text-gray-500 ">
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
After completing registration, students can check their application status in the member center.

By clicking on a course card, they can see detailed information about that course.
-->

---
transition: fade-out
class: p-0
layout: full
---

<div class="grid h-full grid-cols-4 gap-4">
  <div class="flex flex-col justify-between h-full col-span-1 px-10 py-6">
    <!-- 左邊內容 -->
    <div class="flex flex-col gap-2">
      <p class="text-4xl font-black"><span class="font-extrabold text-blue-300">06</span><br><br>Online<br><br>Consult</p>
      <span class="px-3 py-2 text-xs font-black text-white bg-blue-500 rounded-full w-fit">⭐️ Key Design</span>
    </div>
    <p class="text-xs text-gray-500 ">
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
For the online consultation feature, users can see a list of all course providers they’ve talked to, and the system also supports file uploads.

This ensures students get the resources and help they need in real time.
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

<!--
Finally, we used data analysis to gather feedback and improve our design.
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-col h-full py-8 px-14"> 
  <div class="space-y-2">
    <p class="text-xl font-black text-blue-400">Funnel Analysis (Member Registration)</p>
    <p class="text-sm">
      Out of 124 users who visited the registration page, 94 successfully completed the sign-up process, resulting in a 76% conversion rate. <br><span class="text-blue-300 underline underline-offset-4 ">The most significant drop-off occurred at the “Fill in Form Fields” stage</span>, where 10 users exited the process. This indicates potential friction due to <span class="text-blue-300 underline underline-offset-4 ">form complexity or user hesitation</span>. Further improvements to form design and field clarity could help optimize the completion rate.
    </p>
  </div>
  <div class="mx-auto mt-6 overflow-hidden border border-gray-300 w-2xl rounded-xl">
    <table class="w-full text-xs text-gray-900 bg-white">
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
        <tr class="text-center bg-red-100">
          <td class="px-4 py-2">填寫表單欄位</td>
          <td class="px-4 py-2"><code>complete_form_fields</code></td>
          <td class="px-4 py-2">110</td>
          <td class="px-4 py-2">100</td>
          <td class="px-4 py-2 text-red-500">10</td>
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

<!--
We used funnel analysis for the member registration feature.
Out of 124 users who visited the registration page, 94 completed the signup, resulting in a 76% conversion rate.

The biggest drop-off happened at the form filling stage, where 10 users left halfway.

This suggests that the form’s complexity or user hesitation might be causing barriers.

Improving the form design and making the fields clearer could help increase completion rates.
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-col h-full py-8 px-14"> 
  <div class="space-y-2">
    <p class="text-xl font-black text-blue-400">Funnel Analysis (Course Application)</p>
    <p class="text-sm">
      This funnel analysis compares user behavior between the "Before Optimization" and "After Optimization" course application processes.
      <br>
      By <span class="text-blue-300 underline underline-offset-4 ">splitting the registration into multiple steps</span>, user drop-off during the form-filling stage was significantly reduced, resulting in an increase in final registration completion rate from 48.6% to 75%.
    </p>
  </div>
   <ToggleTable />
</div>

<style>
  .slidev-layout th {
    text-align: center;
  }
</style>

<!--
On the course registration page, we compared user behavior before and after optimization.

After splitting the registration into multiple steps, we significantly reduced drop-offs during the form-filling stage.
As a result, the completion rate increased from 48.6% to 75%.
-->

---
transition: slide-up
class: p-0
layout: full
---

<div class="flex flex-col h-full py-8 px-14"> 
  <div class="space-y-2">
    <p class="text-xl font-black text-blue-400">Funnel Analysis (Course Application)</p>
    <p class="text-sm">
      Segmented analysis shows that the final completion rate for users who utilized the save progress feature was 90.2%, which is higher than that of users who did not use the feature. This indicates that <span class="text-blue-300 underline underline-offset-4 ">the save-draft progress function significantly enhances users’ willingness and experience in completing the registration process</span>.
    </p>
  </div>
  <div class="mt-4">
    <div class="flex gap-6">
      <div class="text-sm">
        <span class="inline-flex w-3 h-3 mr-1 bg-green-200 rounded-full"></span>
        有暫存
      </div>
      <div class="text-sm">
        <span class="inline-flex w-3 h-3 mr-1 bg-red-200 rounded-full"></span>
        無暫存
      </div>
    </div>
    <div class="w-full mx-auto mt-4 overflow-hidden border border-gray-300 rounded-xl">
      <table class="w-full text-xs text-gray-900 bg-white">
        <thead class="text-center bg-gray-100">
          <tr>
            <th class="px-4 py-2 text-center">項目</th>
            <th class="px-4 py-2 text-center bg-green-200">使用者數</th>
            <th class="px-4 py-2 text-center bg-green-200">完成數</th>
            <th class="px-4 py-2 text-center bg-green-200">該步驟流失數</th>
            <th class="px-4 py-2 text-center bg-green-200">回訪數</th>
            <th class="px-4 py-2 text-center bg-green-200">流失率(%)</th>
            <th class="px-4 py-2 text-center bg-red-200">使用者數</th>
            <th class="px-4 py-2 text-center bg-red-200">完成數</th>
            <th class="px-4 py-2 text-center bg-red-200">該步驟流失數</th>
            <th class="px-4 py-2 text-center bg-red-200">回訪數</th>
            <th class="px-4 py-2 text-center bg-red-200">流失率(%)</th>
          </tr>
        </thead>
        <tbody>
          <tr class="text-center">
            <td class="px-4 py-2">開始填答</td>
            <td class="px-4 py-2 bg-green-50">72</td>
            <td class="px-4 py-2 bg-green-50">72</td>
            <td class="px-4 py-2 bg-green-50">-</td>
            <td class="px-4 py-2 bg-green-50">-</td>
            <td class="px-4 py-2 bg-green-50">-</td>
            <td class="px-4 py-2 bg-red-50">72</td>
            <td class="px-4 py-2 bg-red-50">72</td>
            <td class="px-4 py-2 bg-red-50">-</td>
            <td class="px-4 py-2 bg-red-50">-</td>
            <td class="px-4 py-2 bg-red-50">-</td>
          </tr>
          <tr class="text-center">
            <td class="px-4 py-2">填寫個人資料表</td>
            <td class="px-4 py-2 bg-green-50">55</td>
            <td class="px-4 py-2 bg-green-50">38</td>
            <td class="px-4 py-2 bg-green-50">17</td>
            <td class="px-4 py-2 bg-green-50">10</td>
            <td class="px-4 py-2 bg-green-50">23.6%</td>
            <td class="px-4 py-2 bg-red-50">65</td>
            <td class="px-4 py-2 bg-red-50">58</td>
            <td class="px-4 py-2 bg-red-50">7</td>
            <td class="px-4 py-2 bg-red-50">-</td>
            <td class="px-4 py-2 bg-red-50">9.7%</td>
          </tr>
          <tr class="text-center">
            <td class="px-4 py-2">填寫上傳文件表</td>
            <td class="px-4 py-2 bg-green-50">48</td>
            <td class="px-4 py-2 bg-green-50">41</td>
            <td class="px-4 py-2 bg-green-50">7</td>
            <td class="px-4 py-2 bg-green-50">17</td>
            <td class="px-4 py-2 bg-green-50">12.7%</td>
            <td class="px-4 py-2 bg-red-50">55</td>
            <td class="px-4 py-2 bg-red-50">45</td>
            <td class="px-4 py-2 bg-red-50">10</td>
            <td class="px-4 py-2 bg-red-50">-</td>
            <td class="px-4 py-2 bg-red-50">15.4%</td>
          </tr>
          <tr class="text-center">
            <td class="px-4 py-2">最終完成報名</td>
            <td class="px-4 py-2 bg-green-50">65</td>
            <td class="px-4 py-2 bg-green-50"><span v-mark.circle.orange>65<br>(90.2%)</span></td>
            <td class="px-4 py-2 bg-green-50">-</td>
            <td class="px-4 py-2 bg-green-50">-</td>
            <td class="px-4 py-2 bg-green-50">-</td>
            <td class="px-4 py-2 bg-red-50">45</td>
            <td class="px-4 py-2 bg-red-50">45<br>(62.5%)</td>
            <td class="px-4 py-2 bg-red-50">-</td>
            <td class="px-4 py-2 bg-red-50">-</td>
            <td class="px-4 py-2 bg-red-50">-</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
  <p class="text-sm">
      Overall, <span class="text-blue-300 underline underline-offset-4 ">splitting the process into steps and providing a save-draft function</span> are key optimization strategies for increasing registration conversion rates.
    </p>
</div>

<style>
  .slidev-layout th {
    text-align: center;
  }
</style>

<!--
Group analysis shows that users who used the draft feature had higher retention rates at each key step.

This indicates that the draft feature significantly improves users’ willingness and experience to complete their registration.
-->

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
Looking ahead, we will continue to improve and enhance the platform’s features.

We plan to expand the online course system to make the platform more useful and better meet users’ needs.

Right now, we’re improving the course application process to offer a smoother experience for users handling large amounts of data, including batch data uploads.

Additionally, we plan to implement a FAQ system to provide basic smart customer support, helping to address staffing shortages and improve overall service quality.
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
Thank you all for joining today!
-->
