<template>
  <q-layout view="LHH lPr fFf">
    <!-- Заголовок -->
    <q-header elevated>
      <q-toolbar>
        <q-toolbar-title>
          {{ t('appName') }}
        </q-toolbar-title>
        <q-btn flat dense round icon="menu" />
      </q-toolbar>
    </q-header>

    <!-- Основное содержимое страницы -->
    <q-page-container>
      <q-page>
        <MainHomePageComponent />
      </q-page>
    </q-page-container>

    <!-- Подвал -->
    <q-footer elevated>
      Footer
    </q-footer>
  </q-layout>
</template>

<script setup lang="ts">
import MainHomePageComponent from 'components/MainHomePage.vue';
import { useI18n } from 'vue-i18n';
const { t } = useI18n();
</script>

<style scoped lang="scss">
/* Дополнительные стили, если они необходимы */
</style>
