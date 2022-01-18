<template>
    <section class="main-authors">
        <div class="main-authors__title">
            <h3> Autores </h3>
        </div>
        <div class="main-authors__wrapper-dektop">
            <div class="main-authors__writers">
                <b-container>
                    <h5 class="writers">ESCRITORES</h5>
                    <b-row>
                        <b-col cols-lg='4'>
                            <ul>
                                <li v-for="(part, index) in participantsSeparated" :key="index"> 
                                    {{ part.students }} 
                                </li>
                            </ul>
                        </b-col>
                        <b-col cols-lg='4'> 
                            <ul>
                                <li v-for="(part, index) in participantsSeparated" :key="index"> 
                                    {{ part.students }} 
                                </li>
                            </ul>  
                        </b-col>
                        <b-col cols-lg='4'> 
                            <div class="main-authors__wrapper-img">
                                <img src="/Vetor Escritores.png" alt="imagem">
                            </div>
                        </b-col>
                    </b-row>              
                </b-container>
            </div>

             <div class="main-authors__developers">
                <b-container>
                    <h5 class="developers">DESENVOLVEDORES</h5>
                    <b-row>
                        <b-col cols-lg='4'> 
                            <div class="main-developers__wrapper-img">
                                <img src="/Vetor Desenvolvedores.png" alt="imagem">
                            </div>
                        </b-col>
                        <b-col cols-lg='4'>
                            <ul>
                                 <li v-for="(part, index) in participantsSeparated" :key="index"> 
                                    {{ part.students }} 
                                </li>
                            </ul>
                        </b-col>
                        <b-col cols-lg='4'> 
                            <ul>
                                <li v-for="(part, index) in participantsSeparated" :key="index"> 
                                    {{ part.students }} 
                                </li>
                            </ul>  
                        </b-col>
                    </b-row>              
                </b-container>
            </div>

             <div class="main-authors__researchers">
                <b-container>
                    <h5 class="researchers">PESQUISADORES</h5>
                    <b-row>
                        <b-col cols-lg='4'>
                            <ul>
                                <li v-for="(part, index) in participantsSeparated" :key="index"> 
                                    {{ part.students }} 
                                </li>
                            </ul>
                        </b-col>
                        <b-col cols-lg='4'> 
                            <ul>
                                 <li v-for="(part, index) in participantsSeparated" :key="index"> 
                                    {{ part.students }} 
                                </li>
                            </ul>  
                        </b-col>
                        <b-col cols-lg='4'> 
                            <div class="main-researchers__wrapper-img">
                                <img src="/Vetor Prsquisadores.png" alt="imagem">
                            </div>
                        </b-col>
                    </b-row>              
                </b-container>
            </div>
        </div>

        <!-- Mobile -->

        <div class="main-authors__wrapper-mobile">
            <div class="main-authors__writers">
                <b-container>
                    <h5 class="writers-mobile">ESCRITORES</h5>
                    <b-row>
                        <b-col cols='6'>
                            <ul>
                                <li v-for="(part, index) in participantsTogether" :key="index"> 
                                    {{ part.students }} 
                                </li>
                            </ul>
                        </b-col>
                        <b-col cols='6'> 
                            <div class="main-writers__wrapper-mobile-img">
                                <img src="/Vetor Escritores.png" alt="imagem">
                            </div>
                        </b-col>
                    </b-row>              
                </b-container>
            </div>

             <div class="main-authors__developers">
                <b-container>
                    <h5 class="developers-mobile">DESENVOLVEDORES</h5>
                    <b-row>
                        <b-col cols='6'> 
                            <div class="main-developers__wrapper-mobile-img">
                                <img src="/Vetor Desenvolvedores.png" alt="imagem">
                            </div>
                        </b-col>
                        <b-col cols='6'>
                            <ul>
                                <li v-for="(part, index) in participantsTogether" :key="index"> 
                                    {{ part.students }} 
                                </li>
                            </ul>
                        </b-col>
                    </b-row>              
                </b-container>
            </div>

            <div class="main-authors__researchers">
                <b-container>
                    <h5 class="researchers-mobile">ESCRITORES</h5>
                    <b-row>
                        <b-col cols="6">
                            <ul>
                                <li v-for="(part, index) in participantsTogether" :key="index"> 
                                    {{ part.students }} 
                                </li>
                            </ul>
                        </b-col>
                        <b-col cols="6"> 
                            <div class="main-researchers__wrapper-mobile-img">
                                <img src="/Vetor Prsquisadores.png" alt="imagem">
                            </div>
                        </b-col>
                    </b-row>              
                </b-container>
            </div>
        </div>

    </section>
</template>

