<template>
  <button class="f-button" @click="$emit('click', $event)">
    <slot></slot>
  </button>
</template>

<script lang="ts" setup>
defineEmits(['click'])
</script>

<style scoped lang="less">
.f-button {
  appearance: none;
  padding: 5px 10px;
  background: #2080f0;
  border: none;
  border-radius: 4px;
  color: #fff;
  cursor: pointer;

  &:active {
    background: #5cb9f3;
  }
  &:not(:last-child) {
    margin-right: 15px;
  }
}
</style>