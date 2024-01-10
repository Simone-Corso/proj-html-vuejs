<template >
    <div class="main-make-happen">
    <div class="container-make-happen">
        <div class="container-left-make">

            <h1>
                Let's Make Things Happen
            </h1>

            <h2>
                Curabitur ac leo nunc. Vestibulum et mauris le ante finibus maximus nec ut leo.
                Integer consectetur.
            </h2>
            <h3>
                "The team ai Avada Marketing Consultant is fabulous. They helped us unlock our potential online and offline.
                We have experienced year on year growth due to their progressive approach"
            </h3>

            <h4>
                George Anderson
            </h4>
            <h4>
                Digitalbox CEO
            </h4>

        </div>
            <div class="container-right-richard">
          <div class="container-profile-richard">
            <img src="/image/marketing-consultant-expert.jpg" alt="marketing-consultant" class="image-richard">
            <h3 class="title-richard">
              Richard Madsen
            </h3>
            <h4>
              Marketing Consultant Expert
            </h4>
            <p class="number-phone">
              <i class="fa-solid fa-phone"></i> (555) 802-1234
            </p>
          </div>
          <div class="container-name-email-phone">
         <div class="container-name">
          <p>Your Name*</p>
        </div>
        <div class="container-email">
          Your Email*
        </div>
        <div class="container-number">
          Your Phone Number*
        </div>
        <div class="container-get-callback">
          <button class="btn-get-callback">
            Get a Callback
          </button>
          <p class="submitting">By submitting my data i agree to be contacted</p>
        </div>
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
     .main-make-happen{
            display: flex;
            justify-content: center;
            background-color: black;
            margin-top: 6rem;
        }
    .container-make-happen{
        height: 800px;
        width: 80%;
        border: 2px solid black;
        display: flex;
        justify-content: center;
        margin-top: 6rem;
        
    }

    .container-left-make{
        height: 100%;
        width: 60%;
        
    }
    .container-right-richard{
        height: 80%;
    width: 30%;
    background: white;
    border-radius: 10px;
    margin-left: 4rem;
    }

    h1{
        color: white;
        font-size: 80px;

    }

    h2{
        color: white;
        font-size: 30px;
    }

    h3{
        color: white;
        font-size: 25px;
    }

    h4{
        color: white;
        font-size: 20px;
    }

    .container-Richard {
    width: 420px;
    height: 590px;
    position: absolute;
    top: 4.2rem;
    right: 470px;
    background-color: white;
    border-radius: 1rem;
  }


  .container-profile-richard{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background-color: white;
    border-radius: 1rem;
  }
  .image-richard{
    border-radius: 50%;
    margin-top: 1rem;
    height: 80px;
    width: 80px;
  }

  .title-richard{
    color: black;
  }

  .number-phone{
    color: #F86011;
    margin-top: 0;
  }


    .container-name-email-phone{
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;

    }
  .container-name,
  .container-email,
  .container-number{
    height: 50px;
    width: 80%;
    border: 2px solid#F4F4F6;
    margin-top: 1rem;
    border-radius: .5rem;
  }

  .btn-get-callback{
    height: 50px;
    width: 375px;
    border: 2px solid#F4F4F6;
    margin-top: 1rem;
    border-radius: .5rem;
    font-size: 18px;
    background-color: #F86011;
    color: white;
  }

  .submitting{
    text-align: center;
    font-size: 13px;
    color: #777777;
  }
</style>