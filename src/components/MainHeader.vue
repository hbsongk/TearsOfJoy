<template>
  <nav class="flex justify-between">
    <span id="home" class="m-8 text-3xl">TearsOfJoy</span>
    <ul
      class="mx-8 items-center hidden text-[17px] lg:flex lg:gap-8 2xl:text-[20px]"
    >
      <li>Films</li>
      <li>TV</li>
      <li>Docs</li>
      <li>Notes</li>
      <li>Shops</li>
      <li>AAA24Icon</li>
      <li>Screeningroom</li>
      <i class="fa-sharp fa-solid fa-magnifying-glass"></i>
    </ul>
    <i class="text-3xl m-8 lg:hidden fa-solid fa-bars"></i>
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
