<template>
    <div class="depoimento">
        <div class="container">
            <div class="img">
                <img src="../../static/Nildete.jpg" alt="">
            </div>
            <div class="apresentacao">
                <h2><b>Profª Nildete Ramos</b></h2>
                <div class="d-flex curriculo">
                    <small>Graduada em Tecnologia em Informática na Educação.</small>
                    <small>Graduada em Pedagogia</small>
                    <small>Com especialização em aperfeiçoamento em docência na Educação Profissional e Especialista em Mídias na Educação.</small>
                </div>
                <p>Ao ingressar no curso técnico de informática ou desenvolvimento de sistema o aluno terá oportunidade de conhecer e trabalhar com as mais variáveis áreas de informática... Terá oportunidade de conhecer e aprender a fazer programas, jogos, página web, fazer manutenção de computadores, aprender a fazer banco de dados, aplicativos para mobile entre outros. E para formar profissionais responsáveis, proativos, determinados, autônomos e colaboradores. Os alunos do curso aprenderão a trabalhar com as diversas linguagens de programação, visando desenvolver projetos de criação e manutenção de websites</p>
            </div>
            
        </div>
        
    </div>
</template>

<style scoped lang="scss">
    .depoimento {
        width: 100%;
        background: #EC047C;
        color: #fff;

        padding: 2rem 0;

        .container {
            display: flex;
            align-items: center;
            flex-direction: row;

            @media (max-width: 820px) {
                flex-direction: column;
            }
            .img {
                width: 100%;
                text-align: center;
                img {
                    width: 400px;
                    margin-right: 2rem;

                    @media (max-width: 550px) {
                        width: 70%;
                    }
                }
            }
            
            .curriculo {
                flex-direction: column;
                margin-bottom: 1.5rem;
            }

            .apresentacao {
                height: 100%;
                display: flex;
                flex-direction: column;
                justify-content: center;

                p {
                    font-size: 15.7px;
                    @media (max-width: 550px) {
                        font-size: 12.3px;
                    }
                }
                
                @media (max-width: 820px) {
                    margin-top: 2rem;
                }
            }
        }
    }
</style>