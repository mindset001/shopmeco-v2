<template>
    <div>
        <div class="brand">
                <h1 style="">We Specialize in these brands and many more</h1>
            <img src="../assets/images/Car icons.png" alt="">
        </div>

        <div class="service">
                <div class="child">
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
</template>

<script>
export default {
    
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Fruktur&family=Inter:wght@100;200;300;400;600;700;800&family=Licorice&display=swap');
@import url('http://fonts.cdnfonts.com/css/sofia-pro');

*, 
::before, 
::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

.brand{
    max-width: 1250px;
    margin: auto;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 400px;
}

.brand h1{
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 500;
    font-size: 26px;
    line-height: 24px;
    letter-spacing: 0.01em;
    color: #7C7C7C;
    padding-bottom: 60px;
    text-align: center;
}

.brand img{
    max-width: 100%;
    padding: 0 2rem;
    height: 68px;
}

.service{
    background: url('../assets/images/Group 5.png');
    background-size: cover;
    background-repeat: no-repeat;
    display: grid;
    place-items: center;
    min-height: 900px;
    padding: 2rem;
}

.child{
    width: 100%;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    /* padding: 5rem; */
    place-items: center;
}

.card{
    max-width: 100%;
    height: 100%;
    /* height: 341px; */
    background: #FFFFFF;
    border-radius: 20px;
    /* margin-left: 60px; */
    padding: 1rem 33px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    box-shadow: 5px 5px 10px -1px rgba(0, 0, 0, 0.1),
  -5px -5px 10px -1px rgba(0, 0, 0, 0.06);  
    }

    .card img{
        width: 65px;
        height: 65px;
        margin-bottom: 30px;
    }

    .card h4{
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
        font-family: 'Sofia Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 20px;
        line-height: 24px;
        text-align: center;
        letter-spacing: 0.01em;
        color: #7C7C7C;
    }

     @media only screen and (max-width: 900px) {
        .brand {
            height: 200px;
            margin-bottom: 4rem;
        }
     }

    @media only screen and (max-width: 600px) {

       .brand h1 {
        padding: 1rem 2rem 60px;
       }
    }

</style>