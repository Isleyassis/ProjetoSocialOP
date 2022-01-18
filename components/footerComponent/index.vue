<template>
    <footer class="main-footer">
        <div class="main-footer__title">
            <h2>Informática 2019 - 2021</h2>
        </div>

        <div class="main-footer__background">
            <img src="background-hd.jpg" class="background-hd" alt="">
            <div class="main-footer__wrapper-img">
            <img src="Foto Rodapé.jpeg" alt="">
        </div>
        </div>
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
        margin-bottom: 160px;

        @media(max-width: 700px) {
            & {
                margin-bottom: 80px;
                font-size: 24px;
            }
        }
    }

    .main-footer__wrapper-img {
        position: absolute;
        width: 750px;
        height: 400px;
        top: -65px;
        left: 25%;

         @media(max-width: 1200px) {
            width: 700px;
            height: 450px;
            top: -65px;
            left: 18%;
        }

        @media(max-width: 992px) {
            width: 90%;
            height: 300px;
            top: -65px;
            left: 5%;
        }

        @media(max-width: 600px) {
            width: 90%;
            height: 200px;
            top: -65px;
            left: 5%;
        }


        img {
            width: 100%;
            height: 100%;
        }
    }

    .main-footer__background {
        height: 500px;
        position: relative;

        @media (max-width: 992px) {
            height: 350px;
        }

        @media (max-width: 600px) {
            height: 200px;
        }

        .background-hd {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
        }
    }

    .main-footer__nameproject {
        background-color: lightgreen;
        display: flex;
        justify-content: flex-end;
        padding: 10px 10%;

        p {
            margin: 0;
            font-weight: bolder;
            color: white;
        }
    }
</style>