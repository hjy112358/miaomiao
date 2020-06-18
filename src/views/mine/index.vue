<template>
  <div>
      <Header title='我的mine'/>
      <loginIn/>
     <tabar/>
  </div>
</template>

<script>
import Header from '@/components/Header'
import tabar from '@/components/tabar'
import loginIn from '@/components/loginIn'
export default {
  name:'mine',
   components:{
    Header,
    tabar,
    loginIn
  }
}

</script>
<style>
</style>