<template>
   <div class="containerImagem">
    <img style=" width: 100%;" src="@/assets/dezembro.jpg" alt="imagem 1">
    </div>
    <div class="divImagemMeiaTela">
        <img src="@/assets/mapa.png" alt="imagem 2">
        <img src="@/assets/cafethe.jpg" alt="imagem 3">  
      </div>
     
    </template>
    
    <script>
    export default {
        name: 'ImagensDiversos',
        props: {
            msg: String 
        }
    }
    </script>
    
    <!--Add "scoped" atribute to limite css to this component only-->
    <style scoped></style>