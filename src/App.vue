<template>
  <div class="app">
    <div class="cont">
      <div class="var">
        <div class="var-contenedor">
          <div class="bar">
            <div class="botones">
              <h1 class="barTitle">Menu</h1>
              <div class="boton-label"><button class="b1"> <icono_home :class="brillo"/></button>
                <label for="b1">Home</label>
              </div> 
              <div class="boton-label"><button class="b2"> <icono_uploads/></button>
                <label for="b2">Uploads</label>
              </div> 
              <div class="boton-label"><button class="b3"> <icono_message/></button>
                <label for="b3">Messages</label>
              </div> 
              <div class="boton-label"><button class="b4"> <icono_storage/></button>
                <label for="b4">Storage</label>
              </div> 
              <div class="boton-label"><button class="b5"> <icono_media/></button>
                <label for="b5">Media</label>
              </div> 
              <div class="boton-label"><button class="b6"> <icono_apps/></button>
                <label for="b6">Apps</label>
              </div> 
              <div class="boton-label"><button class="b7"> <icono_cloud/></button>
                <label for="b7">Cloud</label>
              </div> 
              <div class="boton-label"><button class="b8"> <icono_trash/> </button>
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

<script setup>
import icono_message from './components/icons/icono_message.vue';
import icono_apps from './components/icons/icono_apps.vue';
import icono_cloud from './components/icons/icono_cloud.vue';
import icono_home from './components/icons/icono_home.vue';
import icono_media from './components/icons/icono_media.vue';
import icono_storage from './components/icons/icono_storage.vue';
import icono_trash from './components/icons/icono_trash.vue';
import icono_uploads from './components/icons/icono_uploads.vue';
</script>
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
    background-color: #89993f;
    margin-bottom: 1em;
  }

  .var{
    margin-top: 1.2em;
    margin-right: 1.2em;
    height: 96%;
    width: 20%;
  }

  .nav{
    height: 96%;
    width: 75%;
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
    display: flex;
    flex-direction: column;
    align-content: center;
    gap: 0.7em;
  }

  .barTitle{
  font-family: Arial, sans-serif;
  font-size: 23px;
  color: white;

  }
  button {
    background-color: #cdda84;
    border-radius: 13px;
    width: 3.5em;
    height: 3.5em;
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