---
# try also 'default' to start simple
theme: apple-basic 
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: /image/Home.png
# some information about your slides, markdown enabled
title: Welcome to Slidev
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply any unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-center
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true

layout: intro-image
image: '/image/Home.png'
---

<div class="absolute bottom-10 text-black text-left left-10">
  <h1>Title<br>Evaluation</h1>
</div>

---
transition: fade-out
class: p-0
---

<div class="grid grid-cols-4 gap-4 h-full">  <!-- 設定網格容器高度填滿 -->
  <div class="col-span-1 bg-red-200 h-full">  <!-- 左邊 1/4，並設定高度填滿 -->
    <!-- 左邊內容 -->
    <p>左邊內容</p>
  </div>
  <div class="col-span-3 h-full">  <!-- 右邊 3/4，並設定高度填滿 -->
    <!-- 右邊內容 -->
    <p>右邊內容</p>
  </div>
</div>

---
transition: slide-up
level: 2
---

# Skills
<br>
<div class="flex gap-4 flex-wrap">
  <span class="px-3 py-2 rounded" style="background-color: #FDED98">效率</span>
  <span class="px-3 py-2 rounded" style="background-color: #FDED98">洞察需求</span>
  <span class="px-3 py-2 rounded" style="background-color: #FDED98">即時反應需求</span>
  <span class="px-3 py-2 rounded" style="background-color: #FDED98">對公司產品理解</span>
  <span class="px-3 py-2 rounded" style="background-color: #FDED98">溝通協調</span>
  <span class="px-3 py-2 rounded" style="background-color: #FDED98">設計實作</span>
  <span class="px-3 py-2 rounded" style="background-color: #FDED98">商業分析與研究</span>
  <span class="px-3 py-2 rounded" style="background-color: #FDED98">產品技術邏輯</span>
  <span class="px-3 py-2 rounded" style="background-color: #FDED98">設計趨勢</span>
  <span class="px-3 py-2 rounded" style="background-color: #FDED98">研究方法</span>
  <span class="px-3 py-2 rounded" style="background-color: #FDED98">產業趨勢</span>
  <span class="px-3 py-2 rounded" style="background-color: #FDED98">分析能力</span>
  <span class="px-3 py-2 rounded" style="background-color: #FDED98">專案管理</span>
  <span class="px-3 py-2 rounded" style="background-color: #FDED98">風險評估</span>
  <span class="px-3 py-2 rounded" style="background-color: #FDED98">時間管理</span>
  <span class="px-3 py-2 rounded" style="background-color: #FDED98">自我學習能力</span>
  <span class="px-3 py-2 rounded" style="background-color: #FDED98">學習新技術</span>
</div>
<br>
<div class="flex gap-4 flex-wrap">
  <span class="px-3 py-2 rounded" style="background-color: #F4B461">Vue + Vite</span>
  <span class="px-3 py-2 rounded" style="background-color: #F4B461">AI</span>
</div>

---
layout: section
---

<div class="w-fit">
  <h1>台灣 UX 工作者<span class="text-sm">（不含海外）</span></h1>
  <h1 class="border-b-8 border-[#F4B461]">年薪平均 <span class="font-semibold text-[#F4B461]">88 萬</span>，中位數 <span class="font-semibold text-[#F4B461]">77 萬</span></h1>
  <div class="space-x-4 pt-2">
    <span class="px-3 py-2 border-3 rounded-lg border-[#F4B461]">104</span>
    <span class="px-3 py-2 border-3 rounded-lg border-[#F4B461]">1111</span>
    <span class="px-3 py-2 border-3 rounded-lg border-[#F4B461]">設計師協會</span>
    <span class="px-3 py-2 border-3 rounded-lg border-[#F4B461]">台灣薪資情報網</span>
  </div>
</div>

---
layout: intro-image
image: '/image/Salary.png'
---

# <p class="absolute top-8 text-black text-left left-8 text-4xl">Annual Salary</p>

---
level: 2
---

# Future

<div class="space-y-4">
  <div class="bg-[#FDED98] px-4 py-1 border-l-12 border-[#F4B461] rounded-lg">
    <p class="text-xl font-semibold">專業技能</p>
    <p class="text-md">
      提升中大型專案管理能力，於開發期視專案開發需求調整設計介面，減少溝通成本。維護良好產品品質，建立企業形象。
    </p>
  </div>
  <div class="bg-[#FDED98] px-4 py-1 border-l-12 border-[#F4B461] rounded-lg">
    <p class="text-xl font-semibold">管理能力</p>
    <p>
      學習更有效管理整體進度並適時的調整項目流程，解決衝突來完成項目。
    </p>
  </div>
  <div class="bg-[#FDED98] px-4 py-1 border-l-12 border-[#F4B461] rounded-lg">
    <p class="text-xl font-semibold">學習與創新</p>
    <p>
      保持追蹤市場設計趨勢與新技術，精進 UI/UX 等領域專業知識，學習新技術如互動設計，將 AI 導入工作中。
    </p>
  </div>
</div>