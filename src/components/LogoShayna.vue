<template lang="">
    <div>
        <!-- Partner Logo Section Begin -->
        <div class="partner-logo">
            <div class="container">
                <carousel class="logo-carousel" :items="5" :nav="false">
                    <div v-for="(logo, index) in logos" :key="index" class="logo-item">
                        <div class="tablecell-inner">
                            <img :src="'img/logo-carousel/' + logo" alt="" />
                        </div>
                    </div>
                </carousel>
            </div>
        </div>
        <!-- Partner Logo Section End -->
    </div>
</template>
<script>
import carousel from 'vue-owl-carousel'
export default {
    name: "LogoShayna",
    components: {
        carousel,
    },
    data() {
        return {
            logos: ['logo-1.png', 'logo-2.png', 'logo-3.png', 'logo-4.png', 'logo-5.png']
        }
    }
}
</script>
<style lang="">
    
</style>
