<script setup>
import IButton from './components/IButton.vue'
const darc = 'bg'
</script>

<template>
  <div class="red">hello vue <IButton :class="darc"></IButton></div>
</template>

<style>
.bg {
  background-color: green;
}
.red {
  display: flex;
  align-items: center;
  gap: 50px;
  margin: 80px;
}
</style>
