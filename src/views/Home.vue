<template>
  <div class="home">
        <!-- Page Preloder -->
    <!-- <div id="preloder">
        <div class="loader"></div>
    </div> -->
    <HeaderShayna></HeaderShayna>

        <!-- Hero Section Begin -->
    <section class="hero-section">
        <carousel class="hero-items" :items=1 :nav=false :mouseDrag=true>
            <HeroShayna style="background-image: url('img/hero-1.jpg')"/>
            <HeroShayna style="background-image: url('img/hero-2.jpg')"/>
            <HeroShayna style="background-image: url('img/hero-3.jpg')"/>
        </carousel>
    </section>
    <SectionShayna />
    <InstaShayna />
    <PartnerShayna />
    <FooterShayna />
    <!-- Hero Section End --> 
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from '@/components/HeaderShayna.vue'
import carousel from 'vue-owl-carousel'
import HeroShayna from '@/components/HeroShayna.vue';
import SectionShayna from '@/components/SectionShayna.vue';
import InstaShayna from '@/components/InstaShayna.vue';
import PartnerShayna from '@/components/PartnerShayna.vue';
import FooterShayna from '@/components/FooterShayna.vue';

export default {
  name: 'Home',
  components: {
    HeaderShayna,
    carousel,
    HeroShayna,
    SectionShayna,
    InstaShayna,
    PartnerShayna,
    FooterShayna
  }
}
</script>
