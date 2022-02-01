<template>
<div class="main_container">
    <b-container >
        <b-row class="main_container___row">
            <b-col lg="8">
                <div class="main_container___text">
                <h1>QUAL A IMPORTÂNCIA DO CURSO DE ADMINISTRAÇÃO?</h1>
                <p>
                    Ao se formar Técnico em Administração, o profissional tem um bom entendimento de como diversas áreas de um negócio trabalham. É possível ter uma ideia clara das funções dos setores financeiro, de recursos humanos, comercial, logístico, administrativo, entre outros, e como eles se integram na rotina da companhia.
                </p>
                </div>
            </b-col>
            <b-col lg="4" class="main_wrapper-container">
                <figure class="main_container___img">
                    <img src="administracao icone.png" alt="">
                </figure>
            </b-col>
        </b-row>
    </b-container>
</div>
</template>
<style scoped lang="scss">

.main_container{
    padding-top: 30px;
    background-color: rgb(224, 147, 2);
    margin-bottom: 7rem;
    overflow: hidden;
    padding-bottom: 50px;
}

.main_container___text{
    h1{
        color: black;
        
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