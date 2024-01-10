<template>
    <div class="main-brand">
    <div class="container-brand">
        <div class="container-title-brand">
            <h1>
                Some Brands We Work With
            </h1>
            <h3>Quisque aliquet, libero consequat elementum convallis.</h3>
        </div>
        <div class="container-different-brand">

            <article>
                <img src="/image/abstract.png" alt="abstract" class="image-brand">
            </article>
            <article>
                <img src="/image/cglobal.png" alt="cglobal" class="image-brand">
            </article>
            <article>
                <img src="/image/next.png" alt="next" class="image-brand">
            </article>
            <article>
                <img src="/image/hemisferio.png" alt="hemisferio" class="image-brand">
            </article>
            <article>
                <img src="/image/spaces.png" alt="spaces" class="image-brand">
            </article>
            <article>
                <img src="/image/digitalbox.png" alt="digitalbox" class="image-brand">
            </article>

        </div>
    </div>
    </div>
    <div class="main-marketing">
    <div class="container-marketing-consultant">
        <div class="container-consultant">
            <img src="/image/marketing-expert-cta.png" alt="expert-cta" class="image-expert-cta">

        </div>
</div>
</div>
</template>
<script>
export default {
    
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
        height: 100px;
        width: 100%;
        border: 2px solid black;
        display: flex;
        justify-content: center;
        flex-direction: column;
        align-items: center;

    }

    h1{
        font-size: 45px;
        margin-bottom: 0;
    }

    h3{
        font-size: 20px;
        margin-top: .5rem;
        
    }
    .container-different-brand{
        height: 200px;
        width: 100%;
        border: 2px solid black;
        display: flex;
        justify-content: center;
        align-items: center;

    }

    .image-brand{
        height: 45px;
    }

    article{
        margin-right: 1.5rem;
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

    .image-expert-cta{
        border-radius: 50%;
        height: 80px;
        width: auto;
    }
</style>