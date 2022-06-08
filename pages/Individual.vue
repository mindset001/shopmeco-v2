<template>
    <div class="cover">
        <div class="left">
        <div class="logo">
        <a href="/"><img src="../assets/images/Mask group.png" alt=""></a>
        <img src="../assets/images/Group 3721.png" alt="" class="img">
      </div>
        </div>
        <div class="right first">
        <navbar class="mobile"/>
        <div>
            <a href="/started" style="display:flex; align-items: center;"><img src="../assets/images/icon.png" alt="" style="width:20px; height:20px; margin-right: 10px;"> back</a>
        </div>
        <div class="step">
        <h4>STEP 01/03</h4>
        <h6>Personal Info.</h6>
        </div>
        <div class="log">
            <h1>Register Individual Account</h1>
        <p>Your details are required to set up your account and get you going.</p>
        </div>
        <div class="one">
             <form action="">
            <div style="margin-bottom: 30px">
                <label for="name" >Your fullname<span style="color:red;">*</span></label> <br>
            <input type="text" placeholder="Tolulope Ololade" required>
            </div>
            <div style="margin-bottom: 30px">
                <label for="name" >Email address*</label> <br>
            <input type="email" placeholder="Enter email address" required>
            </div>
            <div style="margin-bottom: 30px">
                    <label for="name">Create password*</label> <br>
            <input type="password" required>
            </div>
            <div class="formy">
                    <div style="display:flex; align-items:center; justify-content: space-between; width:230px; color: #7C7C7C;">
                        <input type="checkbox" name="" id=""  style="border:2px dotted #00f;display:block;background:red; width:20px" >I agree to terms & conditions
                    </div>
                    
            </div>

            <button class="btn1">Register Account</button>
            <div class="or">
                <div class="line"></div>
                <div class="text">OR</div>
                <div class="line"></div>
            </div>

            <button class="btn2"><img src="../assets/images/Group 3707.png" alt=""></button>
      </form>


        </div>
        
        </div>


        <!-- Residency info  -->

        <div class="right second">
        <navbar class="mobile"/>
        <div>
            <a href="/started" style="display:flex; align-items: center;"><img src="../assets/images/icon.png" alt="" style="width:20px; height:20px; margin-right: 10px;"> back</a>
        </div>
        <div class="step">
        <h4>STEP 02/03</h4>
        <h6>Residency Info.</h6>
        </div>
        <div class="log">
            <h1>Complete Your Profile</h1>
        <p>Your details are required to set up your account and get you going.</p>
        </div>
        <div class="one">
             <form action="">
            <div style="margin-bottom: 30px">
                <label for="name" >Your phone number</label> <br>
            <input type="number" placeholder="Enter your phone number" required>
            </div>
            <div style="margin-bottom: 30px">
                <label for="name" >State of residence</label> <br>
            <select name="Car Model" id="" placeholder="select">
                <option value="" style="color: #B5B5B5;">-- Select --</option>
                <option value="">1998</option>
                <option value="">1998</option>
                <option value="">1998</option>
                <option value="">1998</option>
                <option value="">1998</option>
                <option value="">1998</option>
                <option value="">1998</option>
                <option value="">1998</option>
            </select>
            </div>
            <div style="margin-bottom: 30px">
                    <label for="name">Your address</label> <br>
            <textarea name="" id="" cols="30" rows="10" placeholder="Enter your address"></textarea>
            </div>
            
              <div class="here">
              <p>Need to complete profile later? <a href="">Click Here</a></p>
              </div>
            <button class="btn1">Save</button>
            <div class="bot">
              <img src="../assets/images/Group 3720.png" alt="">
            </div>
      </form>


        </div>
        
        </div>


        <!-- service info  -->

        <div class="right third">
        <navbar class="mobile"/>
        <div>
            <a href="/started" style="display:flex; align-items: center;"><img src="../assets/images/icon.png" alt="" style="width:20px; height:20px; margin-right: 10px;"> back</a>
        </div>
        <div class="step">
        <h4>STEP 03/03</h4>
        <h6>Service Info.</h6>
        </div>
        <div class="log">
            <h1>Almost Done!</h1>
        <p>Your details are required to set up your account and get you going.</p>
        </div>
        <div class="one">
             <form action="">
            <div style="margin-bottom: 30px">
                <label for="name" >Car Name</label> <br>
            <input type="text" placeholder="Mercedez Benz" required>
            </div>
            <div style="margin-bottom: 30px">
                <label for="name" >Car Model</label> <br>
            <select name="Car Model" id="" placeholder="select">
                <option value="" style="color: #B5B5B5;">-- Select --</option>
                <option value="">1998</option>
                <option value="">1998</option>
                <option value="">1998</option>
                <option value="">1998</option>
                <option value="">1998</option>
                <option value="">1998</option>
                <option value="">1998</option>
                <option value="">1998</option>
            </select>
            </div>
            <div style="margin-bottom: 30px">
                    <label for="name">Required Services</label> <br>
            <select name="Car Model" id="" placeholder="select">
                <option value="" style="color: #B5B5B5;">-- Select --</option>
                <option value="">1998</option>
                <option value="">1998</option>
                <option value="">1998</option>
                <option value="">1998</option>
                <option value="">1998</option>
                <option value="">1998</option>
                <option value="">1998</option>
                <option value="">1998</option>
            </select>
            <p style="color: #5007E0;font-size: 14px;font-family: 'Sofia Pro';">Bodywork, airconditioning, automechanic</p>
            </div>
            
              <div class="here">
              <p>Need to complete profile later? <a href="">Click Here</a></p>
              </div>
            <button class="btn1">Save</button>
            <div class="bot">
              <img src="../assets/images/Group 3720.png" alt="">
            </div>
      </form>


        </div>
        
        </div>

        <!-- end of service info  -->
    </div>
