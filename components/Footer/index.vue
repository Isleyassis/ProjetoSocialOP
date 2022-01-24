<template>
    <div class="footer">
        <div class="container">
            <nuxt-link to="/pages/index.vue">HOME</nuxt-link>
            <nuxt-link to="/pages/administração.vue">ADMINISTRAÇÃO</nuxt-link>
            <nuxt-link to="/pages/enfermagem.vue">ENFERMAGEM</nuxt-link>
            <nuxt-link to="/pages/finanças.vue">FINANÇAS</nuxt-link>
            <nuxt-link to="/pages/desenvolvimento.vue">DESENVOLVIMENTO DE SISTEMAS</nuxt-link>
        </div>
        <div class="main-footer__nameproject">
            <div class="main-footer__wrappertext">
                <p>
                    INFORONELIO - 2021
                </p>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
    .footer {
        .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;

            padding: 1rem 0;

            @media (max-width: 570px) {
                flex-direction: column;
            }
        }
    }

    .main-footer__nameproject {
        background-color: lightgreen;

        .main-footer__wrappertext {
            max-width: 1140px;
            display: flex;
            justify-content: flex-end;
            align-items: flex-end;
            margin: 0 auto;

            p {
                margin: 0;
                font-weight: bolder;
                color: white;
            }
        }
    }
    
</style>