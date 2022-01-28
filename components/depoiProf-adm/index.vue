<template>
    <div class="depoimento">
        <div class="container">
            
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