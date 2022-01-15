<template>
    <header class="main-header">
        <b-container>
            <b-navbar class="main-header__nav">
                <div class="main-header__nav-wrapper">
                    <a href="#">HOME</a>
                    <b-dropdown class="main-header__nav-dropdown" id="dropdown-1" text="Cursos" >
                        <b-dropdown-item>Desenvolvimento</b-dropdown-item>
                        <b-dropdown-item>Enfermagem</b-dropdown-item>
                        <b-dropdown-item>Administração</b-dropdown-item>
                        <b-dropdown-item>Contabilidade</b-dropdown-item>
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
            }
        }

        &__text {
            color: white;

            h1 {
                font-size: 35px;
            }
        }
    }


    #dropdown-1__BV_toggle_ {
                    background-color: transparent; 
                    padding: 0;
                    border: none;
                    margin-left: 10px;
                }
</style>