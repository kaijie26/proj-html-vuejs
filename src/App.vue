<template>
  <div id="app">
    <HeaderComponent :menuLinks="navLinks" />
    
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'


export default {
  name: 'App',
  components: {
    HeaderComponent,
    
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
