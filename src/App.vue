<template>
  <div class="bg-gray-100 h-100">
    <header class="bg-white shadow-md h-16 flex justify-between items-stretch">
      <router-link :to="{ name: 'home' }"> Home </router-link>
      <div class="flex items-center gap-1">
        <router-link
          to="/"
          class="inline-flex items-center px-2 h-full transition-colors hover:bg-purple-100"
          >Search Meals</router-link
        >
        <router-link
          to="/"
          class="inline-flex items-center px-2 h-full transition-colors hover:bg-purple-100"
          >Meals By Letter</router-link
        >
        <router-link
          to="/"
          class="inline-flex items-center px-2 h-full transition-colors hover:bg-purple-100"
          >Meals By Ingredients</router-link
        >
      </div>
    </header>
    <main>
      <router-view />
    </main>
  </div>
</template>
//PAREI NO 46:00
<script setup></script>

<style scoped></style>
