<template>
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
</template>
<script>
export default {
    
}
</script>
<style scoped>
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
</style>