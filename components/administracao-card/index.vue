<template>
    
  <b-container class="main_container">
<div class="main_container____text">
    <h3>SAIBA O QUE VOCÊ VAI APRENDER DURANTE SEUS 3 ANOS</h3>
</div>

    <b-row class="main_container____row">
        <b-col lg="4" class="gestao">
            <div class="gestao_container">
                <figure>
                    <img src="administracao card 1.png" alt="">
                </figure>
                <div class="gestao_container__infos">
                    <p>Gestão da Qualidade</p>
                </div>
            </div>
            </b-col>

        <b-col lg="4" class="teoria">
            <div class="teoria_container">
                <figure>
                    <img src="administracao card 2.png" alt="">
                </figure>
                <div class="teoria_container__infos">
                    <p>Teoria da Administração</p>
                </div>
            </div>
            </b-col>

        <b-col lg="4" class="recursos">
            <div class="recursos_container">
                <figure>
                    <img src="administracao card 3.png" alt="">
                </figure>
                <div class="recursos_container__infos">
                   <p>Administração de Recursos Humanos</p> 
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
        background-color: rgb(247, 162, 65);
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
        background-color: rgb(247, 162, 65);

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

.gestao p, .recursos p, .teoria p{
    font-size: 20px;
    text-align: center;
}
.gestao_container, .recursos_container, .teoria_container{
    width: 325px;
    height: 365px;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1px solid rgb(255, 183, 101);
    flex-direction: column;
    margin-top: 98px;
    position: relative;
}
.gestao_container, .teoria_container{
    padding: 0px 50px;
}

.recursos_container li{
    padding-right: 40px;
}

.gestao_container figure,
.teoria_container figure,
.recursos_container figure{
    max-width: 200px;
    max-height: 200px;
    margin: 0;
    position: absolute;
    top: 5px;
    display: flex;
    justify-content: center;
    align-items: center;

    img {
        width: 100%;
        height: 100%;
    }
}

.recursos_container__infos{ 
    position: absolute;
    bottom: 15px;
    text-align: center;
}

.teoria_container__infos {
    text-align: center;
    margin-top: 230px;
}

.gestao_container__infos {
    margin-top: 250px;
    text-align: center;
}

.gestao, .teoria, .recursos {
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>