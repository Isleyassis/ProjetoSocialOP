<template>
    <div class="main-second">
        <div class="main-second__wrapper">
             <div class="main-second__wrapper-img">
                <img src="icone2 - finanças.png" alt="">
            </div>
            <b-container>
            <div class="main-second__title">
                <h1> 2º Ano </h1>
            </div>
            
            <b-row>
                <b-col cols="8" lg="6">
                    <div class="main-second__subjects">
                        <h4>Disciplinas:</h4>
                        <ul>
                            <li>Contabilidade de Custos</li>
                            <li>Matemática Financeira</li>
                            <li>Legislação Empresarial e Tributária</li>
                            <li>Administração do Capital de Giro</li>
                            <li>Mercado de Capitais</li>
                            <li>Informática Aplicada à Gestão Financeira</li>
                            <li>Administração Financeira</li>
                            <li>Contabilidade Gerencial</li>
                        </ul>
                    </div>
                </b-col>
                <b-col cols="4" lg="6">
                    <div class="main-second__hours">
                        <h4>Horas:</h4>
                        <ul>
                            <li>40 HORAS</li>
                            <li>60 HORAS</li>
                            <li>60 HORAS</li>
                            <li>40 HORAS</li>
                            <li>40 HORAS</li>
                            <li>60 HORAS</li>
                            <li>60 HORAS</li>
                            <li>40 HORAS</li>
                        </ul>
                    </div>
                </b-col>
            </b-row>
            </b-container>
           
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .col {
        display: flex;
        justify-content: flex-end;

         @media(max-width: 930px) {
             justify-content: center;
        }
    }
    .main-second {   
        margin-bottom: 40px;
        display: flex;
        justify-content: flex-end;
        align-items: flex-end;

        &__wrapper {
            padding: 20px 50px; 
            width: 90%;
            background-color: lightgray;
            position: relative;

            @media(max-width: 930px) {
                padding: 10px;
                width: 100%;
            }
        }

        &__title {
            display: flex;
            justify-content: center;
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
                padding-left: 140px;
            }
            @media(min-width: 1200px){
                padding-left: 240px;
            }
             
        }

        // &__subjects{
           
        // }


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
                      padding-top: 7px;
                      font-size: 0.8rem;
                    }
                }
            }
        }

        &__wrapper-img {
            position: absolute;
            left: 0;
            bottom: 0;
            top: 50px;
            max-width: 20%;
            max-height: 300px;

            img {
                width: 100%;
                height: 100%;
            }

            @media(min-width: 1600px) {
                left: 10%;
                bottom: 0;
                top: 50px;
            }
            @media(max-width: 930px) {
                display: none;
            }
        }
    }
</style>