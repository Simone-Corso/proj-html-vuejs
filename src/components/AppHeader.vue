<template>
    <header>
        <!--realizzerò la macrostruttura del navigation dell'header con un border solid 2px-->
        <div class="navigation-avada-consultant">
        </div>
            <div class="container-bg-image ">
                <div class="container-unlock ">

                </div>
                <div class="container-Richard ">

                </div>

            </div>
    </header>
</template>
<script>
export default {
    components: {
    }
    
}
</script>
<style scoped>
    .navigation-avada-consultant{
        height: 100px;
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