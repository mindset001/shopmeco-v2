<template>
    <div class="cover">
        <div class="left">
        <div class="logo">
        <a href="/"><img src="../assets/images/Mask group.png" alt=""></a>
        <img src="../assets/images/Group 3721.png" alt="" class="img">
      </div>
        </div>
        <div class="right">
        <h4>Don't have an account?<a href="/started"> Register</a></h4>
        <div class="log">
            <h1>Login</h1>
        <p>Login to your account and explore our services and proficient technicians.</p>
        </div>
        <div class="one">
             <form action="">
            <div style="margin-bottom: 30px">
                <label for="name" >Email address</label> <br>
            <input type="email" placeholder="TolulopeOlolade@gmail.com" required>
            </div>
            <div style="margin-bottom: 30px">
                    <label for="name">Password</label> <br>
            <input type="password" required>
            </div>
            <div class="formy">
                    <div style="display:flex; align-items:center; justify-content: space-between; width:130px; color: #7C7C7C;">
                        <input type="checkbox" name="" id=""  style="border:2px dotted #00f;display:block;background:red; width:20px" >Remember me
                    </div>
                    <a href="/">Forget Password?</a>
            </div>

            <button class="btn1">Login</button>
            <div class="or">
                <div class="line"></div>
                <div class="text">OR</div>
                <div class="line"></div>
            </div>

            <button class="btn2"><img src="../assets/images/Group 3707.png" alt=""></button>
      </form>


        </div>
        
        </div>
    </div>
</template>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Fruktur&family=Inter:wght@100;200;300;400;600;700;800&family=Licorice&display=swap');
@import url('http://fonts.cdnfonts.com/css/sofia-pro');

    .cover{
            display: flex;
            width: 100vw;
            
    }
    .left{
        background: url('../assets/images/bg2.png');
        width: 724px;
        height: 100vh;
        padding: 30px 40px;
    }
    .right{
        padding-left: 200px;
        padding-top: 110px;
    }
    

    h1{
            width: 225px;
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
    h4{
      
        font-family: 'Inter';
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 28px;
        color: #7C7C7C;
        padding-left: 560px;
    }
    .img{
        padding: 245px 76px 0px 76px;
    }
    .log{
        margin-top: 72px;
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
      input{
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
</style>