<template>
  <div class="app">
    <div class="nav">
      <h1>hola mundo</h1>
    </div>
  </div>
</template>

<style scoped>
  .app{
    display: grid;
    grid-template-columns: 15% 90%;
    grid-template-rows: 2fr 100px;
    grid-column-gap: 20px;
    grid-row-gap: 20px;
    justify-items: stretch;
    align-items: stretch;
  }
  .nav{
    position: absolute;
    background-color: azure;
    height: 100vh;
  }
</style>