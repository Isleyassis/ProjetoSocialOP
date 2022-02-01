<template>
<div class="main_container">
    <b-container >
        <b-row class="main_container___row">
            <b-col lg="7">
                <div class="main_container___text">
                <h1>QUAL A IMPORTÂNCIA DO CURSO DE DESENVOLVIMENTO DE SISTEMAS?</h1>
                <p>
                    O mercado de Software cria possibilidades de atuação em Instituições públicas, privadas e do terceiro setor, que demandem sistemas computacionais como indústria, bancos, comércio, hospitais. Além disso, o técnico em Desenvolvimento de Sistemas tem ótimas oportunidades em se tornar um empreendedor.
                </p>
                </div>
            </b-col>
            <b-col lg="5" class="main_wrapper-container">
                <figure class="main_container___img">
                    <img src="Icone Banner (1).png" alt="">
                </figure>
            </b-col>
        </b-row>
    </b-container>
</div>
</template>
<style scoped lang="scss">

.main_container{
    padding-top: 30px;
    background-color: rgb(73, 73, 73);
    margin-bottom: 7rem;
    overflow: hidden;
    padding-bottom: 40px;

    @media(max-width: 992px) {
        padding-bottom: 0px;
    }
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
        color: white;

        
    @media(max-width: 992px) {
        & {
            font-size: 14px;
        }
    }
    }

}

.main_wrapper-container {
    @media(max-width: 992px) {
        & {
            display: flex;
            justify-content: center;
        }
    }

.main_container___img{
    height: 100%;
    width: 100%;
    position: relative;
    
    @media(max-width: 992px) {
        & {
            max-height: 294px;
            max-width: 378px;
            margin: 0;
        }
    }
    @media(max-width: 400px) {
        & {
            height: 100%;
            width: 100%;
            padding-bottom: 50px;
        }
    }
    img{
        height: 100%;
        width: 100%;
    }
}}
</style>