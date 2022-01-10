<template>
    <b-container class="main-testimonials">
        <div class="main-testimonials__title">
            <h3>Depoimentos</h3>
        </div>

        <b-row cols="2">   
            <b-col v-for="(test, index) in testimonials" :key="index">
                <div class="main-testimonials__box">
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
            </b-col>
        </b-row>
    </b-container>
</template>

<script>
export default {
    data() {
        return {
            testimonials: [
                {
                    nameStudent: 'Isley Barbosa de Assis',
                    course: 'informática',
                    text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris ut ipsum gravida, condimentum nisl non, maximus risus.',
                    imgURL: "/juliete.png"
                },
                {
                    nameStudent: 'iago Rafael',
                    course: 'informática',
                    text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris ut ipsum gravida, condimentum nisl non, maximus risus.',
                    imgURL: "/juliete.png"
                },
                {
                    nameStudent: 'Edinardo Filho',
                    course: 'informática',
                    text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris ut ipsum gravida, condimentum nisl non, maximus risus.',
                    imgURL: "/juliete.png"
                },
                {
                    nameStudent: 'Kayque Viana',
                    course: 'informática',
                    text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris ut ipsum gravida, condimentum nisl non, maximus risus.',
                    imgURL: "/juliete.png"
                },
                 {
                    nameStudent: 'Natanael Lima',
                    course: 'informática',
                    text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris ut ipsum gravida, condimentum nisl non, maximus risus.',
                    imgURL: "/juliete.png"
                },
                 {
                    nameStudent: 'Ezequias Oliveira',
                    course: 'informática',
                    text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris ut ipsum gravida, condimentum nisl non, maximus risus.',
                    imgURL: "/juliete.png"
                },
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