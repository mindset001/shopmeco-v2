<template>
    <div class="contain1">
        <div>
        
                 <h1>
        Who can use Shopmeco?
    </h1>

    <div class="parent">
    <div class="left">
            <div class="top">
                <div style="display:flex;  justify-content: space-between; align-items: center; " class="mobil">
                        <div>
                        
                        <h2>01.</h2>
                        <h4 style="color:#fff;">Car Owners</h4>
                        <p>Give your car the right service it needs with a unique automechanic shop that 
                        links you with the best, 
                        competent and effective tecnicians.</p>
                        
                        </div>
                        <div>
                            <img src="../assets/images/Rectangle 79.png" alt="">
                        </div>

                </div>
            
            </div>

            <div class="bottom" >
                    <div class="one">
                    
                             <div>
                        
                        <h2>04.</h2>
                        <h4>Auto Part Sellers</h4>
                        <p>Give your car the right service it needs with a unique automechanic shop that 
                        links you with the best, 
                        competent and effective tecnicians.</p>
                        
                        </div>
                        <div>
                            <img src="../assets/images/Rectangle 82.png" alt="">
                        </div>
                    </div>

                    <div class="two">
                             <div>
                        
                        <h2>05.</h2>
                        <h4>Auto-Service Provider</h4>
                        <p>Give your car the right service it needs with a unique automechanic shop that 
                        links you with the best, 
                        competent and effective tecnicians.</p>
                        
                        </div>
                        <div>
                            <img src="../assets/images/Rectangle 83.png" alt="" style="padding-top:20px;">
                        </div>
                    </div>
            </div>
    
    </div>

    <div class="right">
    
            <div class="up">
            <div>
                            <img src="../assets/images/Rectangle 80.png" alt="" style="padding-bottom:30px;">
                        </div>
              <div>
                        
                        <h2 style="color:#1F1F1F;">02.</h2>
                        <h4>Auto Repair Shops</h4>
                        <p style="color:#7C7C7C; width:320px;">Give your car the right service it needs with a unique automechanic shop that 
                        links you with the best, 
                        competent and effective tecnicians.</p>
                        
                        </div>
                        
            
            </div>

            <div class="down">
            
                      <div>
                        
                        <h2 style="color:#1F1F1F;">03.</h2>
                        <h4>Auto Washing Center</h4>
                        <p style="color:#7C7C7C; width:320px; padding-bottom:30px;">Give your car the right service it needs with a unique automechanic shop that 
                        links you with the best, 
                        competent and effective tecnicians.</p>
                        
                        </div>
                        <div>
                            <img src="../assets/images/Rectangle 81.png" alt="">
                        </div>
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

@import url('https://fonts.googleapis.com/css2?family=Fruktur&family=Inter:wght@100;200;300;400;600;700;800&family=Licorice&display=swap');
@import url('http://fonts.cdnfonts.com/css/sofia-pro');

.contain1{
padding-top: 170px;
    display: flex;
    justify-content: center;
    align-content: center;
}
.parent{
       
        display: flex;      
}

.left{
    display: grid;
        grid-template-rows: 1fr 2fr;
        margin-right: 40px;
}
.top{
    width: 920px;
    height: 339px;
    background: #7029FF;
    border-radius: 20px;
    padding: 55px 60px;
    margin-top: 100px;
    margin-bottom: -10px;
}
h2{
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 500;
    font-size: 70px;
    line-height: 70px;
    color: #FFFFFF;
}
h4{
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 500;
    font-size: 30px;
    line-height: 24px;
    align-items: center;
    letter-spacing: 0.01em;
    color: #FFFFFF;
    margin-top: 20pxn;
}
p{
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 18px;
    color: #F4F2FE;
    margin-top: 20px;
    width: 396px;
}
.bottom{
    display: flex;
    
    
}

.one{
    padding: 30px 50px;
    width: 402px;
    height: 607px;
    background: #F4F2FE;
    border: 1px solid #A594FE;
    box-sizing: border-box;
    border-radius: 20px;
}
.two{
    width: 478px;
    height: 607px;
    background: #F4F2FE;
    border: 1px solid #A594FE;
    box-sizing: border-box;
    border-radius: 20px;
    padding: 30px 50px;
    margin-left: 40px;
}

.one p{
    color: #7C7C7C;
    width: 292px;
    padding-bottom: 51px;

}
.one h2, h4{
    color: #1F1F1F;
}
.two p{
    color: #7C7C7C;
    width: 368px;
    padding-bottom: 51px;

}
.two h2, h4{
    color: #1F1F1F;
}
.up{
    width: 440px;
    height: 458px;
    padding: 30px 50px;
    background: #F4F2FE;
    border: 1px solid #A594FE;
    box-sizing: border-box;
    border-radius: 20px;
    margin-top: 40px;
     margin-bottom: 40px;
}
.down{
   
    width: 440px;
    height: 490px;
    background: #FFCC6C;
    border-radius: 20px;
    padding: 30px 60px;
   
}
h1{
    width: 720px;
    height: 58px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 48px;
    line-height: 58px;
    color: #350B89;
    padding-bottom: 40px;
}

@media only screen and (max-width: 600px) {
    .contain1{
    padding-top: 170px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-content: center;
}
.parent{
       
        display: flex;
        flex-direction: column;
        
}
.left{
    display: flex;
        flex-direction: column;
        margin-right: 40px;
}

.bottom{
    display: flex;
    flex-direction: column;
    
    
}
.top{
    margin-left: 15px;
    width: 380px;
    height: 607px;
    box-sizing: border-box;
    border-radius: 20px;
}
.one{
   margin-left: 15px;
    width: 380px;
    height: 607px; 
     margin-bottom: 20px
}
.up{
   margin-left: 15px;
    width: 380px;
    height: 607px; 
     margin-bottom: 20px
}
.down{
   margin-left: 15px;
    width: 380px;
    height: 607px; 
     margin-bottom: 20px
}

.two{
     padding: 30px 50px;
    width: 380px;
    height: 607px;
    box-sizing: border-box;
    border-radius: 20px;
    margin-left: 15px;
    margin-bottom: 20px
}
.two p{
    width: 300px;
}


h2{
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 500;
    font-size: 70px;
    line-height: 70px;
}
h4{
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 500;
    font-size: 30px;
    line-height: 24px;
    align-items: center;
    letter-spacing: 0.01em;
    margin-top: 20pxn;
}
p{
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 400;
    font-size: 18px;
    line-height: 18px;
    margin-top: 20px;
    width: 216px;
}
h1{
    width: 720px;
    height: 58px;
    font-size: 28px;
    padding-left: 20px;
}
.mobil{
    display: flex;
    flex-direction: column;
}

}
</style>