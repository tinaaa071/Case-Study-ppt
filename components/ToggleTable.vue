<template>
    <div class="flex mt-4">
        <button @click="toggleTable" class="px-2 py-1 text-xs text-white bg-blue-500 rounded h-fit">
        {{ showFirstTable ? 'Default' : 'Split' }}
        </button>
  
   <div v-if="showFirstTable" class="mx-auto overflow-hidden border border-gray-300 w-2xl rounded-xl">
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
        <td class="px-4 py-2">查看課程詳情</td>
        <td class="px-4 py-2"><code>view_course_detail</code></td>
        <td class="px-4 py-2">72</td>
        <td class="px-4 py-2">72</td>
        <td class="px-4 py-2">0</td>
        <td class="px-4 py-2">100%</td>
        </tr>
        <tr class="text-center bg-gray-50">
        <td class="px-4 py-2">點擊報名按鈕</td>
        <td class="px-4 py-2"><code>click_register_button</code></td>
        <td class="px-4 py-2">64</td>
        <td class="px-4 py-2">64</td>
        <td class="px-4 py-2">8</td>
        <td class="px-4 py-2">88.9%</td>
        </tr>
        <tr class="text-center bg-red-50">
        <td class="px-4 py-2">填寫報名表單</td>
        <td class="px-4 py-2"><code>fill_registration_form</code></td>
        <td class="px-4 py-2">58</td>
        <td class="px-4 py-2 text-red-500">38</td>
        <td class="px-4 py-2 text-red-500">20</td>
        <td class="px-4 py-2 text-red-500">52.8%</td>
        </tr>
        <tr class="text-center bg-gray-50">
        <td class="px-4 py-2">送出報名表單</td>
        <td class="px-4 py-2"><code>submit_registration</code></td>
        <td class="px-4 py-2">38</td>
        <td class="px-4 py-2">32</td>
        <td class="px-4 py-2">6</td>
        <td class="px-4 py-2">44.4%</td>
        </tr>
        <tr class="text-center">
        <td class="px-4 py-2">報名成功頁</td>
        <td class="px-4 py-2"><code>registration_success</code></td>
        <td class="px-4 py-2">32</td>
        <td class="px-4 py-2">32</td>
        <td class="px-4 py-2">0</td>
        <td class="px-4 py-2">44.4%</td>
        </tr>
    </tbody>
    </table>
  </div>
  <div v-else class="mx-auto overflow-hidden border border-gray-300 w-2xl rounded-xl">
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
          <td class="px-4 py-2">查看課程詳情</td>
          <td class="px-4 py-2"><code>view_course_detail</code></td>
          <td class="px-4 py-2">72</td>
          <td class="px-4 py-2">72</td>
          <td class="px-4 py-2">0</td>
          <td class="px-4 py-2">100%</td>
        </tr>
        <tr class="text-center">
          <td class="px-4 py-2">點擊報名按鈕</td>
          <td class="px-4 py-2"><code>click_register_button</code></td>
          <td class="px-4 py-2">64</td>
          <td class="px-4 py-2">64</td>
          <td class="px-4 py-2">8</td>
          <td class="px-4 py-2">88.9%</td>
        </tr>
        <tr class="text-center">
          <td class="px-4 py-2">確認報名課程</td>
          <td class="px-4 py-2"><code>confirm_registration</code></td>
          <td class="px-4 py-2">62</td>
          <td class="px-4 py-2">62</td>
          <td class="px-4 py-2">2</td>
          <td class="px-4 py-2">86.1%</td>
        </tr>
        <tr class="text-center bg-blue-50">
          <td class="px-4 py-2">填寫個人資料表</td>
          <td class="px-4 py-2"><code>fill_personal_info</code></td>
          <td class="px-4 py-2">58</td>
          <td class="px-4 py-2">50</td>
          <td class="px-4 py-2">8</td>
          <td class="px-4 py-2">69.4%</td>
        </tr>
        <tr class="text-center bg-blue-50">
          <td class="px-4 py-2">填寫上傳文件表</td>
          <td class="px-4 py-2"><code>fill_upload_documents</code></td>
          <td class="px-4 py-2">50</td>
          <td class="px-4 py-2">48</td>
          <td class="px-4 py-2">2</td>
          <td class="px-4 py-2">66.7%</td>
        </tr>
        <tr class="text-center bg-blue-50">
          <td class="px-4 py-2">送出報名表單</td>
          <td class="px-4 py-2"><code>submit_registration</code></td>
          <td class="px-4 py-2">48</td>
          <td class="px-4 py-2">47</td>
          <td class="px-4 py-2">1</td>
          <td class="px-4 py-2">65.4%</td>
        </tr>
        <tr class="text-center">
          <td class="px-4 py-2">報名成功頁</td>
          <td class="px-4 py-2"><code>registration_success</code></td>
          <td class="px-4 py-2">47</td>
          <td class="px-4 py-2">47</td>
          <td class="px-4 py-2">0</td>
          <td class="px-4 py-2"><span v-mark.circle.orange>65.4%</span></td>
        </tr>
      </tbody>
    </table>
  </div>
    </div>
  </template>
  
  <style>
    .slidev-layout th {
        text-align: center;
    }
  </style>

  <script>
  export default {
    data() {
      return {
        showFirstTable: true,  // 控制目前顯示哪個表格
      };
    },
    methods: {
      toggleTable() {
        this.showFirstTable = !this.showFirstTable;
      },
    },
  };
  </script>
  