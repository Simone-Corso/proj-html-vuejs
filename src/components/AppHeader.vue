<template>
    <header>
        <!--realizzerò la macrostruttura del navigation dell'header con un border solid 2px-->
        <div class="header-menu">
        <div class="navigation-avada-consultant">
            <NavigationComponent logo="/image/avada-marketing-logo.png"/>
        </div>
    </div>

        <!--realizzerò la parte del container grande, all'interno con due container unlock e Richard-->
            <div class="container-bg-image">
                <div class="container-unlock ">

                </div>
                <div class="container-Richard">

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

    .header-menu{
        display: flex;
        justify-content: center;
    }
    .navigation-avada-consultant{
        height: 100px;
        width: 80%;
        border: 2px solid red;
    }

    .container-bg-image{
        height: 800px;
        border: 2px solid red;
        display: flex;
    }

    .container-unlock{
        width: 50%;
        height: 100%;
        border: 2px solid red;
    }

    .container-Richard{
        width: 50%;
        height: 100%;
        border: 2px solid red;
    }
</style>