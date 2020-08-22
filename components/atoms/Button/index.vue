<template>
  <button v-bind="$attrs" @click="$emit('click')">
    <span class="label">
      {{ label }}
    </span>
  </button>
</template>

<script>
export default {
  name: "Button",
  props: {
    label: {
      type: String,
      default: () => ""
    }
  }
};
</script>

<style scoped lang="scss">
button {
  width: 100%;
  padding: 13px 0;
  background: #366858;
  border: none;
  border-radius: 5px;
  text-transform: uppercase;
  color: #fff;
  cursor: pointer;

  &:hover {
    background: #30584b;
  }

  &:focus,
  &:active {
    outline: none;
    box-shadow: none;
  }
}
</style>
