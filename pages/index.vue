<template>
   <div>
     <Header />
     <localization />
     <courses />
     <testimonials />
     <objective />
     <authors />
     <footerComponent />
   </div>
</template>

<script>
import Header from '../components/homeComponents/Header/header.vue'
import localization from '../components/homeComponents/localization/index.vue'
import courses from '../components/homeComponents/courses/index.vue'
import testimonials from '../components/homeComponents/testimonials/index.vue'
import objective from '../components/homeComponents/objective/index.vue'
import authors from '../components/homeComponents/authors/index.vue'
import footerComponent from '../components/homeComponents/footerComponent/index.vue'

export default {
  components: {
    Header,
    localization,
    courses,
    testimonials,
    objective,
    authors,
    footerComponent
  }
}
</script>