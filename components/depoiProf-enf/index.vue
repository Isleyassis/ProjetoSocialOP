<template>
    <div class="depoimento">
        <div class="container">
            <div class="img">
                <img src="../../static/Raquel.jpg" alt="">
            </div>
            <div class="apresentacao">
                <h2><b>Profª: Raquel Macedo</b></h2>
                <div class="d-flex curriculo">
                    <small>Graduada e Licenciada em Enfermagem com especialização em Sáude da Família e Docência Profissional.</small>
                </div>
                <p>No curso de enfermagem em regime integral, o aluno além de aprender sobre procedimentos técnicos próprios da assistência prestada por técnicos em enfermagem, fortalece a importância da humanização e da responsabilidade social enquanto cidadão. É um curso que tem grande necessidade no mercado de trabalho, sendo de fácil contratação, contribuindo para a independência financeira, transformações de vida, incentivo e possibilidades para capacitações maiores, além de ter grande relevância na prática social devido a construção humana e essencialmente profissional, super recomendo, por conta da grande contribuição na formação humana considerando a visão e percepção holística do outro. Além da questão política que requer muita luta, resiliência e estudo para valorização da profissão e do ser cidadão!</p>
            </div>
            
        </div>
        
    </div>
</template>

<style scoped lang="scss">
    .depoimento {
        width: 100%;
        background: #3C7392;
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