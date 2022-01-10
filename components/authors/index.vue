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
                                <li v-for="(part, index) in participants" :key="index"> 
                                    {{ part.students }} 
                                </li>
                            </ul>
                        </b-col>
                        <b-col col-lg="4"> 
                            <ul>
                                <li v-for="(part, index) in participants" :key="index"> 
                                    {{ part.students }} 
                                </li>
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

             <div class="main-authors__developers">
                <b-container>
                    <h5 class="developers">DESENVOLVEDORES</h5>
                    <b-row>
                        <b-col col-lg="4"> 
                            <div class="main-developers__wrapper-img">
                                <img src="/Vetor Desenvolvedores.png" alt="imagem">
                            </div>
                        </b-col>
                        <b-col col-lg="4">
                            <ul>
                                 <li v-for="(part, index) in participants" :key="index"> 
                                    {{ part.students }} 
                                </li>
                            </ul>
                        </b-col>
                        <b-col col-lg="4"> 
                            <ul>
                                <li v-for="(part, index) in participants" :key="index"> 
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
                        <b-col col-lg="4">
                            <ul>
                                <li v-for="(part, index) in participants" :key="index"> 
                                    {{ part.students }} 
                                </li>
                            </ul>
                        </b-col>
                        <b-col col-lg="4"> 
                            <ul>
                                 <li v-for="(part, index) in participants" :key="index"> 
                                    {{ part.students }} 
                                </li>
                            </ul>  
                        </b-col>
                        <b-col col-lg="4"> 
                            <div class="main-researchers__wrapper-img">
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
            participants: [
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
            ]
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
        background-color: rgba(89, 187, 89, 0.685);
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
        background-color: rgba(205, 238, 144, 0.644);
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
        background-color: rgb(211, 209, 100);
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
</style>