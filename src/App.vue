<script setup lang="ts">

</script>

<template>
 <div id="app">
  <div class="row">
    <span>1</span>
    <span>+</span>
    <span>1</span>
    <span>=</span>
    <span>2</span>
  </div>
  <div class="row second">
    <p>My favorite kind of taco is Al Pastor</p>
  </div>
</div>
</template>

<style>

.row {
  margin: 50px;
  display: flex;
  justify-content: center;
  font-family: 'Work Sans', sans-serif;
}

input, span {
  padding: 10px;
  font-size: 30px;
  font-family: 'Work Sans', sans-serif;
}

input {
  width: 50px;
}

span {
  width: 20px;
}

.second {
  font-size: 18px;
  p {
    margin-left: 20px;
  }
}
</style>
