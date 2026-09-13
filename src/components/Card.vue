<template>
  <main class="card">
    <slot />
  </main>
</template>

<style scoped>
.card {
  width: min(600px, 100%);
  background: #fff8fb;
  padding: 18px;
  border-radius: 16px;
  box-shadow: 0 10px 24px rgba(219, 92, 142, 0.2);
}
</style>