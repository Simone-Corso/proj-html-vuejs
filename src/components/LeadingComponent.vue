<template>
   <div class="main-leading">
    <div class="container-leading-organisations">
        <div class="container-first-leading">
            <img src="/image/case-studies-1.jpg" alt="" class="image-leading">
            <h1>
                How Spaces attracted five million visitors by improving the content
            </h1>
            <h2>
                200%
            </h2>
            <h3>
                Higher revenue from digital
            </h3>
            
        </div>
        <div class="container-two-leading">
            <img src="/image/case-studies-4.jpg" alt="" class="image-leading">
            <h1>
                Creativity helped Hemisferio to increase their brand reach vertically
            </h1>

            <h2>
                10x
            </h2>
            <h3>
                Sales increase with same ad spend
            </h3>
            <button class="btn-leading">
                Read More Case Studios
    </button>
        </div>
<div class="container-three-leading">
    <img src="/image/case-studies-6.jpg" alt="" class="image-leading">
    <h1>
        How DigitalBox used AI-powered data insight to boost sales
    </h1>

    <h2>
        3-year
    </h2>
            <h3>
                Partnership with Avada Consultant
            </h3>
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

    h1{
        text-align: left;

    }

    h2{
        text-align: left;
        font-size: 40px;
    }

    h3{
        text-align: left;
    }

    .container-btn-leading {
    display: flex;
    flex-direction: row;
    }
    .container-leading-organisations{
        height: 1000px;
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

    .image-leading{
        width: 100%;
        height: 70%;
        object-fit: cover;
    }
    .container-two-leading{
        height: 80%;
        width: 25%;
        border: 1px solid black;
    }

    .btn-leading{
        height: 40px;
        width: 200px;
        border: none;
        border-radius: 10px;
        background-color: #F86011;
        color: white;
    }
    .container-three-leading{
        height: 80%;
        width: 25%;
        border: 1px solid black;
    }

    .container-percent{
        border: 1px solid red;
        text-align: left;
    }
</style>