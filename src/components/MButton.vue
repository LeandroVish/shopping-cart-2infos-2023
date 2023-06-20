<script setup>
const props = defineProps({
  text: String
})
</script>

<template>
  <button>{{ props.text }}</button>
</template>

<style scoped>
button {
  background-color: red;
  color: white;
  border: 1px solid gray;
  border-radius: 5px;
  padding: 10px;
  font-size: 1.2rem;
  cursor: pointer;
  margin: 5px;
}

button:hover {
  background-color: darkred;
}
</style>
