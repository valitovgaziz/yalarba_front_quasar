<template>
  <!-- Заголовок -->
  <q-header hide-on-scroll>
    <q-toolbar>
      <q-toolbar-title>
        {{ t('appName') }}
      </q-toolbar-title>
      <q-btn flat dense round icon="menu" />
    </q-toolbar>
  </q-header>
</template>


<script setup lang="ts">
import { useI18n } from 'vue-i18n';
const { t } = useI18n();

</script>


<style scoped lang="sass">
</style>
