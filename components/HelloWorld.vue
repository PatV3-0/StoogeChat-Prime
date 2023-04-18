<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="main">
    <h1 class="green">StoogeCHAT Prime</h1>
    <h3>
      This is where we'll make a chat program.
      <a href="https://www.youtube.com/watch?v=egG7fiE89IU&pp=ygUcbXkgY2hlbWljYWwgcm9tYW5jZSBuYSBuYSBuYQ%3D%3D" target="_blank" rel="noopener">Let's get going</a> 
      <a href="https://www.youtube.com/watch?v=5-sfG8BV8wU&pp=ygUXanVzdCBkbyBpdCBzaGlhIGxhYmVvdWY%3D" target="_blank" rel="noopener"> and get this done!</a>
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.main h1,
.main h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .main h1,
  .main h3 {
    text-align: left;
  }
}
</style>
