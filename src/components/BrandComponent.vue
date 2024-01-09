<template>
    <div class="main-brand">
    <div class="container-brand">
        <div class="container-title-brand">

        </div>
        <div class="container-different-brand">

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
        height: 150px;
        width: 100%;
        border: 2px solid black;

    }
    .container-different-brand{
        height: 200px;
        width: 100%;
        border: 2px solid black;

    }
</style>