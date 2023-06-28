<template>
  <div class="app">
    <div class="cont">
      <div class="var">
        <div class="var-contenedor">
          <h1>PANEL DE CONTENIDO DE NAV BAR</h1>
        </div>
      </div>
      <div class="nav">
        <div class="view-contenedor">
          <h1>PANEL DE CONTENIDO</h1>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>

  .app{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    width: 100%;
    background-color: #636c3c;
  }
  .cont{
    display: flex;
    justify-content: flex-end;
    height: 96vh;
    width: 124em;
    border-radius: 40px;
    background-color: #929f59;
    margin-bottom: 1em;
  }

  .var{
    margin-top: 1.2em;
    margin-right: 1.2em;
    height: 96%;
    width: 30%;
  }

  .nav{
    height: 96%;

    width: 65%;
    margin-top: 1.2em;
    margin-right: 1.2em;
    background-color: white;
    border-radius: 40px;
  }
</style>