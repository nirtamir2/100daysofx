<template>
  <div class="app">
    <Toolbar/>
    <router-view/>
  </div>
</template>
<script>
import Toolbar from '@/components/Toolbar'
import Card from '@/components/Card'

export default {
  components: { Toolbar, Card }
}
</script>
<style scoped>
.app {
  padding: 1em 1.5em 1.5em;
}
</style>
