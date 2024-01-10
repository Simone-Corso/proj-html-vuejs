<template>
    <div class="main-work">
        <div class="container-big">
            <div class="container-client">
               <h1>
                We Boost Our Client's Bottom Line by Optimizing Their Growth Potential.
               </h1>
               <h3>
                Quisque aliquet, libero consequat alementum convallis, erat risus imperdiet pellentesque sem neque eget.
               </h3>
               <button class="btn-work">
                Why Work With Us

               </button>
            </div>
            <div class="container-image">
                <img src="/image/we-boost-our-clients.jpg" alt="boost" class="image-we-boost">
            </div>
        </div>
        <div class="container-big-two">
            <div class="container-client">
                <h1 class="title-relationships">
                    We Build Relationships
                </h1>
                <h3 class="descrizione-relationships">
                    Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maxiums nec ut leo.
                    integer consectetur.
                </h3>
                <h1 class="title-processes">
                    Proprietary Processes
                </h1>
                <h3 class="descrizione-processes">
                    Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maxiums nec ut leo.
                    integer consectetur.
                 </h3>
            </div>
            <div class="container-loghi">
                <article class="container-accountability">
                    <img src="/image/accountability.png" alt="">
                    <h1 class="title-loghi">
                        Accountability
                    </h1>

                    <h3 class="descrizione-loghi">
                        Curabitur ac leo nunc vestibulum
                    </h3>

                </article>
                <article class="container-trasparency">
                    <img src="/image/trasparency.png" alt="">
                    <h1 class="title-loghi">
                        Trasparency
                    </h1>
                    <h3 class="descrizione-loghi">
                        Curabitur ac leo nunc vestibulum
                    </h3>

                </article>
                    <article class="container-investiment">
                        <img src="/image/investiment.png" alt="">
                        <h1 class="title-loghi">
                            Investiment
                        </h1>
                        <h3 class="descrizione-loghi">
                            Curabitur ac leo nunc vestibulum
                        </h3>

                    </article>
            </div>
        </div>
        <article class="title-awards-first">
            <h1 class="title-awards">
                Awards

            </h1>
        </article>
        <div class="container-awards">
            <div class="logo-awards">
                <img src="/image/award-a.png" alt="" class="image-awards-a">
        
            </div>
            <h3 class="descrizione-awards">

</h3>
            <div class="logo-awards">
                <img src="/image/award-b.png" alt="" class="image-awards-b">
                <h3 class="descrizione-awards">

</h3>
</div>
            <article class="logo-awards">
                <img src="/image/award-c.png" alt="" class="image-awards-c">
                <h3 class="descrizione-awards">

</h3>
            </article>
            <article class="logo-awards">
                <img src="/image/award-d.png" alt="" class="image-awards-d">
                <h3 class="descrizione-awards">

</h3>
            </article>
            
        </div>
    </div>
</template>

<style scoped>
    .main-work {
        display: flex;
        justify-content: center;
        flex-direction: column; 
        align-items: center;
        margin-top: 5rem;
    }

    .container-big {
        display: flex;
    justify-content: space-between;
    height: 500px;
    width: 80%;
    margin-bottom: 10px;
    }

    .container-big-two {
        display: flex;
        justify-content: space-between;
        height: 600px;
        width: 80%;
        margin-bottom: 10px; 
    }

    .container-client {
        height: 100%;
    width: 35%;
    margin-left: auto;
    margin-top: 3.5rem;
    }

    .container-image {
        height: 100%; 
        width: 50%;
        overflow: hidden;
    }

    .container-loghi{
        height: 100%; 
        width: 50%;
        overflow: hidden;
        margin-top: 3rem;
    }

    .title-loghi{
        font-size: 25px;
    }

    .image-we-boost {
        width: 80%;
        height: 100%;
        object-fit: cover; 
        border-radius: 10px;
    }

    .title-relationships{
        font-size: 30px;
    }

    .descrizione-relationships{

    }

    .title-processes{
        font-size: 30px;
    }

    .descrizione-processes{
        
    }

    h1{
        font-size: 50px;
    }

    .container-awards {
        height: 300px;
        width: 80%;
        margin-top: 3rem;
        display: flex;
        justify-content: center;

    }

    .image-awards-a{
        height: 140px;
    }
    .image-awards-b{
        height: 140px;
    }

    .image-awards-c{
        height: 140px;
    }
    .image-awards-d{
        height: 140px;
    }
    .btn-work{
    width: 180px;
    height: 40px;
    background: #F86011;
    color: white;
    border: none;
    border-radius: 10px;
    font-size: 15px;
    }
</style>
