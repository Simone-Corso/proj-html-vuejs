<template>
    <div class="main-category">
        <div class="container-business-growth">
            <div class="container-image-business">
                <img src="/image/image-business.png" alt="Business Image">

            </div>
            <div class="container-descrzione-brand">
                <h1>
                    Increase Brand Awareness
                </h1>

                <P>
                    lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor placerat luctus. Nullam sit amet ante sed orci convallis 
                    gravida et at massa
                </P>
            </div>
        </div>
        <div class="container-investors-people">
            <div class="container-descrizione-house">

            </div>
            <div class="container-image-house">
                <img src="/image/image-investor.png" alt="Business Image">
            </div>
        </div>
        <div class="container-social-media-analysis">
            <div class="container-image-social">
                <img src="/image/image-house.png" alt="Business Image">

            </div>
            <div class="container-descrizione-social-proof">

            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .main-category{
        display: flex;
        justify-content: center;
        align-content: center;
        flex-direction: column;
        flex-wrap: wrap;
        margin-top: 5rem;
    }
    .container-business-growth{
        height: 750px;
        width: 80%;
        border: 2px solid blue;
        display: flex;

    }
    .container-image-business{
        height: 100%;
        width: 50%;
        border: 2px solid blue;

    }
    .container-descrzione-brand{
        height: 100%;
        width: 50%;
        border: 2px solid blue;

    }

    .container-investors-people{
        height: 750px;
        border: 2px solid yellow;
        display: flex;

    }
    .container-descrizione-house{
        height: 100%;
        width: 50%;
        border: 2px solid yellow;

    }
    .container-image-house{
        height: 100%;
        width: 50%;
        border: 2px solid yellow;

    }

    .container-social-media-analysis{
        height: 750px;
        border: 2px solid green;
        display: flex;

    }
    .container-image-social{
        height: 100%;
        width: 50%;
        border: 2px solid green;

    }
    .container-descrizione-social-proof{
        height: 100%;
        width: 50%;
        border: 2px solid green;

    }
</style>