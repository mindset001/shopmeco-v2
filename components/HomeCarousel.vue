<template>
    <div>
    <h1 class="firsty">Hear out what people say about us</h1>
        <ssr-carousel :slides-per-page='1' loop center show-dots show-arrows >
  <slide :index='1'>
    <div class="flex">
        <div>
        <img src="../assets/images/Rectangle 27.png" alt="" class="fish">
        <img src="../assets/images/Rectangle 25.png" alt="" class="fishes">
        </div>
        <p>Give your car the right service it needs with a unique automechanic shop that links you with the best,
         competent and effective tecnicians.your car the right service it needs with a unique automechanic shop that links you with the best, 
         competent and effective tecnicians.</p>
    </div>
  
  </slide>
  <slide :index='2'>
  
     <div class="flex">
        <div>
        <img src="../assets/images/Rectangle 27.png" alt="" class="fish">
        <img src="../assets/images/Rectangle 25.png" alt="" class="fishes">
        </div>
        <p>Give your car the right service it needs with a unique automechanic shop that links you with the best,
         competent and effective tecnicians.your car the right service it needs with a unique automechanic shop that links you with the best, 
         competent and effective tecnicians.</p>
         </div>
  </slide>
  
  
</ssr-carousel>
    </div>
</template>
 
<script>
  import SsrCarousel from 'vue-ssr-carousel'
import ssrCarouselCss from 'vue-ssr-carousel/index.css'
 
  export default {
    name: 'MyComponent',
    components: { SsrCarousel },
     buildModules: [ 'vue-ssr-carousel/nuxt' ]
  }
  
</script> 

<style scoped>
    slide{
      
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 40px;
    padding: 0 40px;
}
p{
  width: 676px;
  height: 162px;
  font-family: 'Sofia Pro';
  font-style: normal;
  font-weight: 400;
  font-size: 26px;
  line-height: 27px;
  text-align: center;
  letter-spacing: 0.01em;
  color: #7C7C7C;
  padding-left: 80px;
  padding-top: 4em;
}

.fish{
    position: relative;
    z-index: 2;
    left: 26.07px;
    width: 238.93px;
    height: 351.02px;
}
.fishes{
    position: absolute;
    top: 26.07px;
    z-index: 1;
    width: 238.93px;
    height: 351.02px;
}
.firsty{

    display: flex;
    align-content: center;
    justify-content: center;
    width: 29em;
    height: 58px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 48px;
    line-height: 58px;
    color: #350B89;
    padding-left: -2em;
    padding-bottom: 20px;
}
</style>

    

