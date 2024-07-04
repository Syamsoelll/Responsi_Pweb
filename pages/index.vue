<template>
  <div>
    <Navbar />
    <HeroSection />
    <ProjectsSection />
    <AboutSection />
    <ContactSection />
    <Footer />
  </div>
</template>

<script>
import HeroSection from '~/components/HeroSection.vue';
import AboutSection from '~/components/AboutSection.vue';
import ProjectsSection from '~/components/ProjectsSection.vue';
import ContactSection from '~/components/ContactSection.vue';
import Navbar from '../components/partials/Navbar.vue';
import Footer from '../components/partials/Footer.vue';


export default {
  components: {
    Navbar,
    HeroSection,
    ProjectsSection,
    AboutSection,
    ContactSection,
    Footer
  }
}
</script>./Index.vue
