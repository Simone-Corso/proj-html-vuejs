<template>
    <div class="main-brand">
    <div class="container-brand">
        <div class="container-title-brand">
            <h1 class="title-brand">
                Some Brands We Work With
            </h1>
            <h3 class="title-brands">Quisque aliquet, libero consequat elementum convallis.</h3>
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
            <article class="consultant-expert">
            <img src="/image/marketing-expert-cta.png" alt="expert-cta" class="image-expert-cta">
        </article>
            <div class="container-title-consultant">
            <h2>
                Sandy Reiff
            </h2>
            <h3>
                Marketing Consultant Expert
            </h3>
        </div>
        <div class="container-title-phone">
            <h1>
                Drive Leads and Sales with Avada
            </h1>
        </div>
            <div class="container-btn-phone">
        <button class="btn-phone-consultant">
            <i class="fa-solid fa-phone"></i> (555) 802-1234
        </button>
        </div>


            



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

    .title-brand{
        font-size: 45px;
        margin-bottom: 0;
    }

    .title-brands{
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

    h1{
       font-size: 25px;
        }

        h3{
            font-size: 15px;
        }
    .consultant-expert{

    }

    .container-title-consultant{
       margin-top: 0;
       line-height: 1rem;

    }
    
    .container-title-phone{
        margin-left: 3rem;
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
        border-radius: 10px;
        display: flex;
        align-items: center;
    }

    .image-expert-cta{
        border-radius: 50%;
        height: 70px;
        width: auto;
        margin-left: 2.5rem;
        margin-top: .5rem;
    }

    .container-btn-phone{
    margin-left: auto;
    margin-right: 3rem;
  }

  .btn-phone-consultant{
    font-size: 15px;
    height: 50px;
    width: 200px;
    border-radius: 10px;
    border: none;
    background-color: #FFE7DA;
    color: #F86011;
  }
</style>