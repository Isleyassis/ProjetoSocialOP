<template>
    <div class="main-second">
        <div class="main-second__wrapper">
            <b-container>
            <div class="main-second__title">
                <h1> 2º Ano </h1>
            </div>
            
            <b-row>
                <b-col>
                    <div class="main-second__subjects">
                        <h4>Disciplinas:</h4>
                        <ul>
                            <li>Informática Basica</li>
                            <li>Informática Basica</li>
                            <li>Informática Basica</li>
                            <li>Informática Basica</li>
                            <li>Informática Basica</li>
                            <li>Informática Basica</li>
                            <li>Informática Basica</li>
                            <li>Informática Basica</li>
                            <li>Informática Basica</li>
                            <li>Informática Basica</li>
                            <li>Informática Basica</li>
                            <li>Informática Basica</li>
                            <li>Informática Basica</li>
                        </ul>
                    </div>
                </b-col>
                <b-col>
                    <div class="main-second__hours">
                        <h4>Horas:</h4>
                        <ul>
                            <li>100 HORAS</li>
                            <li>100 HORAS</li>
                            <li>100 HORAS</li>
                            <li>100 HORAS</li>
                            <li>100 HORAS</li>
                            <li>100 HORAS</li>
                            <li>100 HORAS</li>
                            <li>100 HORAS</li>
                            <li>100 HORAS</li>
                            <li>100 HORAS</li>
                            <li>100 HORAS</li>
                            <li>100 HORAS</li>
                            <li>100 HORAS</li>
                        </ul>
                    </div>
                </b-col>
            </b-row>
            </b-container>
            <div class="main-second__wrapper-img">
                <img src="icone2.png" alt="">
            </div>
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
            left: 0;
            bottom: 0;
            top: 15px;
            width: 200px;

            img {
                width: 100%;
                height: 100%;
            }

            @media(min-width: 1600px) {
                left: 10%;
                bottom: 0;
                top: 15px;
            }
            @media(max-width: 930px) {
                display: none;
            }
        }
    }
</style>