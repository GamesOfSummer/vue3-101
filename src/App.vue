<script lang="ts">
export default {
  data() {
    return {
      message: "Hello World!",
      isRed: true,
      color: "green",
      number1: 1,
      number2: 2,
    };
  },
};
</script>

<template>
  <div id="app">
    <div class="row">
      <input v-model="number1" />

      <span>+</span>
      <input v-model="number2" />
      <span>=</span>
      <span>{{ number1 + number2 }}</span>
    </div>

    <input v-model="message" />

    {{ message }}
  </div>
</template>

<style>
.row {
  margin: 50px;
  display: flex;
  justify-content: center;
  font-family: "Work Sans", sans-serif;
}

input,
span {
  padding: 10px;
  font-size: 30px;
  font-family: "Work Sans", sans-serif;
}

input {
  width: 50px;
}

span {
  width: 20px;
}
</style>
