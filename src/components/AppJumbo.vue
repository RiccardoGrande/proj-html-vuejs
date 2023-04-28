<script>
export default {
    name: 'AppJumbo'

}
</script>


<template>
    <section class="jumbotron">
        <div class="container">
            <div class="row p-3 mb-3">
                <div class="col ">
                    <h1>Learning & Fun</h1>
                </div>
            </div>
            <div class="row p-3 mt-3">
                <div class="col-4">


                </div>
                <div class="col d-flex align-items-center justify-content-between">
                    <img src="fable/images/slider_slide3_img2.png" alt="">
                    <img src="fable/images/slider_slide3_img3.png" alt="">
                </div>
            </div>
        </div>

    </section>
</template>



<style lang="scss" scoped>
h1 {
    font-family: 'Shadows Into Light', cursive;
    color: rgb(169, 166, 166);
    padding-top: 100px;
    font-size: 2rem;
}

.row {
    height: 160px;
}

.jumbotron {
    height: 400px;
    background: linear-gradient(to bottom,
            lightblue 0%, transparent,
            white 50%, transparent,
            rgb(233, 232, 232) 60%,
            rgb(233, 232, 232) 80%,
            rgb(237, 236, 236) 90%),
        rgb(237, 236, 236) 100%
}

img {
    height: 100px;

}
</style>