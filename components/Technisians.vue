<template>
    <div>
        <div class="cover">
                <h2>Meet Some of Our registered Technicians</h2>

                <div class="tech">
                    <div v-for="(doc, index) in technician" :key="index"> 
                    <img  :src="require('@/assets/images/' + doc.img)" alt="" />
                    <div class="avatar_name">{{doc.name}}</div>
                <div class="avatar_skills">{{ doc.work }}</div>
                </div>
                </div>
        </div>
        <div class="trust ">
        <h3>
            Want to fix your car at an affordable price and with trusted technicians?
        </h3>
        <button>
            Sign me up
        </button>
        
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            technician: [
                {img:'Rectangle 5.png', name:'Jacob Jones',work: 'CEO at CleanMech'},
                {img:'Rectangle 6.png', name:'Jenny Wilson',work: 'Technician at safeDrive'},
                {img:'Rectangle 7.png', name:'Annette Black',work: 'Manager at mechatronics '},
                {img:'lady.png', name:'Esther Howard',work: 'Automechanic at BayWork'}

            ]
        }
    },
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Fruktur&family=Inter:wght@100;200;300;400;600;700;800&family=Licorice&display=swap');
@import url('http://fonts.cdnfonts.com/css/sofia-pro');
.cover{
    margin-top: 120px;
    margin-bottom: 120px;
}
.cover h2{
    height: 39px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 32px;
    line-height: 39px;
    text-align: center;
    text-transform: capitalize;
    color: #350B89;
    align-items: center;
    padding-bottom: 60px;

}
    .tech {
        display:flex;
        justify-content: center;
        align-items: center;
        text-align: center;
    }

    .trust{
        background: url('../assets/images/mask.png'), #7029FF;
        border-radius: 20px;
        width: 1401px;
        height: 203px;
        display: flex;
        justify-content: space-around;
        align-items: center;
        margin-left: 250px;
        margin-bottom: 100px;
    }
    h3{

        font-family: 'Inter';
        font-style: normal;
        font-weight: 600;
        font-size: 32px;
        line-height: 39px;
        color: #FFFFFF;
        width: 710px;
    }

    button{
        width: 208px;
        height: 60px;
        background: #FFB74C;
        border-radius: 30px 0px 30px 30px;
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 18px 40px 17px;
        color: #fff;
    }
</style>