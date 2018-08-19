<template>
  <header class="header">
    <Hamburger class="hamburger"/>
    <h1 class="headline">100 days</h1>
  </header>
</template>

<script>
import Hamburger from './icons/Hamburger'

export default {
  name: 'Toolbar',
  components: { Hamburger }
}
</script>

<style scoped>
.header {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--white);
}

.hamburger {
  left: 0;
  position: absolute;
  cursor: pointer;
}

.headline {
  margin: 0;
  font-size: 2em;
  justify-self: center;
  font-weight: initial;
}
</style>
