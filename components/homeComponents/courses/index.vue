<template>
    <div class="container">
        <div class="title-courses">
            <h3>SAIBA MAIS SOBRE OS CURSOS</h3>
            <div class="line"></div>
        </div>
        <div class="cards-container">
            <div class="box-card">
                <div class="card">
                    <img src="/administracao.jpg" alt="">
                </div>
                <div class="course-name">
                    <p>Administração</p>
                </div>
            </div>
            <div class="box-card">
                <div class="card">
                    <img src="/enfermagem.jpg" alt="">
                </div>
                <div class="course-name">
                    <p>Enfermagem</p>
                </div>
            </div>
            <div class="box-card">
                <div class="card">
                    <img src="/financas.jpg" alt="">
                </div>
                <div class="course-name">
                    <p>Finanças</p>
                </div>
            </div>
            <div class="box-card">
                <div class="card">
                    <img src="/desenSistema.jpg" alt="">
                </div>
                <div class="course-name">
                    <p>Desenvol. de Sistemas</p>
                </div>
            </div>
        </div>
        </div>
        
</template>

<style scoped lang="scss">
    .cards-container {
        width: 100%;

        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        align-items: center;
        justify-content: space-between;

        @media (max-width: 530px) {
            justify-content: center;
        }

        .box-card {
            // width: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;

            margin-bottom: 2rem;

            .course-name {
                display: flex;
                justify-content: center;
                align-items: center;
                color: #fff;
                background: #146400;
                padding: .7rem 0;

                p {
                    margin: 0;
                }
            }
        }

        .card, .course-name {
            width: 15rem;
        }
        .card {
            margin-bottom: 1.5rem;
        }

        
    }

    .title-courses {
        text-align: center;

        display: flex;
        justify-content: center;
        flex-direction: column;
        align-items: center;

        margin-bottom: 2rem;

        .line {
            width: 150px;
            height: 5px;
            background: #146400;
        }
    }
</style>