<template>
  <button :class="[$style.button, secondary ? $style.secondary : $style.primary]">
    <slot/>
  </button>
</template>

<script>
export default {
  name: 'DButton',
  props: {
    secondary: { type: Boolean, default: false }
  }
}
</script>

<style module>
.button {
  outline: none;
  background-color: var(--blue);
  color: var(--white);
  padding: 0.5em 1.5em;
  font-size: 1em;
  border: 1px solid var(--blue);
  border-radius: 18px;
  cursor: pointer;
  box-shadow: 0 3px 6px #00000016;
  transition: box-shadow 0.2s ease-in;

  &:hover {
    box-shadow: 0 3px 10px #00000048;
  }
}

.secondary {
  color: var(--blue);
  background-color: var(--white);
}
</style>
