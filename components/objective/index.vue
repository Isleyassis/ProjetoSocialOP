<template>
    <div class="main-objective">
        <div class="main-objective__title">
            <h3> SAIBA MAIS DO NOME DO NOSSO PROJETO </h3>
        </div>
        <div class="main-objective__text">
            <div class="main-objective__wrapper-img">
                <img src="Foto Objetivo.jpeg" alt="">
            </div>
            <div class="main-objective__wrapper-text">           
                <h4>NOSSO OBJETIVO</h4>
                <p> Lorem ipsum dolor sit amet, consectetur adipisicing elit. Laudantium, ducimus ipsum. Voluptatem enim blanditiis, corporis quo architecto consequuntur culpa dolorem dolorum fugiat quidem possimus illum doloribus incidunt rem. Blanditiis, molestias. Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eos qui fugiat provident aliquam natus ratione magnam, aut, repellat ipsam assumenda distinctio corporis doloremque! Eligendi, neque est. Soluta eligendi ipsa suscipit. Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate atque, pariatur recusandae adipisci et perferendis possimus, veritatis aliquam nisi nostrum, vel omnis assumenda minus quam. Eligendi excepturi aspernatur beatae at. </p>
            </div>
        </div>
    </div>
</template>
<style scoped lang="scss">
    .main-objective {
        margin-bottom: 40px;
    }

    .main-objective__title{
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        margin-bottom: 150px;
    }

    .main-objective__title h3{
        font-size: 35px;
        line-height: 52px;
        text-align: center;
        position: relative;

        @media(max-width: 992px) {
            & {
                font-size: 24px;
            }
        }
    }

    .main-objective__title h3::after {
        position: absolute;
        content: '';
        bottom: -10%;
        left: 32%;
        width: 300px;
        height: 4px;
        background-color: #22A800;

    @media (max-width: 992px) {
         & {
            bottom: 5%;
            left: 32%;
        }
    }
    }

    .main-objective__text {
        display: flex;
        justify-content: flex-end;
        position: relative;

        .main-objective__wrapper-img {
            position: absolute;
            left: 8%;
            top: -15%;
            width: 500px;
            height: 300px;

            img {
                width: 100%;
                height: 100%;
            }
        }

        .main-objective__wrapper-text {
            width: 60%;
            background-color: lightgray;
            padding: 20px 100px;

            h4 {
                color: lightgreen;
            }

            p {
                text-align: justify;
            }
        }
    }
</style>