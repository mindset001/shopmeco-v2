<template>
    <div>
        <div class="brand">
                <h1 style="">We Specialize in these brands and many more</h1>
            <img src="../assets/images/Car icons.png" alt="">
        </div>

        <div class="service">
            <div class="parent">
                <img src="../assets/images/Group 5.png" alt="" class="bg">
                <div class="child">
                    <div class="one">
                        <div class="card">
                        <img src="../assets/images/Group 3678.png" alt="">
                        <h4>Avoid getting Stuck</h4>
                        <p>Worry no more if your car halts on the road as you can easily book a mechanic to help you fix it.</p>
                        </div>
                        <div class="card">
                            <img src="../assets/images/Group 3679.png" alt="">
                        <h4>Verified Technicians</h4>
                        <p>We work with verified automechanics and automechanic shop to provide you with the best service. </p>
                        </div>
                        <div class="card">
                            <img src="../assets/images/Group 3680.png" alt="">
                        <h4>No Hassle</h4>
                        <p>Easily book services of our technicians from the comfort of your home without stress.</p>
                        </div>
                    </div>
                    <div class="one" style="margin-top:60px;">
                        <div class="card">
                            <img src="../assets/images/Group 3683.png" alt="">
                        <h4>Real-time dispatch</h4>
                        <p>Our platform makes it easy for autoshops and mechanics to get notified of jobs, and also mange them.</p>
                        </div>
                        <div class="card">
                            <img src="../assets/images/Group 3682.png" alt="">
                        <h4>No paperwork</h4>
                        <p>Autoshops need not to worry about invoice. We provide invoice for customers after a completed service.</p>
                        </div>
                        <div class="card">
                                <img src="../assets/images/Group 3681.png" alt="">
                        <h4>Jobs Proximity</h4>
                        <p>There are lot of car owners across Nigeria. We bring automechanics close to car owners in the same vicinity.</p>
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
.brand{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 400px;
}
.brand h1{
    width: 558px;
    height: 24px;
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 500;
    font-size: 26px;
    line-height: 24px;
    letter-spacing: 0.01em;
    color: #7C7C7C;
    padding-bottom: 55.15px;
}
.brand img{
    width: 1458px;
    height: 68px;
}
.bg{

    height: 970px;
    width: 100%;
}
.parent{
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
}
.child{
    position: absolute;
    top: 7em;
    width: 80%;
   
}

.one{
    display: flex;
     justify-content: space-between;
}
.card{
    width: 440px;
    height: 341px;
    background: #FFFFFF;
    border-radius: 20px;
    margin-left: 60px;
    padding: 0 33px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;

  
}
.card img{
        width: 65px;
        height: 65px;
        margin-bottom: 30px;
    }
    .card h4{
        width: 270px;
        height: 24px;
        font-family: 'Sofia Pro';
        font-style: normal;
        font-weight: 500;
        font-size: 24px;
        line-height: 24px;
        text-align: center;
        letter-spacing: 0.01em;
        color: #1F1F1F;
        margin-bottom: 20px;
    }
    .card p{
        width: 315px;
        height: 96px;
        font-family: 'Sofia Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 20px;
        line-height: 24px;
        text-align: center;
        letter-spacing: 0.01em;
        color: #7C7C7C;
    }

</style>