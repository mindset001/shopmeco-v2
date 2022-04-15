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
          <li><a href="about">About</a></li>
          <li style="color: #FFB74C;"><a href="contact">Contact</a></li>
      </ul>

      <div>
          <button class="btn">Sign in</button>
          <button class="btn2">Sign Up</button>
      </div>
     </div>

     <div class="body">
      <div>
        <h1>Contact Us</h1>
        <p>
          Have more questions or enquires? Send us a message and we’ll get back to you as soon as possible.
        </p>

        <button class="btn3">Get Started</button>
      </div>
     
      <form action="">
            <h3 >Send us a message</h3>
            <div style="margin-bottom: 30px">
                <label for="name">Your name</label> <br>
            <input type="text">
            </div>
            <div style="margin-bottom: 30px">
                    <label for="name">Your email</label> <br>
            <input type="text">
            </div>
            <div>
                    <label for="name">Your name</label> <br>
            <textarea name="" id="" cols="30" rows="10"></textarea>
            </div>

            <button>Submit</button>
      </form>

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
    margin-bottom: 240px;
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
      padding-top: 20px;
  }
 .body img{
    width: 275px;
    height: 404px;
  
  }
 
  form{
    background: #FFFFFF;
    box-shadow: 0px 12px 60px rgba(99, 45, 206, 0.08);
    border-radius: 20px;
    width: 570px;
    height: 704px;
    display: flex;
    flex-direction: column;
    align-items: center;
    
  }
  h3{
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 400;
    font-size: 25px;
    line-height: 31px;
    color: #26046A;
    margin-top: 40px;
    margin-bottom: 40px;
  }
  input{
    border: 1px solid #B5B5B5;
    box-sizing: border-box;
    border-radius: 10px;width: 490px;
    height: 55px;
    
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

  textarea{
    background: #FFFFFF;
    border: 1px solid #B5B5B5;
    box-sizing: border-box;
    border-radius: 10px;
    width: 490px;
    height: 160px;
  }

  form button{
    width: 490px;
    height: 60px;
    background: #FFB74C;
    box-shadow: 0px 6px 50px rgba(74, 25, 172, 0.09);
    border-radius: 30px 0px 30px 30px;
    color: #fff;
    margin-top: 40px;
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 500;
    font-size: 25px;
    line-height: 25px;
  }
    
</style>