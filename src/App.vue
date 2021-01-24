<template>
  <div class="px-4 py-10 text-center text-gray-300 mx-auto w-10/12">
    <TheHeader />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import TheHeader from './components/TheHeader.vue'

export default defineComponent({
  name: 'App',
  components: {
    TheHeader
  }
})
</script>
