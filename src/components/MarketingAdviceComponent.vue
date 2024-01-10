<template>
    <div class="main-marketing">
    <div class="container-marketing">
        <div class="container-title-btn">
            <h1>
                Marketing Resources: <br>
                Insider Advice on How to <br>Increase Online Sales <br>
            </h1>
        </div>
            <div class="container-btn">
                <button class="btn-explore">
                    Explore All Resources
                </button>
            </div>
    </div>
        
        <div class="container-three-image">
            <div class="container-first-marketing">
                <img src="/image/blog-posts-6.jpg" alt="" class="image-posts-6">
                <h2>
                    Marketing Tips And Tricks For Your WebSite
                </h2>
            </div>
            <div class="container-two-marketing">
                <img src="/image/blog-posts-5.jpg" alt="" class="image-posts-5">
                <h2>
                    How To Write Stunning Blog Posts Titles
                </h2>
            </div>
            <div class="container-three-marketing">
                <img src="/image/blog-posts-4.jpg" alt="" class="image-posts-4">
                <h2>
                    Techniques to Reduce Facebook Ads Spend
                </h2>
            </div>
        </div>
    
</div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .main-marketing{
        display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    }
        

    .container-marketing{
        height: 600px;
        width: 80%;
        display: flex;
        align-items: center;

    }
    .container-title-btn{
        height: 300px;
    width: 40%;
    margin-left: 5rem;
}
    

    .container-three-image{
        height: 300px;
    width: 80%;
    display: flex;
    justify-content: center;

    }

    .container-first-marketing{
        height: 100%;
        width: 30%;
    }
    .container-two-marketing{
        height: 100%;
        width: 30%;
        
    }
    .container-three-marketing{
        height: 100%;
        width: 30%;
        
    }

    .btn-explore{
        margin-left: auto; 
        width: 180px;
        height: 40px;
        background: #F86011;
        color: white;
        border: none;
        border-radius: 10px;
        font-size: 15px;
    }

    .container-btn{
        margin-left: auto;
        margin-right: 5rem;
    }

    h1{
        font-size: 50px;
    }

    .image-posts-6{
        height: 100%;
        border-radius: 10px;
    }

    .image-posts-5{
        height: 100%;
        border-radius: 10px;
    }
    .image-posts-4{
        height: 100%;
        border-radius: 10px;
    }



</style>