<script setup>
import Navigation from "./components/Navigation.vue";
import CardList from "./components/CardList.vue";
import Software from "./components/Software.vue";
</script>

<template>
  <header class="bg-green-400 max-w-[350px] w-full">
    <Navigation />
  </header>

  <main class="w-full flex">
    <section class="bg-[#F8F8F8 ] max-w-[492px] h-[100vh] w-full py-[56px]">
      <CardList />
    </section>
    <section class="px-[86px] pt-[56px] w-full g-red-400">
      <Software/>
    </section>
  </main>
</template>

<style>
#app {
  display: flex;
}
</style>
