<template>
  <div class="home">
    <img ref = 'aimg' alt="Vue logo" src="../assets/logo.png">
    <input ref="ing" type="text">
  </div>
</template>

<script lang="ts" setup>
let a=1
for (let index = 0; index < 5; index++) {
  a = a+index
}
console.log(a);

</script>
