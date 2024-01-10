<template>
    <div class="footer-business">
        <div class="container-footer-business">
            <div class="container-grow">
                <FooterNav
  :title="navigationData.title"
  :menuListaUno="navigationData.menuListaUno"
  :menuListaDue="navigationData.menuListaDue"
  :menuListaTre="navigationData.menuListaTre"
  :navigationFooter="navigationData.navigationFooter"
/>

            </div>
        </div>
    </div>
</template>
<script>

import FooterNav from './FooterNav.vue';

export default {
    components: {
      FooterNav,
    },
    data() {
      return {
        navigationData: {
          title: 'Grow Your Online Business Strategically,and improve Customer Retention',
          menuListaUno: ["Services", "Marketing Plan", "Sales Development", "Digital Marketing", "Pricing", "Why Us"],
          menuListaDue: ["Resources", "Learning Center", "Video Tutorial", "Customers", "Blog",],
          menuListaTre: ["Company", "Who We Are", "Contact Us", "Careers",],
        },
      };
    },
  };
</script>
<style scoped>

.footer-business{
display: flex;
justify-content: end;
}

.container-footer-business{
height: 700px;
width: 90%;
display: flex;
justify-content: center;
align-items: center;
}

.container-grow{
height: 80%;
width: 100%;
border: 1px solid black;
}

</style>