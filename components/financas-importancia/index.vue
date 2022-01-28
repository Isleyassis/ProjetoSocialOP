<template>
<div class="main_container">
    <b-container >
        <b-row class="main_container___row">
            <b-col lg="8">
                <div class="main_container___text">
                <h1>QUAL A IMPORTÂNCIA DO CURSO DE FINANÇAS?</h1>
                <p>
                    Ele promove profissionais que compreendem as rotinas financeiras de negócios, as fontes de financiamento e o custo médio ponderado de capital. Esse conhecimento adquirido é utilizado como mecanismo de gestão dos recursos financeiros, visando proporcionar lucro.
                </p>
                </div>
            </b-col>
            <b-col lg="4">
                <figure class="main_container___img">
                    <img src="financas icone.png" alt="">
                </figure>
            </b-col>
        </b-row>
    </b-container>
</div>
</template>
<style scoped lang="scss">

.main_container{
    padding-top: 30px;
background-color: rgb(198, 214, 51);

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

        
    @media(max-width: 992px) {
        & {
            font-size: 14px;
        }
    }
    }

}

.main_container___img{
    height: 500px;
    width: 500px;
    position: relative;
    padding-right: 100px;
    
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