<template>
    <div class="contain3">
        <div class="footer-article col">
            <img src="../assets/images/Mask group.png" alt="">
            <p class="text">
                Give your car the right service it needs with a unique automechanic shop 
                that links you with the best, competent and effective tecnicians.
            </p>

            <div class="social-links" style="display: flex; justify-content: space-between; width: 150px; margin-top: 40px">
                <img src="../assets/images/Path (1).png" alt="">
                <img src="../assets/images/Shape.png" alt="">
                <img src="../assets/images/Path.png" alt="">
                <img src="../assets/images/Shape (1).png" alt="">
            </div>
        </div>

        <div class="menu-links col">
            <div style="text-align: left;">
                <h4>Menu</h4>
                
                <ul>
                    <li>Home</li>
                    <li>About Us</li>
                    <li>Contact</li>
                </ul>
            </div>
        </div>

        <div class="contact col">
            <h4>Contact us</h4>
            <p>08160071243</p>
            <p>shopmeco@gmail.com</p>
            <p>
                No 12, Abike Street, Tando, Lagos state, Nigeria
            </p>
        
        </div>


        <div class="newsletter">
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

    * {
        box-sizing: border-box;
    }

    h4, li, p {
        font-size: inherit;
    }
    
    .contain3{
        background: #26046A;
        display: flex;
        flex-wrap: nowrap;
        justify-content: space-between;
        margin-top: 10rem;
        padding: 60px 80px;
        color: #DAD2EA; 
    }

    .footer-article {
        flex-basis: 30%;
    }

    .menu-links {
        flex-basis: 10%;
        display: flex;
        align-items: center;
        flex-direction: column;
    }

    .contact {
        flex-basis: 20%;
    }

    .newsletter {
        flex-basis: 25%;
    }

    h4{
        font-family: 'Sofia Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 20px;
        padding-bottom: 31px;
    }
    .text{
        /* width: 350px; */
        padding-top: 20px;
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 24px;
    }
    ul {
        padding: 0;
    }
    li{
        padding-bottom: 10px;
    }

    .contact p{
        /* width: 262px; */
        padding-bottom: 15px;
        margin: 0;
    }
    input{
        border-radius: 30px;
        background: #FFFFFF;
        height: 40px;
        padding-left: 20px;
        width: 100%;
    }

 @media only screen and (max-width: 900px) {
    .menu-links {
        display: none;
    }

        .contain3{
        display: grid;
        grid-template-columns: 1fr;
        column-gap: 2rem;
        place-items: center;
        text-align: center;
    }

    .col {
        padding-top: 0;
        padding-bottom: 4rem;
            margin-bottom: 4rem;
        border-bottom: 1px solid #fff;
        border-image: linear-gradient(to right, #26046A, #FFB74C, #26046A);
        border-image-slice: 1;
    }

    .footer-article {
        display: flex;
        align-items: center;
        flex-direction: column;
    }

    h4 {
        font-size: 30px;
        letter-spacing: 2px;
        font-weight: bold;
    }        
}

@media only screen and (max-width: 600px) {
    .contain3{
        padding: 40px 10px;   
    }

    .newsletter {
        padding: 0 5px;
    }

    .contact p {
        font-size: 20px;
    }

    .text {
        line-height: 2;
    }
}

</style>