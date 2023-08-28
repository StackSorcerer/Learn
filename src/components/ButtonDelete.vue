<script setup>
import {ref} from 'vue'
const counter = ref(0)

const increase = () => {
  counter.value++
}
const decrease = () => {
  counter.value--
}
</script>

<template>
<div class="buttons">
    {{ counter }}
    <button class="increase" @click="increase">Увелич </button>
    <button class="decrease" @click="decrease">Уменш</button>
</div>
</template>

<style scoped>
.buttons {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.increase {
  background-color: green;
}

.decrease {
  background-color: red;
}

</style>