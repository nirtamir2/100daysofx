<template>
  <div :class="$style.card">
    <slot/>
  </div>
</template>

<script>
export default {
  name: 'Card'
}
</script>

<style module>
.card{
    background-color: var(--white);
    border-radius: 15px;
    padding: 1em;
    box-shadow: 0 3px 6px #00000025;
}
</style>
