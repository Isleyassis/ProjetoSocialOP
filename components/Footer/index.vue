<template>
    <div class="footer">
        <div class="container">
            <nuxt-link to="/">HOME</nuxt-link>
            <nuxt-link to="administração">ADMINISTRAÇÃO</nuxt-link>
            <nuxt-link to="enfermagem">ENFERMAGEM</nuxt-link>
            <nuxt-link to="finanças">FINANÇAS</nuxt-link>
            <nuxt-link to="desenvolvimento">DESENVOLVIMENTO DE SISTEMAS</nuxt-link>
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