</template>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Fruktur&family=Inter:wght@100;200;300;400;600;700;800&family=Licorice&display=swap');
@import url('http://fonts.cdnfonts.com/css/sofia-pro');

    .cover{
            display: flex;
            width: 100vw;
            
    }
    .mobile{
      display: none;
    }
    .left{
        background: url('../assets/images/bg2.png');
        width: 724px;
        height: 100vh;
        padding: 30px 40px;
    }
    .right{
        padding-left: 100px;
        padding-top: 50px;
    }
    

    h1{
            
            height: 48px;
            font-family: 'Inter';
            font-style: normal;
            font-weight: 600;
            font-size: 40px;
            line-height: 48px;
            color: #1F1F1F;
            margin-bottom: 10px;
    }
    a{
        color:  #5007E0;
    }
    .step{
      
        font-family: 'Inter';
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 28px;
        color: #7C7C7C;
        padding-left: 760px;
        text-align: right;
        align-items: right;
    }
    .step h6{
        width: 206px;
        height: 19px;
        font-family: 'Inter';
        font-style: normal;
        font-weight: 600;
        font-size: 16px;
        line-height: 19px;
        color: #7C7C7C;
    }
    .step h4{
        height: 17px;
        font-family: 'Inter';
        font-style: normal;
        font-weight: 500;
        font-size: 14px;
        line-height: 17px;
        color: #5007E0;
        padding-left: 20px;
    }
    .img{
        padding: 245px 76px 0px 76px;
    }
    .log{
        margin-top: 22px;
        padding-left: 30px;
    }
    .log p{
        width: 411px;
        font-family: 'Sofia Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 28px;
        color: #7C7C7C;

        padding-bottom: 55px;
    }
      input, select, textarea{
    border: 1px solid #7C7C7C;
    box-sizing: border-box;
    border-radius: 10px;
    width: 490px;
    height: 55px;
    padding: 10px;
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 500;
    font-size: 18px;
    line-height: 18px;
    color: #5007E0;
    
    
  }
  input:hover{
    border: 1px solid #5007E0;
  }
  .btn1{
    height: 60px;
    width: 490px;
    background: #5007E0;
    border-radius: 10px;
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 500;
    font-size: 24px;
    line-height: 24px;
    color: #FFFFFF;
  }
  form{
    margin-left: 30px;
  }
  .btn2{
    width: 490px;
    height: 60px;
    background: #FFFFFF;
    border: 1px solid #B5B5B5;
    box-sizing: border-box;
    box-shadow: 0px 6px 50px rgba(74, 25, 172, 0.05);
    border-radius: 6px;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  label{
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 31px;
    color: #7C7C7C;
    margin-bottom: 10px;

  }
  .formy{
    display: flex;
    align-items: center;
    width: 490px;
    justify-content: space-between;
    margin-top: -20px;

  }
  .or{
    display: flex;
    align-content: center;
    height: 40px;
    justify-content: space-between;
    width: 490px;
    margin-top: 30px;
  }
    .line{
        width: 192px;
        height: 0px;
        border: 1px solid #7C7C7c;
        margin-top: 10px;
    }

    .first{
      display: none;
    }
    .second{
      display: block;
    }
    .third{
      display: none;
    }
    .bot{
      align-items: center;
      display: flex;
      width:490px ;
      justify-content: center;
      height: 80px;
    }
    .here{
      display: flex;
      width:490px ;
      justify-content: right;
      margin-top: 4rem;
    }

    @media only screen and (max-width: 600px) {
      .cover{
        overflow: hidden;
      }
      .mobile{
        display: block;
        margin-bottom: 50px;
      }
      .left{
        display: none
      }
      .right{
        padding-left: 0px;
        padding-top: 10px;
    }
    input{
      width: 360px;
    }
    select{
      width: 360px;
    }
    .btn1{
     width: 360px;
    }
   .log p{
      width: 370px;
      
    }
    .line{
      width: 150px;
    }
    .btn2{
      width: 360px;
    }
    .or{
      width: 360px;
    }
    .log h1{
      width: 360px;
      margin-bottom: 60px;
    }
    .step{
      padding-left: 183px;
      width: 360px;
      text-align: right;
    }
    textarea{
      width: 360px;
    }
    }
</style>