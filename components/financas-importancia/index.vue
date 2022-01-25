<template>
<div class="main_container">
    <b-container >
        <b-row class="main_container___row">
            <b-col lg="9">
                <div class="main_container___text">
                <h1>QUAL A IMPORTÂNCIA DO CURSO DE FINANÇAS?</h1>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
                    Phasellus vel tincidunt ligula. Morbi posuere ac neque ac viverra. 
                    Nunc a mattis risus, eu accumsan quam. Phasellus id posuere nulla. 
                    Curabitur volutpat magna eget eros eleifend aliquam. 
                    Quisque vitae eros in ante cursus tincidunt in et metus. 
                    Etiam feugiat rutrum purus nec lobortis. 
                    Aliquam erat volutpat. 
                    Cras nec urna libero. 
                    Etiam ut tortor ut mi congue tristique.
                    Ut tempor tellus nunc, at commodo massa varius sed. 
                    Duis id egestas purus. 
                    Duis pulvinar, mauris quis accumsan varius, eros lacus volutpat lacus, ac facilisis urna arcu in lectus. 
                    Donec a iaculis nibh. Ut ullamcorper id purus quis condimentum. 
                    Praesent scelerisque dolor elit. 
                    Donec posuere pretium blandit. 
                    Donec faucibus ante in tortor dignissim cursus. 
                    Sed felis ante, tristique ut ligula ac, vestibulum consectetur est.
                    Sed nisi enim, hendrerit eget ligula vel, lobortis pharetra leo. 
                    Nullam vestibulum libero lacus, ac consequat tellus laoreet ut. 
                    Sed ornare, dolor id luctus sagittis, ex.
                </p>
                </div>
            </b-col>
            <b-col lg="3">
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
    height: 545px;
    width: 545px;
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