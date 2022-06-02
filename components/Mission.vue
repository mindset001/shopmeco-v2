<template>
    <div>
        <div class="cover">
            <h2>Our Mission & Vision</h2>
            <div class="all">
                <div style="margin-right: 60px" class="mission">
                <img src="../assets/images/Group 1000004166.png" alt="">
                <p>Give your car the right service it needs with a unique automechanic shop that links you with the best, competent and effective tecnicians.</p>
                
                </div>
                <div class="mission" style="margin-left: 80px">
                <img src="../assets/images/Group 1000004166.png" alt="">
                <p>Give your car the right service it needs with a unique automechanic shop that links you with the best, competent and effective tecnicians.</p>
                
                </div>
            </div>

             
        </div>
        

   <div>
   <h4>We connect customers with expert technicians.</h4>
          <div class="control">
        
          <div class="iCountUp">
    <ICountUp
      :delay="delay"
      :endVal="endVal"
      :options="options"
      @ready="onReady"
      class=""
    />
    <p>registered technicians</p>
  </div>
     <div class="iCountUp">
    <ICountUp
      :delay="delay"
      :endVal="endValy"
      :options="options"
      @ready="andReady"
    />
    <p>registered companies</p>
  </div>
  <div class="iCountUp">
    <ICountUp
      :delay="delay"
      :endVal="endValue"
      :options="options"
      @ready="weReady"
    />
    <p>registered customers</p>
  </div>
  <div>
      <img src="../assets/images/mask1.png" alt="">
  </div>
       </div>
   </div>
    </div>
</template>

<script type="text/babel">
  import ICountUp from 'vue-countup-v2';
  export default {
    components: {
      ICountUp
    },
    data() {
      return {
        delay: 1000,
        endVal: 50,
        endValy:30,
        endValue:70,
        options: {
        //   useEasing: true,
        //   useGrouping: true,
        //   separator: ',',
        //   decimal: '.',
        //   prefix: 'nb',
          suffix: '+'
        }
      };
    },
    methods: {
      onReady: function(instance, CountUp) {
        // const that = this;
        // instance.update(this.endVal);
        instance.update( this.endVal)
      },
      andReady: function(instance, CountUp) {
        // const that = this;
        // instance.update(this.endVal);
        instance.update( this.endValy)
      },
       weReady: function(instance, CountUp) {
        // const that = this;
        // instance.update(this.endVal);
        instance.update( this.endValue)
      },
    
      
    }
  };
</script>

<style scoped>
        .all{
            display:flex; 
        justify-content: space-between;
        align-items: center;
        }
    .mission{
        display:flex; 
        justify-content: space-around;
        margin-top: 40px;

    }

    p{
        width: 520px;
        height: 104px;
        font-family: 'Sofia Pro';
        font-style: normal;
        font-weight: 400;
        font-size: 24px;
        line-height: 26px;
        color: #7C7C7C;
    }
    img{
        width: 65px;
        height: 65px;
        margin-right: 30px;
    }
    .cover{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        margin-top: 100px;
        width: 100%;
    }
    .cover h2{
        width: 1015px;
        height: 39px;
        font-family: 'Inter';
        font-style: normal;
        font-weight: 600;
        font-size: 32px;
        line-height: 39px;
        text-align: center;
        color: #350B89;
        margin-bottom: 32px;

    }
     .iCountUp {
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 600;
    font-size: 60px;
    line-height: 35px;
    color: #350B89;
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
  }
  .iCountUp p{
    width: 262px;
    height: 35px;
    font-family: 'Sofia Pro';
    font-style: normal;
    font-weight: 400;
    font-size: 26px;
    line-height: 35px;
    text-align: center;
    color: #5007E0;
    padding-top: 17px;
  }

  .control{
    background: #F5F3FF;
    width: 100%;
    height: 8rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-left: 16rem;
    margin-top: 40px;
  }
  .control img{
    width: 126px;
    height: 128px;
  }

  h4{
      width: 100vw;
      height: 35px;
      font-family: 'Sofia Pro';
      font-style: normal;
      font-weight: 400;
      font-size: 26px;
      line-height: 35px;
      color: #7C7C7C;
      text-align: center;
      margin-top: 110px;
  }
</style>