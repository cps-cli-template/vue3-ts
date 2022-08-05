<!--
 * @Author: cpasion-office-win10 373704015@qq.com
 * @Date: 2022-08-03 16:48:03
 * @LastEditors: cpasion-office-win10 373704015@qq.com
 * @LastEditTime: 2022-08-04 16:17:28
 * @FilePath: \vue3-ts\src\App.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
// import HelloWorld from "./components/HelloWorld.vue";
// import { Menu, MenuButton, MenuItems, MenuItem } from "@headlessui/vue";
// import axios, { Axios } from "axios";

console.log(axios);

const count = ref(33333333);
console.log(count.value);
</script>

<template>
  <HelloWorld msg="Vite + Vue" />
  <Test />
  <h1 class="text-3xl font-bold underline bg-blue-500">Hello world!1</h1>
</template>

<style scoped></style>
