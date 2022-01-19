<template>
<b-container class="main_container">
<div class="main_container____text">
    <h3>SOBRE A ESCOLA</h3>
</div>
<!-- . -->
    <b-row class="main_container____row">
        <b-col lg="4" class="local">
            <div class="local_container">
                <figure>
                    <img src="Icone Localização.png" alt="">
                </figure>
                <div class="local_container__infos">
                    <h2> Localização </h2>
                    <p>Av. E, 471 - Pref. José Walter, Fortaleza - CE, 604750-040</p>
                </div>
            </div>
            </b-col>

        <b-col lg="4" class="phone">
            <div class="phone_container">
                <figure>
                    <img src="Icone Telefone.png" alt="">
                </figure>
                <div class="phone_container__infos">
                    <h2> Contato </h2>
                    <p>(85) 3101-2984</p>
                </div>
            </div>
            </b-col>

        <b-col lg="4" class="cursos">
            <div class="cursos_container">
                <figure>
                    <img src="Icone Cursos.png" alt="">
                </figure>
                <div class="cursos_container__infos">
                    <h2> Cursos </h2>
                    <ul>
                        <li>Administração</li>
                        <li>Enfermagem</li>
                        <li>Finanças</li>
                        <li>Desenvolvimento de sistemas</li>
                    </ul>
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

.main-authors__title h3::after {
        position: absolute;
        content: '';
        bottom: -10%;
        left: 10%;
        width: 100px;
        height: 4px;
        background-color: #22A800;
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
        left: 32%;
        width: 100px;
        height: 4px;
        background-color: #22A800;

    @media (max-width: 992px) {
         & {
            bottom: 5%;
            left: 32%;
        }
    }
}

.main_container____row{
    display: flex;
    align-items: center;
    justify-content: center;
}

.local_container, .cursos_container{
    background: #E8E8E8;
}

.local h2, .cursos h2, .phone h2{
    font-size: 30px;
    line-height: 45px;
    color: #146400;
}

.cursos ul{
    list-style: none;
}

.local p, .cursos p, .phone p{
    font-size: 20px;
    line-height: 30px;
    text-align: center;
}
.local_container, .cursos_container, .phone_container{
    width: 325px;
    height: 365px;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1px solid #C4C4C4;
    flex-direction: column;
    margin-top: 98px;
    position: relative;
}
.local_container, .phone_container{
    padding: 0px 50px;
}

.cursos_container li{
    padding-right: 40px;
}

.local_container figure,
.phone_container figure,
.cursos_container figure{
    max-width: 150px;
    max-height: 150px;
    margin: 0;
    position: absolute;
    top: 10px;


    img {
        width: 100%;
        height: 100%;
    }
}

.cursos_container__infos{ 
    position: absolute;
    bottom: 15px;
    text-align: center;
}

.phone_container__infos {
    text-align: center;
    margin-top: 100px;
}

.local_container__infos {
    margin-top: 150px;
    text-align: center;
}

.local, .phone, .cursos {
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>