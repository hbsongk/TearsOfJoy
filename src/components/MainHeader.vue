<template>
  <nav class="flex justify-between md:text-xl text-2xl">
    <span id="home" class="m-8 text-3xl">TearsOfJoy</span>
    <ul class="hidden md:flex md:block md:gap-12 md:m-8">
      <li>Films</li>
      <li>TV</li>
      <li>Docs</li>
      <li>Notes</li>
      <li>Shops</li>
      <li>AAA24Icon</li>
      <li>ScreeningroomIcon</li>
      <li>SearchingIcon</li>
    </ul>
    <i class="text-3xl m-8 md:hidden fa-solid fa-bars"></i>
  </nav>
</template>

<script>
export default {
  name: "MainHeader",
};
</script>

<style scoped>
* {
  color: white;
}
#home {
  font-family: sans-serif;
}
</style>
