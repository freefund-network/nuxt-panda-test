<script setup lang="ts">
import { css } from "styled-system/css";
import { hstack, vstack } from "styled-system/patterns";
</script>
 
<template>
  <div :class="vstack({})">
    <div :class="css({ fontSize: '5xl', fontWeight: 'bold' })">Hello 🐼!</div>
    <div :class="css({ fontSize: '3xl' })">Welcome to your Vite + Vue 3 + TS + TailwindCSS + Styled System app</div>
  </div>
</template>
