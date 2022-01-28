<template>
    <div class="depoimento">
        <div class="container">
            <div class="img">
            </div>
            <div class="apresentacao">
                <h2><b>Profª: Sandra Nogueira</b></h2>
                <div class="d-flex curriculo">
                    <small>Bacharel em Ciências Contábeis e possui 2 especializações, uma em Gestão Pública pela UNILAB e outra em Auditoria e Controladoria (UNIC).</small>
                    <small>Bacharel em Direito (sétimo semestre) e possui conhecimentos em francês</small>
                </div>
                <p>O curso de finanças é um curso que visualiza muito de forma bem ampla a questão do fluxo de caixa, abrange a área contabél de forma geral, a diferença entre finanças e contabilidade é que a finanças vê a parte de um todo de Contabilidade(é como se fosse um grande guarda-roupa) e finanças vê parte desse guarda-roupa metaforicamente falando, requisitos para finanças é basicamente fluxo de caixa, entrada e saída de dinheiro, o aluno de finanças tem que gostar muito de organização e matemática. Finanças vê a parte de movimentação do dinheiro da empresa. O mercado de trabalho, tem muita demanda e muita oferta e visualiza essa parte de capitais. E recomendo sim o curso para os alunos, pois cada final de fechamento de curso, os meninos migram para ciências contábeis, e sempre temos bons resultados como por exemplo a aluna Yara Joyce, aluna aprovada para PM(feminina) está concluindo Ciências Contábeis, neste semestre (2022.1) Ela foi aluna da turma de Finanças(2013-2015)</p>
            </div>
            
        </div>
        
    </div>
</template>

<style scoped lang="scss">
    .depoimento {
        width: 100%;
        background: #9D9932;
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