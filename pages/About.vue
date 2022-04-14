<template>
 <div>
 
     <div class="contain">
  <div>
     <div class="nav">
         <div class="logo">
        <img src="../assets/images/Mask group.png" alt="">
      </div>
      <ul>
          <li ><a href="/">Home</a></li>
          <li style="color: #FFB74C;"><a href="about">About</a></li>
          <li><a href="contact">Contact</a></li>
      </ul>

      <div>
          <button class="btn">Sign in</button>
          <button class="btn2">Sign Up</button>
      </div>
     </div>

     <div class="body">
      <div>
        <h1>Our Story</h1>
        <p>
          Give your car the right service it needs with a unique automechanic 
          shop that links you with the best, competent and effective tecnicians.
        </p>

        <button class="btn3">Get Started</button>
      </div>
      <div>
    <div>
          <img src="../assets/images/Rectangle27.png" alt="" class="fishes">
          <img src="../assets/images/man.png" alt="" class="fish">
    </div>
      </div>
      <div>
      <div style="margin-top: 7em">
          <img src="../assets/images/Rectangle 27 (1).png" alt="" class="fishe">
        <img src="../assets/images/woman.png" alt=""  class="fishing">
      </div>
      </div>

     </div>
  </div>

 
  </div>
        <Technisians/>
   
 </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Fruktur&family=Inter:wght@100;200;300;400;600;700;800&family=Licorice&display=swap');
@import url('http://fonts.cdnfonts.com/css/sofia-pro');

  .contain{
    background: url(../assets/images/background.png);
    height: 80vh;
    padding: 0 190px;
    padding-top: 15px;
    background-size: cover;
    background-position: center bottom;
    background-repeat: no-repeat;
  }
  .nav{
    display: flex;
    justify-content: space-between;
  }
  .btn2{
    background: #FFB74C;
    border-radius: 20px 0px 20px 20px;
    width: 135px;
    height: 45px;
    align-items: center;
    color: #fff;
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 400;
    font-size: 21px;
    line-height: 21px;
  }
   .btn3{
    background: #FFB74C;
    border-radius: 30px 0px 30px 30px;
    width: 212px;
    height: 60px;
    margin-top: 60px;
    align-items: center;
    color: #fff;
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 400;
    font-size: 21px;
    line-height: 21px;
  }
  ul{
    display: flex;
    justify-content: space-between;
    color: #fff;
  }
  li{
    padding-left: 32px;
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 400;
    font-size: 21px;
    line-height: 21px;
  }
  .btn{
    color: #fff;
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 400;
    font-size: 21px;
    line-height: 21px;
    padding-right: 33px;
  }
  a:hover{
    color: #FFB74C;
  }

  .body{
    padding-top: 120px;
    display: flex;
    justify-content: space-between;

  }

  h1{
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 52px;
    line-height: 63px;
    color: #FFFFFF;
    width: 729px;
  }
  .body p{

      font-family: 'Sofia Pro';
      font-style: normal;
      font-weight: 400;
      font-size: 26px;
      line-height: 31px;
      color: #DAD2EA;
      width: 617px;
      padding-top: 60px;
  }
 .body img{
    width: 275px;
    height: 404px;
  
  }
 
   .fishes
    {
      position: relative;
      top: 0;
      left: 0;
      z-index: 2;
    }
     .fish
    {
      position: absolute;
      top: 13em;
      left:  67em;
      z-index: 1;
    }
     .fishe
    {
      position: absolute;
      top: 21em;
      right: 17.6em;
      z-index: 2;
    }
   
     .fishing
    {
      position: relative;
      top: 1em;
      right:  4em;
      z-index: 1;
    }
    
</style>