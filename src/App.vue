<template>
  <div id="app">
    <HeaderComponent :menuLinks="navLinks" />
    <main>
      <SectionSpecialties />
      <SectionTeam />

    </main>
    
    
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import SectionSpecialties from './components/SectionSpecialties.vue'
import SectionTeam from './components/SectionTeam.vue'


export default {
  name: 'App',
  components: {
    HeaderComponent,
    SectionSpecialties,
    SectionTeam
    
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
