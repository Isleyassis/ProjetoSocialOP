<template>
    <footer class="main-footer">
        <div class="main-footer__title">
            <h2>Informática 2019 - 2021</h2>
        </div>
        <div class="main-footer__wrapper-img">
            <img src="Foto Rodapé.jpeg" alt="">
        </div>
        <div class="main-footer__background"></div>
        <div class="main-footer__nameproject">
            <p>
                NOME DO PROJETO - 2021
            </p>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
    .main-footer__title {
        display: flex;
        justify-content: center;
        align-items: center;
        margin-bottom: 60px;
    }

    .main-footer__wrapper-img {
        position: absolute;
        width: 60%;
        height: 600px;
        top: -30px;
    }

    .main-footer__background {
        background-color: darkgreen;
        height: 700px;
        position: relative;
    }

    .main-footer__nameproject {
        background-color: lightgreen;
        display: flex;
        justify-content: flex-end;
        padding: 5px 10%;

        p {
            margin: 0;
            font-weight: bolder;
            color: white;
        }
    }
</style>