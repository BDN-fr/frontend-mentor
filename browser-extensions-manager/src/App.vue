<script setup>
import Extension from './components/extension.vue'
</script>

<template>
<div>
  <Extension
  :name="'test'"
  :description="'test'"
  :is-active=true
  :logo="'./assets/images/logo-devlens.svg'"
  />
</div>
</template>

<style scoped>

</style>

<style>
:root {
  /* Neutral Colors */
  --neutral-900: hsl(227, 75%, 14%);
  --neutral-800: hsl(226, 25%, 17%);
  --neutral-700: hsl(225, 23%, 24%);
  --neutral-600: hsl(226, 11%, 37%);
  --neutral-300: hsl(0, 0%, 78%);
  --neutral-200: hsl(217, 61%, 90%);
  --neutral-100: hsl(0, 0%, 93%);
  --neutral-0: hsl(200, 60%, 99%);

  /* Red Colors */
  --red-400: hsl(3, 86%, 64%);
  --red-500: hsl(3, 71%, 56%);
  --red-700: hsl(3, 77%, 44%);

  /* Gradients */
  --light-gradient: linear-gradient(180deg, #EBF2FC 0%, #EEF8F9 100%);
  --dark-gradient: linear-gradient(180deg, #040918 0%, #091540 100%);
}

/* Typography */
body {
  font-family: 'Noto Sans', sans-serif;
  font-size: 16px;
  color: var(--neutral-0);
}

h1, h2, h3, h4, h5, h6 {
  font-weight: 700;
}

p {
  font-weight: 400;
}
</style>