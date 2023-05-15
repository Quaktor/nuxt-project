<template>
    <div>
     <TopNav/>
      <div class="about">Strona o nas

      <button @click="showInfo">Press me</button>
    </div>
  </div>
  </template>
  
  <script>
  import TopNav from '~/components/navi/TopNav.vue';

  export default {
    name: 'AboutPage',
    components: { TopNav },

    methods: {
        showInfo: () => {
            alert('Alert');
            console.log('Konsola')
        }
    }
  }
  </script>
  
  <style scoped>

  .about{
    padding: 15px 5px 10px 30px;
    font-family: 'Raleway', sans-serif;
    font-size:larger;
    font-size: 20px;
    gap: 20px;
  }
  </style>
  