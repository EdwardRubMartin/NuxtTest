<template>
  <div><p class="bg-pink-300 text-pink-700">Hola chicos y chicas</p></div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'AboutPage',
  mounted() {
    // eslint-disable-next-line no-console
    console.log(this.$route)
  },
})
</script>
