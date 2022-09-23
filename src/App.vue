<template>
  <nav class=" navbar navbar-success bg-success">
    <span class="navbar-text">
      <p class="text-white">FastFood | Diana Laura Martinez Romero 10° "A"</p> 
    </span>
  </nav>

    <h1 align="center">Menú</h1>
    <hr />
  <card url="https://i.pinimg.com/564x/34/f4/8f/34f48f5c56c938642b80b0555e5adf82.jpg" nombre="Pizza" descripcion="Mediana Mexicana" precio="$100"/>
  <card url="https://i.pinimg.com/564x/c4/e6/11/c4e611dad9d151787d4a319410757ec9.jpg" nombre="Hamburguesa" descripcion="Doble Carne" precio="$80"/>
  <card url="https://i.pinimg.com/564x/7e/88/cd/7e88cdc14e9783a1744f2805dac4c20c.jpg" nombre="Sándwich" descripcion="Jamon De Pavo" precio="$55"/>
  <card url="https://i.pinimg.com/564x/6b/16/4e/6b164e621f26fa773a4d060fc4661455.jpg" nombre="Papas" descripcion="Francesa" precio="$45"/>  
  <card url="https://i.pinimg.com/564x/3c/a6/f4/3ca6f4118f5969256ffb82fcaaeb3b0c.jpg" nombre="Hog-Dog" descripcion="2x1" precio="$60"/>  
  <card url="https://i.pinimg.com/564x/2c/8c/11/2c8c11dc2a85739e46fe73ebe7f661ec.jpg" nombre="Nachos" descripcion="Con Arrachera" precio="$50"/>  

  <br><br><br><br><br>
  
  <footer>
    <p align="center">Copyright 2022©</p>
    <p align="center">Contáctanos al 230-875-96-50</p>
  </footer>
</template>

<script>
  import Card from "./components/Card.vue";
  import Nav from "./components/Nav.vue";
  export default{
    components: { Card, Nav },
  };
</script>

