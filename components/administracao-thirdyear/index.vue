<template>
    <div class="main-third">
        <b-container class="main-third__wrapper">
            <div class="main-third__title">
                <h1> 3º Ano </h1>
            </div>

            <b-row>
                <b-col>
                    <div class="main-third__subjects">
                        <h4>Disciplinas:</h4>
                        <ul>
                            <li>Estratégia de Produção</li>
                            <li>Logística Empresarial</li>
                            <li>Gestão de Vendas</li>
                            <li>Responsabilidade Sócioambiental</li>
                            <li>Estágio Curricular</li>
                        </ul>
                    </div>
                </b-col>
                <b-col>
                    <div class="main-third__hours">
                        <h4>Horas:</h4>
                        <ul>
                            <li>40 HORAS</li>
                            <li>60 HORAS</li>
                            <li>40 HORAS</li>
                            <li>40 HORAS</li>
                            <li>300 HORAS</li>
                        </ul>
                    </div>
                </b-col>
            </b-row>
            <div class="main-third__wrapper-img">
                <img src="icone3 - administração.png" alt="">
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
                      font-size: 0.8rem;
                    }
                }
            }
        }

         &__wrapper-img {
            position: absolute;
            right: 0;
            bottom: 0;
            top: 10px;
            width: 15%;

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