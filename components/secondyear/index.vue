<template>
    <div class="main-second">
        <div class="main-second__wrapper">
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
                        </ul>
                    </div>
                </b-col>
            </b-row>
            <div class="main-second__wrapper-img">
                <img src="Icone 1 Ano.png" alt="">
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
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
            overflow: hidden;
        }

        &__title {
            h1 {
                font-weight: bolder;
            }
        }

        &__subjects, &__hours {
            h4 {
                font-weight: bolder;
            }
        }

        &__subjects {
            ul {
                padding-left: 5px;
            }
        }

        &__hours {
            ul {
                list-style: none;
                padding-left: 10px;
            }
        }

        &__wrapper-img {
            position: absolute;
            right: 0;
            bottom: 0;
            width: 70%;
            display: none;

            img {
                width: 100%;
                height: 100%;
            }
        }
    }
</style>