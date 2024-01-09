<template>
    <header>
      <!--realizzerò la macrostruttura del navigation dell'header con un border solid 2px-->
      <div class="header-menu">
        <div class="navigation-avada-consultant">
          <div class="container-consultant">
            <NavigationComponent logo="/image/avada-marketing-logo.png" />
          </div>
            <div class="menu-list">
              <div class="container-menu">
                <ul class="menu-items">
                  <li v-for="menuItem in navigationData.menuLista" :key="menuItem">{{ menuItem }}</li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      
  
      <!--realizzerò la parte del container grande, all'interno con due container unlock e Richard-->
      <div class="container-bg-image">
        <img src="/image/marketing-intro.jpg" alt="marketing-intro" class="intro-image">
        <div class="container-unlock"></div>
        <div class="container-Richard"></div>
      </div>
    </header>
  </template>
  
  <script>
  import NavigationComponent from './NavigationComponent.vue';
  
  export default {
    components: {
      NavigationComponent,
    },
    data() {
      return {
        navigationData: {
          logo: 'avada-marketing-logo.png',
          menuLista: ["Home", "Service", "Why Us", "Case Studies", "About", "Blog"],
        },
      };
    },
  };
  </script>
  
  <style scoped>
  .container-menu {
    
    border: 2px solid magenta;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 20px;
  }
  
  .menu-items {
    list-style-type: none;
    display: flex;
    flex-grow: 1; 
  }
  
  .menu-items li {
    margin-right: 10px; 
  }
  
  .header-menu {
    display: flex;
    justify-content: center;
  }
  
  .navigation-avada-consultant {
    height: 100px;
    width: 80%;
    border: 2px solid red;
    display: flex;
    justify-content: space-between; 
  }
  
  .container-consultant {
     
    border: 2px solid cadetblue;
    display: flex;
    align-items: center;
  }
  
  .container-bg-image {
    height: 600px;
    border: 2px solid red;
    display: flex;
    position: relative;
  }

    .intro-container{
        width: 100%;
        height: 100%;
        overflow: hidden;
    }
  .intro-image{
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  
.container-unlock,
.container-Richard {
  width: 50%;
  height: 100%;
  border: 2px solid red;
  position: absolute; 
  top: 0;
}
  </style>
  
  