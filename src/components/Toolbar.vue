<template>
  <header :class="$style.header">
    <Hamburger :class="$style.hamburger"/>
    <h1 :class="$style.headline">100 days</h1>
  </header>
</template>

<script>
import Hamburger from './icons/Hamburger'

export default {
  name: 'Toolbar',
  components: { Hamburger }
}
</script>

<style module>
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
