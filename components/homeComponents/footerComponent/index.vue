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
            <div class="main-footer__wrappertext">
                <p>
                    INFORONELIO - 2021
                </p>
            </div>
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
        

        @media(min-width: 1551px) {
            width: 850px;
            height: 450px;
            top: -65px;
            left: 28%;
        }

        @media(max-width: 1550px) {
            width: 850px;
            height: 450px;
            top: -65px;
            left: 18%;
        }

        @media(max-width: 1050px) {
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

        @media (max-width: 1050px) {
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

        .main-footer__wrappertext {
            max-width: 1140px;
            display: flex;
            justify-content: flex-end;
            align-items: flex-end;
            margin: 0 auto;

            p {
                margin: 0;
                font-weight: bolder;
                color: white;
            }
        }
    }
</style>