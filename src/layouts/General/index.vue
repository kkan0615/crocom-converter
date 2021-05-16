<template>
  <main
    class="h-full w-full"
  >
    <header-general-layout
      class="mb-1"
    />
    <router-view />
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HeaderGeneralLayout from '@/layouts/General/components/Header.vue'

export default defineComponent({
  name: 'GeneralLayout',
  components: {
    HeaderGeneralLayout
  },
  setup () {
    return
  }
})
</script>
