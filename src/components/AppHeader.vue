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
              <i class="fa-solid fa-phone"></i> (555) 802-1234
            </p>
          </div>
          <div class="container-name-email-phone">
         <div class="container-name"> 
          <p>Your Name*</p>
        </div>
        <div class="container-email">
          Your Email*
        </div>
        <div class="container-number">
          Your Phone Number*
        </div>
        <div class="container-get-callback">
          <button class="btn-get-callback">
            Get a Callback
          </button>
          <p class="submitting">By submitting my data i agree to be contacted</p>
        </div>
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
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 20px;
  }
  
  .menu-items {
    list-style-type: none;
    display: flex;
    flex-grow: 1;
    margin-top: 3rem;
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
    display: flex;
    justify-content: space-between; 
  }
  
  .container-consultant {
    display: flex;
    align-items: center;
  }
  
  .container-bg-image {
    height: 600px;
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
    width: 420px;
    height: 590px;
    position: absolute;
    top: 4.2rem;
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

  .number-phone{
    color: #F86011;
    margin-top: 0;
  }


    .container-name-email-phone{
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;

    }
  .container-name,
  .container-email,
  .container-number{
    height: 50px;
    width: 80%;
    border: 2px solid#F4F4F6;
    margin-top: 1rem;
    border-radius: .5rem;
  }

  .btn-get-callback{
    height: 50px;
    width: 375px;
    border: 2px solid#F4F4F6;
    margin-top: 1rem;
    border-radius: .5rem;
    font-size: 18px;
    background-color: #F86011;
    color: white;
  }

  .submitting{
    text-align: center;
    font-size: 13px;
    color: #777777;
  }
  </style>
  
  