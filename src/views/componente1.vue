<template>
<div class="pantallacom">
    <div class="divi">
        <div class="cont"> 
         CONTENIDO 1 
        </div>
        <div class="cont">
         CONTENIDO 2
        </div>
    </div>
    <div> 
    </div>
</div>
</template>

<style scoped>

.pantallacom{
    width: 100vh;
    height: 100vh;
    display: grid;
    grid-template-columns: 50% 50%;
}

.divi{
    grid-column-start: 2;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    align-content: center;
}

.cont{
    width: 20vh;
    height: 15vh;
    box-shadow: black;
    border-radius: 10px;
    margin-bottom: 1em;
    border-color: beige;
}

</style>