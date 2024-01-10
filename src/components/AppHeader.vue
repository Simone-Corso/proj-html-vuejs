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
        <div class="container-unlock">
          <h1>
            Unlock Your Online Growth Potential
          </h1>
          <h3>
            Online marketing to secure customer retention,leads,and males.
            We focus on the bigger picture.
          </h3>
          <button class="btn-unlock">
            Our Services <i class="fa-solid fa-arrow-right"></i>
          </button>
        </div>
        <div class="container-Richard">
          <div class="container-profile-richard">
            <img src="/image/marketing-consultant-expert.jpg" alt="marketing-consultant" class="image-richard">
            <h3 class="title-richard">
              Richard Madsen
            </h3>
            <h4>
              Marketing Consultant Expert
            </h4>
            <p class="number-phone">
              (555) 802-1234
            </p>
          </div>
        </div>
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

  h1{
    font-size: 65px;
    line-height: 60px;
    color: white;
    margin-top: 1rem;
  }

  h3{
    font-size: 25px;
    color: white;
    text-align: justify;
  
  }

  h4{
    font-size: 20px;
    margin-top: 0;
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
  
  .container-unlock {
    width: 650px;
    height: 400px;
    border: 2px solid red;
    position: absolute; 
    top: 50%; 
    left: 10%;
    transform: translateY(-50%);
  }

  .btn-unlock{
    font-size: 20px;
    width: 180px;
    height: 50px;
    border-radius: .5rem;
    border: none;
  }

  .container-Richard {
    width: 460px;
    height: 550px;
    border: 2px solid red;
    position: absolute;
    top: 6.2rem;
    right: 470px;
    background-color: white;
    border-radius: 1rem;
  }


  .container-profile-richard{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background-color: white;
    border-radius: 1rem;
  }
  .image-richard{
    border-radius: 50%;
    margin-top: 1rem;
    height: 80px;
    width: 80px;
  }

  .title-richard{
    color: black;
  }
  </style>
  
  