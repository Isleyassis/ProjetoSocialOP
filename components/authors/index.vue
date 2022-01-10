<template>
    <section class="main-authors">
        <div class="main-authors__title">
            <h3> Autores </h3>
        </div>
        <div class="main-authors__wrapper">
            <div class="main-authors__writers">
                <b-container>
                    <h5 class="writers">ESCRITORES</h5>
                    <b-row>
                        <b-col col-lg="4">
                            <ul>
                                <li>Caio dos Santos Ferreira</li>
                                <li>Erick de Lima Silva</li>
                                <li>Francisca Leticia Lima da Silva</li>
                                <li>Francisco Gabriel M. Alburquerque</li>
                            </ul>
                        </b-col>
                        <b-col col-lg="4"> 
                            <ul>
                                <li>John Herbert Martins Frota</li>
                                <li>Michael Paulino de Souza</li>
                                <li>Rodrigo da Silva Lima</li>
                                <li>Widson Ferreira dos Santos</li>
                            </ul>  
                        </b-col>
                        <b-col col-lg="4"> 
                            <div class="main-authors__wrapper-img">
                                <img src="/Vetor Escritores.png" alt="imagem">
                            </div>
                        </b-col>
                    </b-row>              
                </b-container>
            </div>

             <div class="main-authors__writers">
                <b-container>
                    <h5 class="writers">ESCRITORES</h5>
                    <b-row>
                        <b-col col-lg="4">
                            <ul>
                                <li>Caio dos Santos Ferreira</li>
                                <li>Erick de Lima Silva</li>
                                <li>Francisca Leticia Lima da Silva</li>
                                <li>Francisco Gabriel M. Alburquerque</li>
                            </ul>
                        </b-col>
                        <b-col col-lg="4"> 
                            <ul>
                                <li>John Herbert Martins Frota</li>
                                <li>Michael Paulino de Souza</li>
                                <li>Rodrigo da Silva Lima</li>
                                <li>Widson Ferreira dos Santos</li>
                            </ul>  
                        </b-col>
                        <b-col col-lg="4"> 
                            <div class="main-authors__wrapper-img">
                                <img src="/Vetor Escritores.png" alt="imagem">
                            </div>
                        </b-col>
                    </b-row>              
                </b-container>
            </div>

             <div class="main-authors__writers">
                <b-container>
                    <h5 class="writers">ESCRITORES</h5>
                    <b-row>
                        <b-col col-lg="4">
                            <ul>
                                <li>Caio dos Santos Ferreira</li>
                                <li>Erick de Lima Silva</li>
                                <li>Francisca Leticia Lima da Silva</li>
                                <li>Francisco Gabriel M. Alburquerque</li>
                            </ul>
                        </b-col>
                        <b-col col-lg="4"> 
                            <ul>
                                <li>John Herbert Martins Frota</li>
                                <li>Michael Paulino de Souza</li>
                                <li>Rodrigo da Silva Lima</li>
                                <li>Widson Ferreira dos Santos</li>
                            </ul>  
                        </b-col>
                        <b-col col-lg="4"> 
                            <div class="main-authors__wrapper-img">
                                <img src="/Vetor Escritores.png" alt="imagem">
                            </div>
                        </b-col>
                    </b-row>              
                </b-container>
            </div>
        </div>
    </section>
</template>

<style scoped>
    .main-authors__title {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 70px;
    }

    .main-authors__title h3 {
        position: relative;
        font-style: normal;
        font-weight: normal;
        font-size: 30px;
        line-height: 45px;
        color: #000000;
        text-transform: uppercase;
    }

    .main-authors__title h3::after {
        position: absolute;
        content: '';
        bottom: -10%;
        left: 10%;
        width: 80%;
        height: 4px;
        background-color: #22A800;
    }

    .main-authors__writers {
        background-color: lightgreen;
        position: relative;
        padding: 20px 0;
        margin-bottom: 30px;
    }

    .writers {
        position: absolute;
        left: 30%;
        top: -13px;
        font-weight: bolder;
    }

    .main-authors__writers ul {
        list-style: none;
    }

    .main-authors__wrapper-img {
        width: 200px;
        height: 200px;
        position: absolute;
        top: -80px;
        left: 0; 
    }

    .main-authors__wrapper-img img{
        width: 100%;
        height: 100%;
    }

</style>