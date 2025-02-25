<template>
  <q-layout class="column justify-center items-center">
    <HeaderMain />
    <!-- Основное содержимое страницы -->
    <q-page-container class="main-content" q-scroll-area>
      <q-page>
        <MainHomePageComponent />
        <MainHomePageComponent />
        <MainHomePageComponent />
        <MainHomePageComponent />
        <MainHomePageComponent />
        <MainHomePageComponent />
        <MainHomePageComponent />
        <MainHomePageComponent />
        <MainHomePageComponent />
        <MainHomePageComponent />
        <MainHomePageComponent />
        <MainHomePageComponent />
        <MainHomePageComponent />
      </q-page>
    </q-page-container>

    <!-- Подвал -->
    <q-footer>
      Footer
    </q-footer>
  </q-layout>
</template>

<script setup lang="ts">
import MainHomePageComponent from 'components/MainHomePage.vue';
import HeaderMain from 'components/header/main-header-page.vue'
</script>

<style scoped lang="sass">
/* Дополнительные стили, если они необходимы */
</style>
