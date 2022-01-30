<template>
    
  <b-container class="main_container">
<div class="main_container____text">
    <h3>SAIBA O QUE VOCÊ VAI APRENDER DURANTE SEUS 3 ANOS</h3>
</div>

    <b-row class="main_container____row">
        <b-col lg="4" class="anatomia">
            <div class="anatomia_container">
                <figure>
                    <img src="Icone Destaque 1 (1).png" alt="">
                </figure>
                <div class="anatomia_container__infos">
                    <p>Lógica de programação</p>
                </div>
            </div>
            </b-col>

        <b-col lg="4" class="saude">
            <div class="saude_container">
                <figure>
                    <img src="Icone Destaque 2 (1).png" alt="">
                </figure>
                <div class="saude_container__infos">
                    <p>Design de Interface e Usabilidade</p>
                </div>
            </div>
            </b-col>

        <b-col lg="4" class="lab">
            <div class="lab_container">
                <figure>
                    <img src="Icone Destaque 3 (1).png" alt="">
                </figure>
                <div class="lab_container__infos">
                   <p>Desenvolvimento de Aplicação para Dispositiveis Moveis</p> 
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
        background-color: #3e8fbe;
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
        background-color: rgb(73, 73, 73);

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

.anatomia p, .lab p, .saude p{
    font-size: 20px;
    text-align: center;
}
.anatomia_container, .lab_container, .saude_container{
    width: 325px;
    height: 365px;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1px solid #574885;
    flex-direction: column;
    margin-top: 98px;
    position: relative;
}
.anatomia_container, .saude_container{
    padding: 0px 50px;
}

.lab_container li{
    padding-right: 40px;
}

.anatomia_container figure,
.saude_container figure,
.lab_container figure{
    max-width: 300px;
    max-height: 300px;
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

.lab_container__infos{ 
    position: absolute;
    bottom: 15px;
    text-align: center;
}

.saude_container__infos {
    text-align: center;
    margin-top: 230px;
}

.anatomia_container__infos {
    margin-top: 260px;
    text-align: center;
}

.anatomia, .saude, .lab {
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>