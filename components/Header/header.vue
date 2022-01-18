<template>
    <div class="bga">
        <header class="container">
            <p>HOME</p>
            <select>
                <option value="#">CURSOS</option>
                <option value="administracao">Administração</option>
                <option value="enfermagem">Enfermagem</option>
                <option value="Financas">Finanças</option>
                <option value="DS">Desenvol. Sistemas</option>
            </select>
        </header>

        <div class="container hero">
            <h3>Projeto Social</h3>
            <h1>TITULO DO PROJETO</h1>
            <h3>EEEP PROFESSOR ONÉLIO PORTO - INFORMÁTICA 3 2021</h3>
        </div>
    </div>
</template>

<style scoped>
    .bga {
        background: #c4c4c4;
        color: #fff;
        background-image: url(../../static/Banner.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        background-position-y: -25rem;

        padding-bottom: 10rem;
    }

    header {
        display: flex;
        align-items: center;
        justify-content: flex-end;
        padding: 2.6rem 0;
    }

    select {
        margin-left: 1rem;
        font-size: 25px;
        background: transparent;
        border: 0;
        width: 130px;
        color: #fff
    }

    p {
        margin: 0;
        font-size: 25px;
    }

    .hero {
        height: 100%;
        display: flex;
        flex-direction: column;
        align-items: flex-start;

        margin-top: 2rem;
    }

    h3 {
        font-size: 25px;
        line-height: 45px;
    }
    
    h1 {
        font-size: 110px;
        line-height: 125px;
        width: 70%;
    }
</style>