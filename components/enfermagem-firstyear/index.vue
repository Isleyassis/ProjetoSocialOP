<template>
    <div class="main-first">
        <div class="main-first__wrapper">
            <b-container>
                <div class="main-first__title">
                    <h1> 1º Ano </h1>
                </div>

                <b-row>
                    <b-col cols="8" lg="6">
                        <div class="main-first__subjects">
                            <h4>Disciplinas:</h4>
                            <ul>
                                <li>Informática Basica</li>
                                <li>Introdução à Profissão, Legislação e Bioética</li>
                                <li>Políticas de Saúde</li>
                                <li>Promoção, Prevenção e Vigilância em Saúde</li>
                                <li>Anatomia e Fisiologia Humana Básica</li>
                                <li>Educação em Saúde e Práticas Integrativas</li>
                                <li>Saúde e Segurança no Trabalho</li>
                                <li>Gestão em Saúde e Redes de Atenção</li>
                                <li>Saúde Coletiva</li>
                            </ul>
                        </div>
                    </b-col>
                    <b-col cols="4" lg="6">
                        <div class="main-first__hours">
                            <h4>Horas:</h4>
                            <ul>
                               <li>100 HORAS</li>
                                <li>60 HORAS</li>
                                <li>40 HORAS</li>
                                <li>60 HORAS</li>
                                <li>40 HORAS</li>
                                <li>40 HORAS</li>
                                <li>40 HORAS</li>
                                <li>40 HORAS</li>
                                <li>60 HORAS</li>
                            </ul>
                        </div>
                    </b-col>
                </b-row>
            </b-container>
            <div class="main-first__wrapper-img">
                <img src="Icone1.png" alt="">
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .col {
         @media(max-width: 930px) {
            display: flex;
            justify-content: center;
        }
    }

    .main-first {
        width: 90%;
        background-color: lightgray;
        position: relative;
        overflow: hidden;
        margin-bottom: 40px;
        
        @media(max-width: 930px) {
            width: 100%;
        }

        &__wrapper {
            padding: 20px 50px;

            @media(max-width: 930px) {
                padding: 10px;
            }
        }

        &__title {
            @media(max-width: 930px) {
                display: flex;
                justify-content: center;
            }
            h1 {
                font-weight: bolder;

                @media(max-width: 930px) {
                      font-size: 1.8rem;
                }
            }
        }

        &__subjects, &__hours {
            h4 {
                font-weight: bolder;

                @media(max-width: 930px) {
                    font-size: 1.2rem;
                }
            }
        }

        &__subjects {
            ul {
                padding-left: 5px;

                li {
                    @media(max-width: 930px) {
                      font-size: 0.8rem;
                    }
                }
            }
        }

        &__hours {
            ul {
                list-style: none;
                padding-left: 10px;

                li {
                    @media(max-width: 930px) {
                      padding-top: 5px;
                      font-size: 0.8rem;
                    }
                }
            }
        }

        &__wrapper-img {
            position: absolute;
            right: 0;
            bottom: 0;
            top: -15px;
            width: 200px;

            img {
                width: 100%;
                height: 100%;
            }

            @media(min-width: 1600px) {
                right: 10%;
                bottom: 0;
                top: -15px;
            }
            @media(max-width: 930px) {
                display: none;
            }
        }
    }
</style>