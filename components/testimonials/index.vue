<template>
    <b-container class="main-testimonials">
        <div class="main-testimonials__title">
            <h3>Depoimentos</h3>
        </div>

    <VueSlickCarousel :settings="settings">    
                <div class="main-testimonials__box" v-for="(test, index) in testimonials" :key="index">
                    <div class="main-testimonials__wrapper-infos">
                        <div class="main-testimonials__wrapper-img">
                            <img :src="test.imgURL" alt="">
                        </div>
                            <div class="main-testimonials__wrapper-name">
                                <h5> {{ test.nameStudent }} </h5>
                                <small> {{ test.course }} </small>
                            </div>
                    </div>
                    <div class="main-testimonials__text">
                        <p> {{ test.text }} </p>
                    </div>
                </div>
    </VueSlickCarousel>
    </b-container>
</template>

<script>
import VueSlickCarousel from 'vue-slick-carousel'
import 'vue-slick-carousel/dist/vue-slick-carousel.css'
import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

export default {
    name: 'MyComponent',
    components: { VueSlickCarousel },

    data() {
        return {
            testimonials: [
                {
                    nameStudent: 'Davi Oliveira',
                    course: 'Enfermagem',
                    text: 'A experiência que tive em relação ao curso foi bastante positiva, fico felis em ver o quanto os professores do técnico são qualificados e o quanto as mesmas se empenham para passar o máximo de conhecimento, eu não entrei com nenhuma ideia formada na cabeça de "o curso deve ser do jeito x", mas posso dizer que me sentir bastante satisfeito com tudo que aprendi, e com certeza recomendaria o curso para outras pessoas, sem pensar duas vezes!!',
                    imgURL: "/juliete.png"
                },
                {
                    nameStudent: 'Stefany Abreu',
                    course: 'Enfermagem',
                    text: 'Minha experiência foi algo bem interessante e cansativo ao mesmo tempo por ter muitas coisas para aprender. Além de várias aulas teóricas sobre o corpo humano, aprendi muito sobre a empatia e a humanização, o que foi algo muito importante tanto na Enfermagem, como no dia a dia. O curso foi sim o que eu esperava, pois aprendi bastante sobre os cuidados nos pacientes, doenças e etc, algo que estava nas minhas expectativas. E com certeza recomendaria para as pessoas, é um ótimo curso, principalmente para quem gosta da matéria de biologia.',
                    imgURL: "/juliete.png"
                },
                {
                    nameStudent: 'Erick de Lima',
                    course: 'Informática',
                    text: 'A minha experiência com o curso foi muito boa, conseguir evoluir bastante durante todo esse tempo, infelizmente tivemos 2 anos apáticos por conta da pandemia, porém aprendi bastante, tudo que foi passado, cheguei sem nenhuma expectativa mas gostei bastante e com tempo aprendi muito, e com certeza recomendo o curso para amigos que tiverem interesse no curso e mas disciplinas oferecidas por ele.',
                    imgURL: "/juliete.png"
                },
                {
                    nameStudent: 'Isley de Assis',
                    course: 'Informática',
                    text: 'O curso mudou minha vida, pelo fato de quando entrei no Onélio Porto, eu não tinha noção do que eu queria para a minha carreira e o curso abriu meus olhos diante do desenvolvimento web e hoje não me vejo fazendo outra coisa, certamente achei minha paixão, e o curso foi bem mais do que eu esperava, pelo fato da carga do conhecimento absurda adquirida diante esse tempo como aluno e com certeza eu recomendaria para as pessoas, o curso é impecável os profissionais de ensino te dão uma base absurda e você se dedicar certamente irá adorar programação.',
                    imgURL: "/juliete.png"
                },
                 {
                    nameStudent: 'Samuel Mangeth',
                    course: 'Contabilidade',
                    text: 'Foi uma experiência muito boa, dentro do curso técnico nós vimos a importância dela no meio empresarial, porém o curso não era muito do que eu esperava, pois eu pensava que iria ser um pouco diferentes, os conteúdos são bem mais profundos, e didáticos, e com certeza eu indico para meus amigos e conhecidos, o curso técnico, seja qual for, nós trás muitos benefícios. E é um aprendizado além da base comum que você leva para a vida toda, abre totalmente as portas.',
                    imgURL: "/juliete.png"
                },
                 {
                    nameStudent: 'Marcelo Macedo',
                    course: 'Finanças ',
                    text: ' curso técnico de finanças foi bastante proveitoso, as experiências no campo de estágio na empresa leva nos técnicos ensinamentos para a vida toda. O setor no qual concluir o meu estágio no o Departamento Pessoal, e conseguir ter aprendizados com diversas situações de funcionários da empresa e indico para todos os estudantes que vierem do ensino médio, a busca por técnico em finanças é bastante grande, pois tem uma forte aceitação do mercado de trabalho. Aprendemos durante o curso a ter controle da vida financeira pessoal, e isso contribui bastante porque saímos do ensino médio com um pensamento de organização do nosso dinheiro que receberemos no mercado de trabalho.',
                    imgURL: "/juliete.png"
                },
           ],
           settings: [
               {
                    dots: false,
                    arrows: true,
                    slidesToShow: 3,
                    autoplay: true,
                    autoplaySpeed: 2000,
                }
           ]
        }
    }
}
</script>

<style scoped>
.main-testimonials {
    margin-bottom: 50px;
}

.main-testimonials__box {
    border: 2px solid #146400;
    padding: 20px;
    max-width: 510px;
    margin-bottom: 40px;
}

.main-testimonials__wrapper-img {
    width: 59px;
    height: 54px;
}

.main-testimonials__wrapper-img img{
    width: 100%;
    height: 100%;
}

.main-testimonials__title {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 70px;
}

.main-testimonials__title h3 {
    position: relative;
    font-style: normal;
    font-weight: normal;
    font-size: 30px;
    line-height: 45px;
    color: #000000;
    text-transform: uppercase;
}

.main-testimonials__title h3::after {
    position: absolute;
    content: '';
    bottom: -10%;
    left: 25%;
    width: 100px;
    height: 4px;
    background-color: #22A800;
}

.main-testimonials__wrapper-infos {
    display: flex;
    margin-bottom: 10px;
}

.main-testimonials__wrapper-name {
    display: flex;
    flex-direction: column;
    margin-left: 20px; 
}
.main-testimonials__wrapper-name h5{
    margin-bottom: 10px; 
}

</style>