<template>
    <div class="main-third">
        <b-container class="main-third__wrapper">
            <div class="main-third__title">
                <h1> 3º Ano </h1>
            </div>
            <div class="main-third__wrapper-img2">
                <img src="icone3 2.png" alt="">
            </div>
            <b-row>
                <b-col cols="8" lg="6">
                    <div class="main-third__subjects">
                        <h4>Disciplinas:</h4>
                        <ul>   
                            <li>Assistência ao Paciente Cirúrgico</li>
                            <li>Assistência ao Paciente Crítico </li>
                            <li>Laboratório de Práticas de Enfermage</li>
                            <li>Estágio Curricular I </li>
                            <li>Estágio Curricular II </li>
                        </ul>
                    </div>
                </b-col>
                <b-col cols="4" lg="6">
                    <div class="main-third__hours">
                        <h4>Horas:</h4>
                        <ul>
                            <li>40 HORAS</li>
                            <li>80 HORAS</li>
                            <li>40 HORAS</li>
                            <li>200 HORAS</li>
                            <li>400 HORAS</li>
                        </ul>
                    </div>
                </b-col>
            </b-row>
            <div class="main-third__wrapper-img1">
                <img src="icone3 1.png" alt="">
            </div>
           
        </b-container>
    </div>
</template>

<style lang="scss" scoped>
    .col {
        display: flex;
        justify-content: center;
    }
    .main-third {
        background-color: lightgray;
        position: relative;
        overflow: hidden;
        margin-bottom: 40px;

        &__wrapper {
            padding: 20px 50px;

            @media(max-width: 930px) {
                padding: 10px;
            }
        }

        &__title {
            display: flex;
            justify-content: center;
            align-items: center;

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
                @media(min-width: 1024px){
                padding-left: 70px;
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

        &__wrapper-img1 {
            position: absolute;
            left: 0;
            bottom: 0;
            top: 10px;

            img {
                width: 100%;
                height: 100%;
            }

            @media(min-width: 1600px) {
                left: 10%;
                bottom: 0;
                top: 10px;
            }
            @media(max-width: 930px) {
                display: none;
            }
        }
         &__wrapper-img2 {
            position: absolute;
            right: 0;
            bottom: 0;
            top: 10px;

            img {
                width: 100%;
                height: 100%;
            }
            
            @media(min-width: 1600px) {
                right: 10%;
                bottom: 0;
                top: 10px;
            }
            @media(max-width: 930px) {
                display: none;
            }
        }
    }
</style>