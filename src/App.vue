<template>
<div>
  <primeiroComponente/>
  <p>O dado  de app e:</p>

  <Lifecycle/>
</div>
</template>


<script>

import primeiroComponente from './components/primeiroComponente.vue'
import Lifecycle from './components/Lifecycle.vue';
export default {
     name:'App',
     components:{
      primeiroComponente,
      Lifecycle
     },
     data(){
      return{
        testando:"teste"

      }
     }
}

</script>
