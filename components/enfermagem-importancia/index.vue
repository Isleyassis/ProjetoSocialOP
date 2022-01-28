<template>
<div class="main_container">
    <b-container >
        <b-row class="main_container___row">
            <b-col lg="9">
                <div class="main_container___text">
                <h1>QUAL A IMPORTÂNCIA DO CURSO DE ENFERMAGEM?</h1>
                <p>
                    O Técnico em Enfermagem possui diversas oportunidades de trabalho: Sem dúvida, um dos motivos que podem levar diversas pessoas a fazer um curso de técnico de enfermagem é a ampla variedade de segmentos e oportunidades no mercado de trabalho. Isso porque, cada dia mais tem crescido a demanda por esses profissionais.
                </p>
                </div>
            </b-col>
            <b-col lg="3">
                <figure class="main_container___img">
                    <img src="../../static/soro.png" alt="">
                </figure>
            </b-col>
        </b-row>
    </b-container>
</div>
</template>
<style scoped lang="scss">

.main_container{
    padding-top: 30px;
background-color: rgb(121, 184, 189);

margin-bottom: 7rem;
}

.main_container___text{
    h1{
        color: white;
        
    @media(max-width: 992px) {
        & {
            font-size: 24px;
        }
    }
    }
    p{
        font-size: 18px;
        color: black;

        
    @media(max-width: 992px) {
        & {
            font-size: 14px;
        }
    }
    }

}

.main_container___img{
    height: 445px;
    width: 445px;
    position: relative;
    
    
    @media(max-width: 992px) {
        & {
            height: 420px;
            width: 420px;
        }
    }
    img{
        height: 100%;
        width: 100%;
    }
}
</style>