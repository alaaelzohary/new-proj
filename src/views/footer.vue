<template>
  <section>
    <Section1/>
    <Section2/>

  </section>
</template>

<script>
// @ is an alias to /src
import Section1 from '@/components/footer/Section1.vue'
import Section2 from '@/components/footer/Section2.vue'
export default{
  name: 'Footer',
  components: {
    Section1,
    Section2

  }
}
</script>