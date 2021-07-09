<template>
  <div class="container">
    <VacationPicker />
  </div>
</template>

<script>

import VacationPicker from '@/components/VacationPicker'

export default {
   name: 'app',
    components:{
      VacationPicker
   } 
 }
</script>
<style> 
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: bottom;
  text-align: center;
  color: #0d7ceb;
  margin-top: 60px;
  background: linear-gradient(to right, #66FF00 , #0066FF) ;
}
#img{
  border-radius: 10%;
}
</style>
