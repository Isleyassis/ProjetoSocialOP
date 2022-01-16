<template>
    <header class="main-header">
        <b-container>
            <b-navbar class="main-header__nav">
                <div class="main-header__nav-wrapper">
                    <a href="#">HOME</a>
                    <b-dropdown class="main-header__nav-dropdown" variant="link" no-caret>
                        <template #button-content>
                           <p class="main-header__cousers">CURSOS</p>  <span class="sr-only">Search</span>
                        </template>
                        <b-dropdown-item href="/">Desenvolvimento</b-dropdown-item>
                        <b-dropdown-item href="/">Enfermagem</b-dropdown-item>
                        <b-dropdown-item href="/">Administração</b-dropdown-item>
                        <b-dropdown-item href="/">Contabilidade</b-dropdown-item>
                    </b-dropdown>
                </div>
            </b-navbar>

            <div class="main-header__text"> 
                <h3>PROJETO SOCIAL</h3>
                <h1>TITULO DO <br> PROJETO</h1>
                <p>EEEP PROFESSOR ONÉLIO PORTO - INFORMÁTICA 3 2021</p>
            </div>
        </b-container>
    </header>    
</template>


<style lang="scss" scoped>
    .main-header {
        background-image: url("/Banner.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        height: 100vh;
        width: 100%;
        margin-bottom: 70px;

        &__nav {
            display: flex;
            justify-content: flex-end;

            .main-header__nav-wrapper {
                display: flex;
                align-items: center;

                a {
                    color: white;
                    text-decoration: none;
                }

                .main-header__nav-dropdown {
                    .main-header__cousers {
                        display: inline-block;
                        color: white;
                        margin: 0;

                        &::after {
                            display: inline-block;
                            margin-left: 0.255em;
                            vertical-align: 0.255em;
                            content: "";
                            border-top: 0.3em solid;
                            border-right: 0.3em solid transparent;
                            border-bottom: 0;
                            border-left: 0.3em solid transparent;
                        }
                    }
                }
            }
        }

        &__text {
            color: white;

            h1 {
                font-size: 120px;
                font-weight: bolder;


                @media(max-width: 992px) {
                    & {
                        font-size: 80px;
                    }
                }
                 @media(max-width: 450px) {
                    & {
                        font-size: 40px;
                    }
                }
            }
        }
    }
</style>