<template>
  <button>
    <slot>CREATE</slot>
  </button>
</template>

<script setup>

</script>

<style lang="scss" scoped>
  button {
    padding: 8px 16px;
    border: none;
    cursor: pointer;
    transition: all .4s ease-in-out;

    &:hover {
      background-color: #41b080;
      color: white;
    }

  }
</style>