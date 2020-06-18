<template>
  <div>
      <Header title='我的cinma'/>
      <div id="content">
        <ul>
          <li>全程</li>
          <li>品牌</li>
          <li>特色</li>
        </ul>
        <cinlist/>
      </div>
     <tabar/>
  </div>
</template>

<script>
import Header from '@/components/Header'
import tabar from '@/components/tabar'
import cinlist from '@/components/cinlist'
export default {
  name:'cinma',
   components:{
    Header,
    tabar,
    cinlist
  }
}

</script>
<style>
</style>