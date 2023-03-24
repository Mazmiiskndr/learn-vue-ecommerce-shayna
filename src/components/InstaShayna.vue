<template lang="">
    <div>
        <!-- Instagram Section Begin -->
        <div class="instagram-photo">
            <div v-for="(photo, index) in photos" :key="index" class="insta-item set-bg" 
                :style="{ backgroundImage: 'url(' + photo + ')' }">
                <div class="inside-text">
                    <i class="ti-instagram"></i>
                    <h5><a href="#">shayna_gallery</a></h5>
                </div>
            </div>
        </div>
        <!-- Instagram Section End -->
    </div>
</template>
<script>
export default {
    name: "HeroShayna",
    data() {
        return {
            photos: ['/img/insta-1.jpg', '/img/insta-2.jpg', '/img/insta-3.jpg', '/img/insta-4.jpg', '/img/insta-5.jpg', '/img/insta-6.jpg']
        }
    }
}
</script>
<style lang="">
    
</style>
