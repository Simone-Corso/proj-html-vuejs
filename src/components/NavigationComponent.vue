<template>
    <img :src="this.logo" alt="Logo">
  </template>
  
  <script>
  export default {
    props: {
      navigationData: {
        type: Object,  
        required: false,
        
      },
      logo: {
        type: String,
        required: true,
      },
      menuLista: {
        type: Array,
        required: true,
      }
    },
    methods: {
      getImageUrl() {
        console.log(this);
        //return `/image/${this.navigationData.logo}?url`;
        
      },
    },
  };
  </script>
  
  <style scoped>
   img{
    margin-top: 2rem;
   }
  </style>
  
