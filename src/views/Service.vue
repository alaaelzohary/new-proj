<template>
    <section>
     <Caption/>
     <Cards/>
    </section>
</template>




  

<script>
import Caption from '@/components/service/Caption.vue'
import Cards from '@/components/service/Cards.vue'

export default{
   name: "Service",
   components:{
       Caption,
       Cards
   }
}
</script>

