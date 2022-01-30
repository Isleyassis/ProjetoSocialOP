<template>
    <header class="main-header">
        <b-container>
            <b-navbar class="main-header__nav">
                <div class="main-header__nav-wrapper">
                    <nuxt-link to="/">HOME</nuxt-link>
                    <b-dropdown class="main-header__nav-dropdown" variant="link" no-caret>
                        <template #button-content>
                           <p class="main-header__cousers text">CURSOS</p>  <span class="sr-only">Search</span>
                        </template>
                        <b-dropdown-item class="text" href="desenvolvimento">Desenvolvimento</b-dropdown-item>
                        <b-dropdown-item class="text" href="enfermagem">Enfermagem</b-dropdown-item>
                        <b-dropdown-item class="text" href="administração">Administração</b-dropdown-item>
                        <b-dropdown-item class="text" href="finanças">Finanças</b-dropdown-item>
                    </b-dropdown>
                </div>
            </b-navbar>

            <div class="central">
                <div class="main-header__text">
                    <h1>Administração</h1>
                </div>    
            </div>
        </b-container>
    </header>    
</template>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Lora:wght@400&display=swap');
.main-header {
        background-image: url("../../static/adm-banner.jpg");
        background-position: bottom;
        background-repeat: no-repeat;
        background-size: cover;
        height: 80%;
        width: 100%;
        padding-bottom: 7rem;
        margin-bottom: 7rem;

        .container {
            height: 100%;
        }

        a, .text {
            font-size: 25px;
        }

        &__nav {
            display: flex;
            justify-content: flex-end;
            
            padding: 2rem 0;

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

        .central {
            height: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }


        &__text {
            color: white;


            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;

            h1 {
                font-size: 120px;
                font-family: 'Lora', serif;
                text-align: center;


                @media(max-width: 992px) {
                    & {
                        font-size: 70px;
                    }
                }
                 @media(max-width: 520px) {
                    & {
                        font-size: 40px;
                    }
                }
            }
        }
    }
</style>