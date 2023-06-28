<template>
  <div class="app">
    <div class="nav">
      <h1></h1>
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
    width: 7em;
    border-radius: 40px;
    background-color: #1a212a;
    height: 99vh;
  }
</style>