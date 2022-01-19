<template>
    <div class="main-first">
        <div class="main-first__wrapper">
            <div class="main-first__title">
                <h1> 1º Ano </h1>
            </div>

            <b-row>
                <b-col>
                    <div class="main-first__subjects">
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
                    <div class="main-first__hours">
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
            <div class="main-first__wrapper-img">
                <img src="Icone 1 Ano.png" alt="">
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .main-first {
        width: 90%;
        background-color: lightgray;
        position: relative;
        overflow: hidden;
        margin-bottom: 40px;

        &__wrapper {
            padding: 20px 50px;
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