<template>
  <div class="navigation-avada-consultant">
    <img :src="getImageUrl(`/image/${navigationData.logo}?url`)" alt="Logo">
  </div>
  </template>
  
  <script>
  export default {
    props: {
      navigationData: {
        type: Object,  
        required: true,
      },
    },
    methods: {
      getImageUrl() {
        return `/image/${this.navigationData.logo}?url`;
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
  
