<script>

export default {
  data: () => ({
    contador: 0
  }),
  methods: {
    sumar(){
      this.contador++;
    },
    Restar(){
      this.contador--;
    },
    Limpiar(){
      this.contador = 0;
    }
  },
};

</script>

<template>
  <div class="container">
      <img src="./assets/logo.svg" alt="logo vue" width="125" height="125"/>
  <small>
    <h1>Contador de jeremmy prueba VUE.js</h1>
  </small>
  <hr/>
  <h2>Contador: {{ contador }}</h2>
  <button @click="sumar()">+1</button>
  <button @click="Restar()">1</button>
  <button @click="Limpiar()">Reset</button>
  </div>
  
</template>
<style scoped>

.container{
  text-align: center;
}
small{
  color: blueviolet;
}
h2{
  font-size: 2.5rem;
}
button{
  cursor: pointer;
  font-size: 1.5rem;
  margin: 0px 6px;
}


/* h1{
  color: black;
} */
</style>
                I

