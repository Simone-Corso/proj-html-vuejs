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

                <button class="btn-get-consultantion">
                    Get a Consultantion
                </button>
            </div>
        </div>
        <div class="container-investors-people">
            <div class="container-descrizione-house">
                <h1>
                    In-House Sales Training
                </h1>

                <P>
                    lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor placerat luctus. Nullam sit amet ante sed orci convallis 
                    gravida et at massa
                </P>

                <button class="btn-get-consultantion">
                    Get a Consultantion
                </button>

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
                <h1>
                    Harness Your Social Proof
                </h1>

                <P>
                    lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor placerat luctus. Nullam sit amet ante sed orci convallis 
                    gravida et at massa
                </P>

                <button class="btn-get-consultantion">
                    Get a Consultantion
                </button>

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
        display: flex;

    }
    .container-image-business{
        height: 100%;
        width: 50%;

    }
    .container-descrzione-brand{
        height: 567px;
        width: 547px;
        display: flex;
        justify-content: center;
        flex-direction: column;

    }

    .container-investors-people{
        height: 750px;
        display: flex;
        justify-content: flex-end;

    }
    .container-descrizione-house{
        height: 567px;
        width: 547px;
        display: flex;
        justify-content: center;
        align-items: flex-start;
        flex-direction: column;

    }
    .container-image-house{
        height: 100%;
        width: 50%;

    }

    .container-social-media-analysis{
        height: 750px;
        display: flex;

    }
    .container-image-social{
        height: 100%;
        width: 50%;

    }
    .container-descrizione-social-proof{
        height: 567px;
        width: 547px;
        display: flex;
        justify-content: center;
        flex-direction: column;
}

.btn-get-consultantion{

    width: 180px;
    height: 40px;
    background: #F86011;
    color: white;
    border: none;
    border-radius: 10px;
    font-size: 15px;
}

h1{
    font-size: 50px;
}

p{
    font-size: 20px;
}

</style>