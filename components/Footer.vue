<template>
    <div class="contain">
        <div>
        <img src="../assets/images/Mask group.png" alt="">
        <p class="text">Give your car the right service it needs with a unique automechanic shop 
        that links you with the best, competent and effective tecnicians.</p>

            <div style="display: flex; justify-content: space-between; width: 150px; margin-top: 20px">
                <img src="../assets/images/Path (1).png" alt="">
                <img src="../assets/images/Shape.png" alt="">
                <img src="../assets/images/Path.png" alt="">
                <img src="../assets/images/Shape (1).png" alt="">
            </div>
        </div>

        <div>
        <h4>Menu</h4>
            <ul>
            <li>Home</li>
            <li>About Us</li>
            <li>Contact</li>
            </ul>
        </div>

        <div class="contact">
        <h4>Contact us</h4>
        <p>08160071243</p>
        <p>shopmeco@gmail.com</p>
        <p>No 12, Abke Street, Tando, Lagos state, Nigeria</p>
        
        </div>

        <div>
            <h4>Suscribe to our Newsletter</h4>
            <input type="text" placeholder="Your email">
        </div>
        
    </div>
</template>


<script>
export default {
    
}
</script>


<style scoped>
@import url('http://fonts.cdnfonts.com/css/sofia-pro');
    .contain{
        background: #26046A;
        display: flex;
        justify-content: space-between;
        padding: 40px 180px;
        color: #DAD2EA;
       
    }
    h4{
     
        font-family: 'Sofia Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 20px;
        padding-bottom: 31px;
    }
    .text{
        width: 350px;
        padding-top: 20px;
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 24px;
    }
    li{
        padding-bottom: 15px;
    }
    .contact p{
        width: 262px;
        padding-bottom: 15px;
    }
    input{
        border-radius: 30px;
        background: #FFFFFF;
        height: 40px;
        padding-left: 20px;
    }

</style>