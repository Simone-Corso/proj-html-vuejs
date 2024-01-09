<template>
    <div>
        <CategoryComponent/>
    </div>
    <div class="main-brand">
    <div class="container-brand">
        <div class="container-title-brand">

        </div>
        <div class="container-different-brand">

        </div>
    </div>
    </div>
    <div class="main-marketing">
    <div class="container-marketing-consultant">
        <div class="container-consultant">

        </div>

</div>
</div>
<div class="main-leading">
    <div class="container-leading-organisations">
        <div class="container-first-leading">

        </div>
        <div class="container-two-leading">

        </div>
<div class="container-three-leading">

</div>
<div class="container-btn-leading">
        <button class="btn-leading">
        orange
    </button>
    </div>
</div>
    
</div>

<div class="main-work">
    <div class="container-big">
    <div class="container-client">

    </div>
    <div class="container-image">

    </div>
    <div class="container-awards">

    </div>
</div>
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

export default {
    components: { CategoryComponent }
}
</script>
<style scoped>
    .main-brand{
        display: flex;
        justify-content: center;
        align-content: center;
    }

    .container-brand{
        height: 350px;
        width: 80%;
        border: 2px solid black;
        display: flex;
        align-content: center;
        flex-direction: column;
        
    }
    .container-title-brand{
        height: 150px;
        width: 100%;
        border: 2px solid black;

    }
    .container-different-brand{
        height: 200px;
        width: 100%;
        border: 2px solid black;

    }

    .main-marketing{
        display: flex;
        justify-content: center;
    }
    .container-marketing-consultant{
        height: 100px;
        width: 80%;
        border: 2px solid black;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .container-consultant{
        height: 80px;
        width: 80%;
        border: 2px solid magenta;
    }

    .main-leading{
        display: flex;
        justify-content: center;
        text-align: center;
    }

    .container-btn-leading {
    display: flex;
    flex-direction: row;
    }
    .container-leading-organisations{
        height: 800px;
        width: 80%;
        border: 2px solid brown;
        display: flex;
        justify-content: space-around;
        align-items: center;

    }

    .container-first-leading{
        height: 80%;
        width: 25%;
        border: 1px solid black;
    }
    .container-two-leading{
        height: 80%;
        width: 25%;
        border: 1px solid black;
    }
    .container-three-leading{
        height: 80%;
        width: 25%;
        border: 1px solid black;
    }

    .main-work{
        display: flex;
        justify-content: center;

    }

    .container-big{
        height: 900px;
        width: 80%;
        border: 2px solid black;
        display: flex;
        justify-content: center;

    }

    .container-client{
        height: 450px;
        width: 50%;
        border: 1px solid red;
    }
    .container-image{
        height: 450px;
        width: 50%;
        border: 1px solid red;
    }

    .container-awards{
        height: 450px;
        width: 100%;
        border: 1px solid green;
    }

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