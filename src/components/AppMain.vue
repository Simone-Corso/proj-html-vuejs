<template>
    <div>
        <CategoryComponent/>
        <BrandComponent/>
        <LeadingComponent/>
        <GrowthComponent />
    </div>
<div class="main-team-avada">
    <div class="container-team">
        <div class="container-image-avada">

        </div>
        <div class="container-descrizione-avada">

        </div>
    </div>
</div>

<div class="main-marketing">
    <div class="container-marketing">
        <div class="container-title-btn">

        </div>
        <div class="container-three-image">
            <div class="container-first-marketing">

            </div>
            <div class="container-two-marketing">
                
            </div>
            <div class="container-three-marketing">
                
                
            </div>
        </div>
    </div>
</div>

<div class="main-make-happen">
    <div class="container-make-happen">
        <div class="container-left-make">

        </div>
        <div class="container-right-richard">

        </div>
    </div>
</div>
</template>
<script>
import CategoryComponent from './CategoryComponent.vue';
import BrandComponent from './BrandComponent.vue';
import LeadingComponent from './LeadingComponent.vue';
import GrowthComponent from './GrowthComponent.vue';
export default {
    components: {CategoryComponent, 
                BrandComponent,
                LeadingComponent,
                GrowthComponent,
                }

}
</script>
<style scoped>

        .main-team-avada{
            display: flex;
            justify-content: center;
        }
        .container-team{
        height: 500px;
        width: 80%;
        border: 2px solid red;
        display: flex;
        justify-content: center;

    }

    .container-image-avada{
        height: 100%;
        width: 40%;
        border: 1px solid black;
    }

    .container-descrizione-avada{
        height: 100%;
        width: 40%;
        border: 1px solid black;
    }

    .container-marketing{
        height: 600px;
        width: 80%;
        border: 2px solid black;

    }
    .container-title-btn{
        height: 300px;
        width: 100%;
        border: 1px solid red;
    }

    .container-three-image{
        height: 300px;
        width: 100%;
        border: 1px solid red;
        display: flex;
        justify-content: center;

    }

    .container-first-marketing{
        height: 100%;
        width: 30%;
        border: 1px solid black;
    }
    .container-two-marketing{
        height: 100%;
        width: 30%;
        border: 1px solid black;
        
    }
    .container-three-marketing{
        height: 100%;
        width: 30%;
        border: 1px solid black;
        
    }

        .main-make-happen{
            display: flex;
            justify-content: center;
        }
    .container-make-happen{
        height: 600px;
        width: 80%;
        border: 2px solid black;
        display: flex;
        justify-content: center;
        
    }

    .container-left-make{
        height: 100%;
        width: 60%;
        border: 1px solid red;
    }
    .container-right-richard{
        height: 100%;
        width: 30%;
        border: 1px solid red;
    }
</style>