<template>
  <div>
    <Navbar />
    <HeroSection />
    <PartnerLogos />
    <SearchCourses />
    <Benefits />
    <PopularCourses />
    <BecomeInstructor />
    <Testimonials />
    <GetinTouch />
    <Footer />
  </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
import HeroSection from '../components/HeroSection.vue';
import PartnerLogos from '../components/PartnerLogos.vue';
import SearchCourses from '../components/SearchCourses.vue';
import Benefits from '../components/Benefits.vue';
import PopularCourses from '../components/PopularCourses.vue';
import BecomeInstructor from '../components/BecomeInstructor.vue';
import Testimonials from '../components/Testimonials.vue';
import GetinTouch from '../components/GetinTouch.vue';
import Footer from '../components/Footer.vue';

export default {
  components: {
    Navbar,
    HeroSection,
    PartnerLogos,
    SearchCourses,
    Benefits,
    PopularCourses,
    BecomeInstructor,
    Testimonials,
    GetinTouch,
    Footer
  }
}
</script>