<script>
export default {
    data() {
        return {
            participantsSeparated: [
                {
                    students: 'John Herbert Martins Frota'
                },
                {
                    students: 'Michael Paulino de Souza'
                },
                {
                    students: 'Rodrigo da Silva Lima'
                },
                {
                    students: 'Widson Ferreira dos Santos'
                }
            ],
            participantsTogether: [
               {
                    students: 'John Herbert Martins Frota'
                },
                {
                    students: 'Michael Paulino de Souza'
                },
                {
                    students: 'Rodrigo da Silva Lima'
                },
                {
                    students: 'Widson Ferreira dos Santos'
                },
                 {
                    students: 'John Herbert Martins Frota'
                },
                {
                    students: 'Michael Paulino de Souza'
                },
                {
                    students: 'Rodrigo da Silva Lima'
                },
                {
                    students: 'Widson Ferreira dos Santos'
                }
            ],
        }
    }
}
</script>

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
        width: 100px;
        height: 4px;
        background-color: #22A800;
    }

    .main-authors__writers {
        background-color: #CBD898;
        position: relative;
        padding: 20px 0;
        margin-bottom: 60px;
    }

    .writers {
        position: absolute;
        left: 28%;
        top: -13px;
        font-weight: bolder;
    }

    .main-authors__writers ul {
        list-style: none;
    }

    .main-authors__wrapper-img {
        width: 250px;
        height: 250px;
        position: absolute;
        top: -100px;
        left: 0; 
    }

    .main-authors__wrapper-img img{
        width: 100%;
        height: 100%;
    }


     .main-authors__developers {
        background-color: #EAF6B9;
        position: relative;
        padding: 20px 0;
        margin-bottom: 60px;
    }

    .developers {
        position: absolute;
        left: 55%;
        top: -13px;
        font-weight: bolder;
    }

    .main-authors__developers ul {
        list-style: none;
    }

    .main-developers__wrapper-img {
        width: 250px;
        height: 250px;
        position: absolute;
        top: -100px;
        right: 20px; 
    }

    .main-developers__wrapper-img img{
        width: 100%;
        height: 100%;
    }
    

    .main-authors__researchers {
        background-color: #E0F688;
        position: relative;
        padding: 20px 0;
        margin-bottom: 60px;
    }

    .researchers {
        position: absolute;
        left: 28%;
        top: -13px;
        font-weight: bolder;
    }

    .main-authors__researchers ul {
        list-style: none;
    }

    .main-researchers__wrapper-img {
        width: 250px;
        height: 250px;
        position: absolute;
        top: -100px;
        left: 0; 
    }

    .main-researchers__wrapper-img img{
        width: 100%;
        height: 100%;
    }

    /* mobile style */

    .main-authors__wrapper-mobile {
        display: none;
    }

    .writers-mobile {
        position: absolute;
        left: 8%;
        top: -13px;
        font-weight: bolder;
        font-size: 18px;
    }

    .main-authors__wrapper-mobile ul {
        list-style: none;
        padding: 0;
    }

    .main-authors__wrapper-mobile ul li {
        font-size: 11px;
        font-weight: bolder;
    }

    .main-writers__wrapper-mobile-img {
        width: 170px;
        height: 170px;
        position: absolute;
        top: -10px;
        right: 0;
    }

    .main-writers__wrapper-mobile-img img{
        width: 100%;
        height: 100%;
    }


     .developers-mobile {
        position: absolute;
        right: 8%;
        top: -13px;
        font-weight: bolder;
        font-size: 18px;
    }

    .main-authors__wrapper-mobile ul {
        list-style: none;
        padding: 0;
    }

    .main-authors__wrapper-mobile ul li {
        font-size: 11px;
        font-weight: bolder;
    }

    .main-developers__wrapper-mobile-img {
        width: 170px;
        height: 170px;
        position: absolute;
        top: -10px;
        right: 0;
    }

    .main-developers__wrapper-mobile-img img{
        width: 100%;
        height: 100%;
    }


     .researchers-mobile {
        position: absolute;
        left: 8%;
        top: -13px;
        font-weight: bolder;
        font-size: 18px;
    }

    .main-authors__wrapper-mobile ul {
        list-style: none;
        padding: 0;
    }

    .main-authors__wrapper-mobile ul li {
        font-size: 11px;
        font-weight: bolder;
    }

    .main-researchers__wrapper-mobile-img {
        width: 170px;
        height: 170px;
        position: absolute;
        top: -10px;
        right: 0;
    }

    .main-researchers__wrapper-mobile-img img{
        width: 100%;
        height: 100%;
    }


    /* medias globais */

    @media(max-width: 998px){
        .container, .container-sm, .container-md{
            max-width: 100%;
        }
    }

    @media(max-width: 765px){

        .main-authors__wrapper-dektop {
            display: none;
        }

        .main-authors__wrapper-mobile {
            display: block;
        }

        .main-authors__title h3 {
            font-size: 24px;
        }

        .main-authors__title h3::after {
            bottom: 5%;
            left: 2%;
        }
    }
</style>