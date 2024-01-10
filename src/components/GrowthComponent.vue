<template>
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
</template>
<script>
export default {
    
}
</script>
<style>
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
</style>