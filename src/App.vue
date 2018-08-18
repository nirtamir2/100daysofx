<template>
  <div :class="$style.app">
    <Toolbar/>
    <router-view/>
  </div>
</template>
<script>
import Toolbar from '@/components/Toolbar.vue'
import Card from '@/components/Card.vue'

export default {
  components: {Toolbar, Card}
}
</script>
<style module>
    .app {
        padding: 1em 1.5em 1.5em;
    }
</style>
