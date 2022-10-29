<template>
  <div>
    <h1>Ola Vue</h1>
    <p>Meu nome e  {{nome}} trabalho como: {{ profissoa}}</p>
  </div>
  </template>
  
  
  <script>
  
  
  export default {
       name:'primeiroComponente',
       data(){
        return{
            nome:"Edson",
            profissoa:"programador"
        }
       }
  }
  
  </script>
  