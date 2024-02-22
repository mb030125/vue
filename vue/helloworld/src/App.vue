<script setup>

import {ref,reactive} from 'vue'

const message =ref('helloworld')

message.value = 'helloworld2'

const counter = reactive({
  helloworld: 'helloworld3'
})

</script>



<template> 

  <h1>helloworld</h1><br>

  <p>{{ message }}</p><br>

  <p>{{ counter.helloworld }}</p>
  
</template> 
