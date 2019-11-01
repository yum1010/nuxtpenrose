<template>
  <v-layout
    column
    justify-center
    align-center
  >
   <board :N="N"></board>
  </v-layout>
</template>

<script>
import board from '~/components/board.vue'

export default{
  components:{
      board
  },
    data(){
	return{
	    N:2
	}
    }
    
}
</script>
