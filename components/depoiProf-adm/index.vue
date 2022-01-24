<template>
    <div class="depoimento">
        <div class="container">
            <div class="img">
                <img src="../../static/Mentor do Curso.png" alt="">
            </div>
            <div class="apresentacao">
                <h2>Nome do professor</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus at risus aliquam, dignissim tellus a, mattis augue. Fusce bibendum tristique varius. Vivamus eu felis nisi. Sed vitae lectus eu turpis lobortis eleifend vitae at magna. Aenean vehicula massa imperdiet interdum pharetra. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Ut mollis hendrerit mauris at efficitur. Duis tortor leo, consequat non ligula at, sollicitudin sagittis nulla. Aliquam diam massa, mollis ut laoreet non, accumsan eget nunc. Cras ut dictum neque, nec suscipit sapien. Nullam et eros quis mauris interdum accumsan aliquet eu ex.</p>
            </div>
            
        </div>
        
    </div>
</template>

<style scoped lang="scss">
    .depoimento {
        width: 100%;
        background: #95451D;
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