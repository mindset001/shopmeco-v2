<template>
   <div class="all">
    <div class="search">
        <input type="text" placeholder="Search or type"> 
        <div><img src="../Sidebar/images/Ellipse 2239.png" alt=""></div>
        
        </div>

        <div >
            <h3>Service Provider details</h3>

            <div class="cont">
            <img src="../Sidebar/images/Rectangle 5775.png" alt="" class="cont2">
            <div>
                    <div >
                <div class="car">
                    <div>
                            <h2>Car Cleaning</h2>
                    <h4>CleanMech</h4>
                    </div>
                    <div>
                    <p>Auto-wash</p>
                </div>

                
                </div>
                <div class="next">
                    <img src="../Sidebar/images/Group 1000004168.png" alt="">
                    <p>273 reviews</p>
                </div>

                <div class="desc">
                    <h1>Description</h1>
                    <p>Give your car the right service it needs with a unique automechanic 
                    shop that links you with the best, competent and effective tecnicians.</p>
                </div>
                <div style="margin-top:30px; margin-left:20px;">
                    <button class="btn1">BOOK NOW</button>
                    <button class="btn2">REVIEW</button>
                </div>
            </div>

                    
            </div>
                
            </div>

               
        </div>
         <div class="bottom">
                    <h3>Provider’s Location</h3>
                    <div class="content">
                            <div>
                                <div style="display:flex; align-items: center; margin-top: 40px;">
                                <div style="margin-right: 30px;">
                                    <img src="../Sidebar/images/Icon.png" alt="">
                                </div>
                                <div>
                                    <h5>Address</h5>
                                <p>Mechanic Village
No 22, Bolaji Mc Anthony way, opposite Law School, Ikeja, Lagos State.</p>
                                </div>
                                
                                </div>

                                 <div>
                                <div style="display:flex; align-items: center; margin-top: 40px;">
                                <div style="margin-right: 30px;">
                                    <img src="../Sidebar/images/Icon.png" alt="">
                                </div>
                                <div>
                                    <h5>Opening hours</h5>
                                 <p>Monday-Friday</p>
                                 <p>8:00 AM-6:00 PM</p>
                                </div>
                                
                                </div>
                                </div>
                            
                            </div>
                            <div class="map"><img src="../Sidebar/images/Group 3747.png" alt=""></div>
                    </div>
                </div>
       
    </div>
</template>

<style scoped>

    input{
  width: 660px;
  height: 47px;
  background: #FFFFFF;
  border: 1px solid #D5CCFF;
  box-sizing: border-box;
  border-radius: 8px;
  padding: 10px 10px;
}
.search{
  display: flex;
  justify-content: space-between;
  padding: 30px 72px;
}
.all{

  width: 80vw;
}
h3{
    width: 1420px;
    height: 51px;
    background: #FDFDFF;
    box-shadow: 0px 12px 45px rgba(74, 25, 172, 0.06);
    border-radius: 8px;
    padding: 10px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 24px;
    line-height: 29px;
    color: #000000;
    margin-left: 60px;
}
.cont{
    width: 1420px;
    height: 380px;
    background: #FFFFFF;
    box-shadow: 0px 12px 45px rgba(74, 25, 172, 0.06);
    border-radius: 10px;
    margin-left: 60px;
    margin-top: 20px;
    padding: 30px;
    display: flex;
}
.cont2{
    margin-right: 5em;
}

.car{
    display: flex;
    justify-content: space-between;
    width: 45vw;
    padding: 0 20px;
}
.car p{
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 500;
    font-size: 18px;
    line-height: 18px;
    color: #FFB74C;
}
.next {
    display: flex;
    padding-left: 20px;
    align-items: center;
}
.next p{
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 26px;
    color: #7C7C7C;
    padding-left: 19.14px;
}
h4{
        font-family: 'Sofia Pro';
        font-style: normal;
        font-weight: 500;
        font-size: 22px;
        line-height: 22px;
        color: #7C7C7C;
        padding-top: 6px;
        padding-bottom: 30px;
}
h2{
        font-family: 'Sofia Pro';
        font-style: normal;
        font-weight: 500;
        font-size: 32px;
        line-height: 32px;
        color: #000000;
}
.desc p{
        font-family: 'Sofia Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 26px;
        color: #7C7C7C;
        width: 704px;
}
.desc h1{
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    color: #000000;
    padding-bottom: 15px;

}
.desc{
    padding-left: 19.14px;
    margin-top: 32px;
}
.btn1{
    width: 253px;
    height: 50px;
    background: #5007E0;
    border-radius: 7.57143px;
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    color: #FFFFFF;
    margin-right: 60px;
}
.btn2{
    background: #FFFFFF;
    border: 1px solid #5007E0;
    box-sizing: border-box;
    border-radius: 7.57143px;
    width: 253px;
    height: 50px;
}
.bottom{
    margin-top: 20px;
    width: 1037px;
    height: 109px;
    
   
}
.map{
    background: url('../Sidebar/images/Rectangle 5784.png');
    background-repeat: no-repeat;
    width: 450px;
    height: 319px;
    
}
.map img{
    position: relative;
    left: 6rem;
    top: 10rem;
    
}
.content{
    display: flex;
    justify-content: space-between;
     width: 1420px;
    margin-left: 60px;
    margin-top: 20px;
    padding: 30px;
    background: #FFFFFF;
    box-shadow: 0px 12px 45px rgba(74, 25, 172, 0.06);
    border-radius: 15px;
}
h5{
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 600;
    font-size: 20px;
    line-height: 16px;
    color: #1F1F1F;
}

.content p{
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 20px;
    color: #7C7C7C;
    mix-blend-mode: normal;
    width: 400px;
    padding-top: 10px;
}
</style>