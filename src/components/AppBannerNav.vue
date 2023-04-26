<script>
export default {
    name: 'AppBannerNav',
    data() {

        return {

            banner: [
                {
                    image: 'fable/home.png',
                    text: 'Home',


                },
                {
                    image: 'fable/document.png',
                    text: 'Pages',


                },
                {
                    image: 'fable/printer.png',
                    text: 'Blog',


                },
                {
                    image: 'fable/cart.png',
                    text: 'Shop',


                },
                {
                    image: 'fable/lab.png',
                    text: 'Shortcodes',


                },
                {
                    image: 'fable/chat.png',
                    text: 'Support',


                },
                {
                    image: 'fable/envelope.png',
                    text: 'Contact',


                }
            ]

        }

    }

}
</script>


<template>
    <section>
        <div class="container">
            <div class="row p-2">
                <div class="col-4 d-flex align-items-center justify-content-center">
                    <img class="logo" src="/fable/images/logo.png" alt="fable_logo">
                </div>
                <div class="col-6 d-flex">
                    <div class="col d-flex flex-column align-items-center justify-content-center" v-for="item in banner">
                        <img class="icon" :src="item.image">
                        <span>{{ item.text }}</span>

                    </div>


                </div>

            </div>

        </div>

    </section>
</template>



<style lang="scss" scoped>
.logo {
    height: 100px;
}

.col {
    padding: 0;
}

.icon {
    height: 30px;
    width: 30px;

}

span {
    padding-top: 10px;
    color: #554e9e;
}
</style>