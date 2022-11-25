<template>
    <div class="fumetto">
        <img :src="datoFumetto.thumb" alt="">
          <h5 class="w-80">{{datoFumetto.series}}</h5>
    </div>
</template>
<script>


export default {
    props:{
        datoFumetto:Object
    }
    
}
</script>



<style scoped>

.w-80{
  width: 80%;
}
</style>
