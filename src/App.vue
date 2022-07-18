<template>
  <div id="app">
    <HeaderComponent :menuLinks="navLinks" />
    <main>
      <SectionSpecialties/>

    </main>
    
    
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import SectionSpecialties from './components/SectionSpecialties.vue'


export default {
  name: 'App',
  components: {
    HeaderComponent,
    SectionSpecialties,
    
  },

  data(){
    return{
      navLinks:[
        {
          text: 'HOMES',
          url: '#',
          current: true
        },
        {
          text: 'PAGES',
          url: '#',
          current: false
        },
        {
          text: 'BLOG',
          url: '#',
          current: false
        },
        {
          text: 'SHOP',
          url: '#',
          current: false
        },
        {
          text: 'EVENTS',
          url: '#',
          current: false
        },
        {
          text: 'ELEMENTS',
          url: '#',
          current: false
        },
      ]


    }
  },

  methods:{
    

  }

  
}

</script>

<style lang="scss">
@import './style/common';


</style>
