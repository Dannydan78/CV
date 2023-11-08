<script setup>

import Sidebar from '@/components/Sidebar.vue';
import Header from '@/components/Header.vue';
import Content from '@/components/Content.vue';

</script>


<template>
  <div class="flex h-100">
    <Sidebar />
    <div class="flex-1 p-4">
      <Header />
      <div class="mt-5">
        <Content />
      </div>
    </div>
  </div>
  <!-- <div class="mt- bg-gradient-to-b from-purple-500 to-blue-500 h-40"></div> -->
  <!-- <div class="bg-gray-900 mt-10 h-10"></div> -->
</template>







