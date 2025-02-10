<template>
    <div class="flex relative justify-center items-center p-4 w-8/12 bg-gradient-to-br rounded-3xl h-8/12 to-green-200/20 via-purple-200/20 from-blue-300/20">
      <!-- Axes -->
      <div class="absolute inset-x-0 top-1/2 border-t border-gray-300"></div>
      <div class="absolute inset-y-0 left-1/2 border-l border-gray-300"></div>
  
      <!-- Labels -->
      <div class="absolute -left-20 top-1/2 -translate-y-full transform rotate-[-90deg]  text-gray-400 text-sm">
        General Courses
      </div>
      <div class="absolute -right-20 top-1/2 -translate-y-full transform rotate-[90deg]  text-gray-400 text-sm">
        Clinical Training
      </div>
      <div class="absolute -top-10 left-1/2 text-sm text-gray-400 -translate-x-1/2">
        Medical Expertise
      </div>
      <div class="absolute -bottom-10 left-1/2 text-sm text-gray-400 -translate-x-1/2">
        Medical Applications
      </div>
  
      <!-- Grid -->
      <div class="grid grid-cols-2 grid-rows-2 gap-8 h-full text-left text-white">
        <!-- Quadrant 1 -->
        <div class="flex flex-col justify-between p-4 h-full bg-purple-400 rounded-2xl">
          <h5 class="text-sm font-semibold">Health Care Professional Programs</h5>
          <div class="space-y-1">
            <h5 class="text-xs">• Format: Onsite, Online, Hybrid</h5>
            <h5 class="text-xs">• Apply: Personal, Group</h5>
          </div>
        </div>
  
        <!-- Quadrant 2 -->
        <div class="flex flex-col justify-between p-4 h-full bg-blue-400 rounded-2xl">
          <h5 class="text-sm font-semibold">Clinical Training Programs</h5>
          <div class="space-y-1">
            <h5 class="text-xs">• Format: Onsite, Hybrid</h5>
            <h5 class="text-xs">• Apply: Personal</h5>
          </div>
        </div>
  
        <!-- Quadrant 3 -->
        <div class="flex flex-col justify-between p-4 h-full bg-teal-400 rounded-2xl">
          <h5 class="text-sm font-semibold">Integrated Innovation Programs</h5>
          <div class="space-y-1">
            <h5 class="text-xs">• Format: Onsite, Online, Hybrid</h5>
            <h5 class="text-xs">• Apply: Personal, Group</h5>
          </div>
        </div>
  
        <!-- Empty space for layout -->
        <div></div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "CoursesDiagram",
  };
  </script>
  
  <style>
  
  </style>
  