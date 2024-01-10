<template >
    <div class="main-team-avada">
    <div class="container-team">
        <div class="container-image-avada">
            <img src="/image/large-testimonial-600x583.jpg" alt="" class="image-team">

        </div>
        <div class="container-descrizione-avada">
            <h1>
                "The team at Avada Marketing Consulant is fabulos. They helped us unlock our potential online and offline.
                We have experienced year on year growth due to their progressive approach."
            </h1>
            <h3>
                Kate Schadler
            </h3>
            <h4>
                Marketing Consulant - Abstract
            </h4>
        </div>
    </div>
</div>
</template>
<script>
export default {
    
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
        width: 30%;
        border: 1px solid black;
    }

    .image-team{
        height: 100%;
        border-radius: 10px;
    }

    h1{
        font-size: 32px;
        margin-top: 4rem;
    }

    h3{
        
    }
</style>