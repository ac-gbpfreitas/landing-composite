<template>
    <main class="main-content">
        <!-- FEATURES ROW -->
        <FeaturesSection />
        <!-- FEATURES ROW END -->
        <!-- ABOUT ROW -->
        <AboutSection/>
        <!-- ABOUT ROW END -->
        <!-- WORK ROW -->
        <WorkSection />
        <!-- WORK ROW END -->
        <!-- PORTFOLIO ROW -->
        <PortfolioSection />
        <!-- PORTFOLIO ROW END -->
        <!-- CONTACT ROW -->
        <ContactSectionVue />
        <!-- CONTACT ROW END -->
    </main>
</template>

<script>
import AboutSection from './MainContent/AboutSection.vue';
import FeaturesSection from './MainContent/FeaturesSection.vue';
import PortfolioSection from './MainContent/PortfolioSection.vue';
import WorkSection from './MainContent/WorkSection.vue';

export default {
    name: "MainContent",
    components : {
        FeaturesSection,
        AboutSection,
        WorkSection,
        PortfolioSection
    }
}
</script>