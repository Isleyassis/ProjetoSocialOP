<template>
    <div class="main-objective">
        <div class="main-objective__title">
            <h3> SAIBA MAIS DO NOME DO NOSSO PROJETO </h3>
        </div>
        <div class="main-objective__text">
            <div class="main-objective__wrapper-img">
                <img src="Foto Objetivo.jpeg" alt="">
            </div>
            <div class="main-objective__wrapper-text">           
                <h4>NOSSO OBJETIVO</h4>
                <p>
                    Nos últimos tempos, ficou visível que os alunos ao ingressarem na EEEP ONÉLIO PORTO não possuem quase nenhum conhecimento sobre os cursos técnicos que irão adentrar, e muita das vezes não conhecem as próprias diretrizes da escola. Ocorre-se que durante o decorrer de sua trajetória, diversos alunos abandonam o curso, pois não conseguem acompanhar as disciplinas apresentadas durante todo o caminho. Entendendo que a etapa escolar é a base para a correção dessas lacunas de conhecimento técnico, nos propomos a realizar um projeto social que contribua de forma positiva para o ambiente escolar, auxiliando aos novos alunos que estarão ingressando na escola nos próximos anos. Logo, Este projeto tem como principal objetivo apresentar aos jovens na faixa etária entre 15 e 16 anos que estarão ingressando na escola profissional sobre os cursos técnicos oferecidos pela instituição.
                </p>
            </div>
        </div>
    </div>
</template>
<style scoped lang="scss">
    .main-objective {
        margin-bottom: 40px;
    }

    .main-objective__title{
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        margin-bottom: 180px;

        @media(max-width: 1200px) {
            & {
                margin-bottom: 320px;
            }
        }

        @media(max-width: 550px) {
            & {
                margin-bottom: 250px;
            }
        }
    }

    .main-objective__title h3{
        font-size: 35px;
        line-height: 52px;
        text-align: center;
        position: relative;

        @media(max-width: 992px) {
            & {
                font-size: 24px;
                line-height: 1;
            }
        }
    }

    .main-objective__title h3::after {
        position: absolute;
        content: '';
        bottom: -20%;
        left: 32%;
        width: 200px;
        height: 4px;
        background-color: #22A800;

        @media (max-width: 500px) {
            & {
                bottom: -17%;
                left: 22%;
            }
        }
    }

    .main-objective__text {
        display: flex;
        justify-content: flex-end;
        position: relative;

        .main-objective__wrapper-img {
            position: absolute;
            width: 500px;
            height: 300px;

            img {
                width: 100%;
                height: 100%;
            }
            
            @media(min-width: 1651px) {
                & {
                    left: 17%;
                    top: -120px;
                }
            }
            @media(max-width: 1650px) {
                & {
                    left: 10%;
                    top: -100px;
                }
            }
            @media(max-width: 1550px) {
                & {
                    left: 6%;
                    top: -120px;
                }
            }
            @media(max-width: 1180px) {
                & {
                    left: 23%;
                    top: -280px;
                }
            }
            @media(max-width: 780px) {
                & {
                    left: 15%;
                    top: -280px;
                }
            }
            @media(max-width: 600px) {
                & {
                    height: 250px;
                    left: 7%;
                    top: -200px;
                    width: 88%;
                }
            }
        }

        .main-objective__wrapper-text {
            width: 60%;
            background-color: lightgray;
            padding: 20px 100px;

            h4 {
                color: #22A800;
            }

            p {
                text-align: justify;
            }

            @media(max-width: 1180px) {
                & {
                    width: 100%;
                    padding: 40px 100px;
                }
            }

            @media (max-width: 600px) {
                & {
                    padding: 70px 20px 10px 20px;
                }
            }
        }
    }


    // 1280px 1550px
</style>