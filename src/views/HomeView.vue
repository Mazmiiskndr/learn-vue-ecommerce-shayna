<template>
  <div class="home">
    
    <!-- Start Header -->
    <HeaderShayna />
    <!-- End Header -->

    <!-- Start Header -->
    <HeroShayna />
    <!-- End Header -->

    <!-- Start Section -->
    <WomanShayna />
    <!-- End Section -->

    <!-- Start Instagram -->
    <InstaShayna />
    <!-- End Instagram -->

    <!-- Start Instagram -->
    <LogoShayna />
    <!-- End Instagram -->

    <!-- Start Instagram -->
    <FooterShayna />
    <!-- End Instagram -->

  </div>
</template>

<script>
import HeaderShayna from '@/components/HeaderShayna.vue';
import HeroShayna from '@/components/HeroShayna.vue';
import WomanShayna from '@/components/WomanShayna.vue';
import InstaShayna from '@/components/InstaShayna.vue';
import LogoShayna from '@/components/LogoShayna.vue';
import FooterShayna from '@/components/FooterShayna.vue';

export default {
  name: 'HomeView',
  components: {
    HeaderShayna,
    HeroShayna,
    WomanShayna,
    InstaShayna,
    LogoShayna,
    FooterShayna,
  }
}
</script>
