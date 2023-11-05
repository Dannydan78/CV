<script setup>

import Sidebar from '@/components/Sidebar.vue';
import Header from '@/components/Header.vue';
import Content from '@/components/Content.vue';

</script>


<template>
  <div class="flex h-screen">
    <Sidebar />
    <div class="flex-1 p-4">
      <Header />
      <div class="mt-5">
        <Content />
      </div>
    </div>
  </div>
</template>







