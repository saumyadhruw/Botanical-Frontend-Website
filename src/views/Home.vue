<template>
  <div class="mx-auto">
    <NavBar />
    <Section1 />
    <Section2/>
    <Section3/>
    <Footer />
  </div>
</template>

<script>
import Footer from '../components/Footer/Footer.vue';
import Section1 from "../components/HomePage/Section1.vue";
import Section2 from '../components/HomePage/Section2.vue';
import Section3 from '../components/HomePage/Section3.vue';
import NavBar from "../components/NavBar/NavBar.vue";
// @ is an alias to /src

export default {
  name: "Home",
  components: {
    NavBar,
    Section1,
    Section2,
    Section3,
    Footer
  },
};
</script>
