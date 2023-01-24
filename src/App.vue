<template>
  <div>
    <main-header />
  </div>
</template>

<script>
import MainHeader from "./components/MainHeader.vue";
import "@/assets/tailwind.css";
export default {
  name: "App",
  components: {
    MainHeader,
  },
};
</script>

<style>
*{
  background-color: black;
}
</style>
