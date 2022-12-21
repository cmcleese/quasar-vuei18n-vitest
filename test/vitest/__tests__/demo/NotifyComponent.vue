<script lang="ts" setup>
import { Notify } from 'quasar';
import { useI18n } from 'vue-i18n';

const { t } = useI18n();
function onClick() {
  Notify.create('Hello there!');
}
</script>

<template>
  <q-btn @click="onClick"> {{t('click')}} </q-btn>
</template>

