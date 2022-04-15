<template>
    <div class="cover">
        <div class="left">
        <div class="logo">
        <a href="/"><img src="../assets/images/Mask group.png" alt=""></a>
        <img src="../assets/images/Group 3721.png" alt="" class="img">
      </div>
        </div>
        <div class="right">
        <h4>Already have an account?<a href="/login"> Log In</a></h4>
        <h1>Get Started</h1>
        <div class="one">
            <div>
                <img src="../assets/images/Group 3702.png" alt="">
            </div>
            <div>
                <h5>Individual / Car Owners</h5>
                <p>Personal account to manage your car and keep it in good condition.</p>
            </div>
            <div>
                <img src="../assets/images/Union.png" alt="">
            </div>
        </div>
        <div class="two">
            <div>
                <img src="../assets/images/Group 3699.png" alt="">
            </div>
            <div>
                <h5>Business</h5>
                <p>Business account for individual service providers and companies.</p>
            </div>
            <div>
                <!-- <img src="../assets/images/Union.png" alt=""> -->
            </div>
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
        padding-left: 100px;
        padding-top: 110px;
    }
    .one{
        width: 690px;
        height: 115px;
        background: #F5F3FF;
        border: 1px solid #5007E0;
        box-sizing: border-box;
        box-shadow: 0px 4px 14px 1px rgba(0, 0, 0, 0.04);
        border-radius: 10px;
        display: flex;
        align-items: center;
        padding: 0 30px;
        justify-content: space-between;
    }

    .two{
        width: 690px;
        height: 115px;
        background: #FFFFFF;
        box-shadow: 0px 5px 54px 1px rgba(55, 5, 153, 0.08);
        border-radius: 10px;
        margin-top: 20px;
        display: flex;
        align-items: center;
        padding: 0 30px;
        justify-content: space-between;
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
            margin-bottom: 60px;
    }
    a{
        color:  #5007E0;
    }
    h4{
      
        height: 28px;
        font-family: 'Inter';
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 28px;
        color: #7C7C7C;
        padding-left: 660px;
        margin-bottom: 148px;
    }
    .img{
        padding: 245px 76px 0px 76px;
    }
</style>