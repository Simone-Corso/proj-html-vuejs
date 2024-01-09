<template>
  <div class="navigation-avada-consultant">
    <img :src="this.logo" alt="Logo">
  </div>
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
    .navigation-avada-consultant {
      height: 100px;
      border: 2px solid red;
    }
  </style>
  
