<template>
    
  <b-container class="main_container">
<div class="main_container____text">
    <h3>SAIBA O QUE VOCÊ VAI APRENDER DURANTE SEUS 3 ANOS</h3>
</div>

    <b-row class="main_container____row">
        <b-col lg="4" class="economia">
            <div class="economia_container">
                <figure>
                    <img src="financas card 1.png" alt="">
                </figure>
                <div class="economia_container__infos">
                    <p>Introduçao à Economia</p>
                </div>
            </div>
            </b-col>

        <b-col lg="4" class="financeira">
            <div class="financeira_container">
                <figure>
                    <img src="financas card 2.png" alt="">
                </figure>
                <div class="financeira_container__infos">
                    <p>Administração Financeira</p>
                </div>
            </div>
            </b-col>

        <b-col lg="4" class="plano">
            <div class="plano_container">
                <figure>
                    <img src="financas card 3.png" alt="">
                </figure>
                <div class="plano_container__infos">
                   <p>Plano de Negócios</p> 
                </div>
            </div>
            </b-col>

    </b-row>
   </b-container>
</template>


<style lang="scss" scoped>
.main_container {
    margin-bottom: 70px;
    font-family: sans-serif;
}

.main-container__text h3::after {
        position: absolute;
        content: '';
        bottom: -10%;
        left: 10%;
        width: 100px;
        height: 4px;
        background-color: rgb(212, 230, 59);
}
       

.main_container____text{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}

.main_container____text h3{
    font-size: 35px;
    line-height: 52px;
    text-align: center;
    position: relative;

    @media(max-width: 992px) {
        & {
            font-size: 24px;
        }
    }
}

.main_container____text h3::after {
        position: absolute;
        content: '';
        bottom: -10%;
        left: 45%;
        width: 100px;
        height: 4px;
        background-color: rgb(212, 230, 59);

    @media (max-width: 992px) {
         & {
            bottom: 5%;
            left: 37%;
        }
    }
}

.main_container____row{
    display: flex;
    align-items: center;
    justify-content: center;
}

.economia p, .plano p, .financeira p{
    font-size: 20px;
    text-align: center;
}
.economia_container, .plano_container, .financeira_container{
    width: 325px;
    height: 365px;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1px solid rgb(198, 214, 51);
    flex-direction: column;
    margin-top: 98px;
    position: relative;

     @media (max-width: 992px) {
         & {
           margin-top: 70px;
        }
    }
}
.economia_container, .financeira_container{
    padding: 0px 50px;
}

.plano_container li{
    padding-right: 40px;
}

.economia_container figure,
.financeira_container figure,
.plano_container figure{
    max-width: 200px;
    max-height: 200px;
    margin: 0;
    position: absolute;
    top: 5px;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 30px;

    img {
        width: 100%;
        height: 100%;
    }
}

.plano_container figure{
    margin-top: 80px;
}

.plano_container__infos{ 
    position: absolute;
    bottom: 60px;
    text-align: center;
}

.financeira_container__infos {
    text-align: center;
    margin-top: 210px;
}

.economia_container__infos {
    margin-top: 180px;
    text-align: center;
}

.economia, .financeira, .plano {
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>