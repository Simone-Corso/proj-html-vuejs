<template >
    <div class="main-team-avada">
    <div class="container-team">
        <div class="container-image-avada">
            <img src="/image/large-testimonial-600x583.jpg" alt="" class="image-team">

        </div>
        <div class="container-descrizione-avada">

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
        width: 40%;
        border: 1px solid black;
    }
</style>