<script>
  export default{
    data:() => ({
        contador:1,
    }),

    methods:{
      saludar(){
        console.log("Hola 10A | @")
      },

      incrementar(){
        this.contador++;
      },
      decrementar(){
        this.contador--;
      },
      resetear(){
        this.contador = 0;
      }

    }
  }
</script>

<template>
  <nav class="navbar sticky-top navbar-dark bg-dark">
    <div class="container-fluid">
          <a class="navbar-brand h1">Luis Enrique Mendez Lezama 10° "A" DMI</a>       
    </div>
  </nav>
  
  <div class="container">

    <img src="./assets/logo.svg" alt="Logo VUE" width="125" height="125">
    <small>
      <h1>Hola desde VUE.JS 3</h1>
    </small>
    <hr>
    <h2>Contador {{contador}}</h2>
    <button @click="incrementar()">+1</button>
    <button @click="decrementar()">-1</button>
    <button @click="resetear()">Reset</button>
    <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
 
  </div>
</template>

<style scoped>
  .container{
    text-align: center;
  }
  small{
    color: #666;
  }
  h1 {
    font-weight: bolder;
  }
  h2{
    font-size: 2.5rem;
  }
  button{
    cursor:pointer;
    font-size: 1.5rem;
    margin: 0pc 8px;
  }
  nav a{
    margin: auto;
  }
</style>
