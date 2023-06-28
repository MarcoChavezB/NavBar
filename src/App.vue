<template>
  <div class="app">
    <div class="cont">
      <div class="var">
        <div class="var-contenedor">
          <div class="bar">
            <div class="botones">
              <h1 class="barTitle">Menu</h1>
              <div class="boton-label"><button class="b1"></button>
                <label for="b1">Home</label>
              </div> 
              <div class="boton-label"><button class="b2"></button>
                <label for="b2">Uploads</label>
              </div> 
              <div class="boton-label"><button class="b3"></button>
                <label for="b3">Messages</label>
              </div> 
              <div class="boton-label"><button class="b4"></button>
                <label for="b4">Storage</label>
              </div> 
              <div class="boton-label"><button class="b5"></button>
                <label for="b5">Media</label>
              </div> 
              <div class="boton-label"><button class="b6"></button>
                <label for="b6">Apps</label>
              </div> 
              <div class="boton-label"><button class="b7"></button>
                <label for="b7">Cloud</label>
              </div> 
              <div class="boton-label"><button class="b8"></button>
                <label for="b8">Trash</label>
              </div> 
            </div>
          </div>
        </div>
      </div>
      <div class="nav">
        <div class="view-contenedor">
          <h1></h1>
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
    background-color: #e0e7bd;
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
  .bar {
    
    display: flex;
    flex-direction: column;
    height: 92vh;
    width: 80%;
    border-radius: 30px;
  }
  .botones{
    display: grid;
    grid-template-columns: 1fr;
    gap: 0.7em;
    margin-top: 33%;
  }
  .barTitle{
  font-family: Arial, sans-serif;
  font-size: 23px;
  color: white;

  }
  button {
    border-radius: 13px;
    width: 3.5em;
    height: 3.5em;
    background-color: transparent;
    border: 2px solid  white;
    transition: transform 0.3s, margin-left 0.3s;
    margin-right: 0.5em;
  }
  button:hover {
    background-color: white;
    transform: scale(1.3);
    margin-left: -1em;
  }
  .boton-label {
  display: flex;
  align-items: center;
}
label{
  margin-left: 0.5em;
  font-family: Arial, sans-serif;
  font-size: 19px;
  color: white;
}
</style>