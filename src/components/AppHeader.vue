<script>
import AppBannerNav from './AppBannerNav.vue'
import AppJumbo from './AppJumbo.vue'
export default {
    name: 'AppHeader',
    components: {
        AppBannerNav,
        AppJumbo
    }

}
</script>


<template>
    <AppBannerNav></AppBannerNav>
    <AppJumbo></AppJumbo>
    <section class="learn_more">
        <div class="container">
            <div class="row">
                <div class="col text-end">
                    <h4>How to Enroll Your Child to a Class?</h4>
                </div>
                <div class="col d-flex align-items-center justify-content-center">
                    <a href="h"></a>
                    <img src="fable/hover-button2.png" alt="">
                </div>
            </div>
        </div>
    </section>
</template>



<style lang="scss" scoped>
.learn_more {
    background-image: url('fable/images/pattern.png');
}

h4 {
    padding: 1rem;
    color: white;
}

img {
    height: 60px;
}
</style>