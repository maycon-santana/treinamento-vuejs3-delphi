<script setup lang="ts">

</script>

<template>
  <div class="app-background">
    <header class="app-header">
      <h1>Sistema Financeiro</h1>
    </header>
  </div>
</template>

<style scoped>
html, 
body {
  font-family: "Segoe UI";
  margin: 0;
  padding: 0;
}

.app-background {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
  background-color: white;
}

.app-header {
  background-color: darkblue;
  width: 100vw;
  text-align: center;
  height: 130px;
  font-family: "Poppins", "sans-serif";
  letter-spacing: 2px;
  padding-top: 20px;
}

.app-header h1 {
  margin: 0;
  padding: 0;
  font-size: calc(20px + 2vmin);
  color: #fff;
  padding-top: 30px;
}
</style>
