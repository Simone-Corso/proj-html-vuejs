<template>
    <div>
      <h1>{{ title }}</h1>
      <ul>
        <li v-for="item in menuListaUno" :key="item">{{ item }}</li>
      </ul>
      <ul>
        <li v-for="item in menuListaDue" :key="item">{{ item }}</li>
      </ul>
      <ul>
        <li v-for="item in menuListaTre" :key="item">{{ item }}</li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      title: {
        type: String,
        required: true,
      },
      menuListaUno: {
        type: Array,
        required: true,
      },
      menuListaDue: {
        type: Array,
        required: true,
      },
      menuListaTre: {
        type: Array,
        required: true,
      },
      navigationFooter: {
        type: Object,
        required: false,
      },
    },
    methods: {
      getImageUrl() {
        // Supponendo che navigationFooter sia definito
        return `/image/${this.navigationFooter.logo}?url`;
      },
    },
  };
  </script>
  
  <style scoped>
    img {
      margin-top: 2rem;
    }

    ul,li{
        list-style-type: none;
    }
  </style>
  