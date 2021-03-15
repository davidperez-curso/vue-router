<template>
  <div class="home container">
    
    <Cabecera/>
    <Lista/>
    <button @click="irFotos">Fotos</button>
    
    
  </div>
</template>

<script>
// @ is an alias to /src

import Cabecera from '@/components/Cabecera.vue'
import Lista from '@/components/Lista.vue'

export default {
  name: 'Home',
  components: {
    Cabecera,
    Lista
  },
  methods: {
    irFotos(){
      this.$router.push('/fotos/1')
    }
  },
  
}
</script>
