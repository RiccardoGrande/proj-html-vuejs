<script>
export default {
    name: 'AppMain',
    data() {

        return {

            cards: [
                {
                    image: 'fable/images/schoolbag_alt.png',
                    title: 'Morbi Etos',
                    text: 'present interdum est gravida veicula esta noche estudas loaf morbius a dosid lucus nou est oresent.'


                },
                {
                    image: 'fable/images/stroller_alt.png',
                    title: 'Congue Gravida',
                    text: 'present interdum est gravida veicula esta noche estudas loaf morbius a dosid lucus nou est oresent.'


                },
                {
                    image: 'fable/images/globe_alt.png',
                    title: 'Morbi Etos',
                    text: 'present interdum est gravida veicula esta noche estudas loaf morbius a dosid lucus nou est oresent.'


                },
                {
                    image: 'fable/images/bell_alt.png',
                    title: 'Morbi Etos',
                    text: 'present interdum est gravida veicula esta noche estudas loaf morbius a dosid lucus nou est oresent.'


                }

            ]

        }

    }

}
</script>


<template>
    <section class="Fable_welcome">
        <div class="container m-auto">
            <div class="row">
                <div class="col text-center">
                    <h2 class="header_title p-4">Welcome to Fable</h2>
                </div>

            </div>
            <div class="row p-2">
                <div class="col text-center">
                    <div class="title p-2">Fable daycare. preschool and kindergarten</div>
                    <img src="fable/images/header_divider.png" alt="header_divider">
                </div>
            </div>
            <div class="row ">
                <div class="col" v-for="item in cards">
                    <div class="card text-center">
                        <img :src="item.image" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">{{ item.title }}</h5>
                            <p class="card-text">{{ item.text }}
                            </p>

                        </div>
                    </div>

                </div>

            </div>
        </div>

    </section>

    <section>
        <div class="container m-auto">
            <div class="row">
                <div class="col">
                    <div>
                        <span class="overwiew p-1">Overwiew</span>
                        <span class="mission p-1">Our mission</span>
                    </div>
                </div>
                <div class="col"></div>
            </div>
        </div>
    </section>
</template>



<style lang="scss" scoped>
h2 {
    color: #554e9e;
}

.title {
    color: rgb(180, 178, 178);
}

.card {
    border: none;
    margin: 1rem;

}



.card-img-top {
    background-color: #fe6601;
    border-radius: 50%;
}

.overwiew {
    background-color: #fe6601;
    color: #fff;
}

.mission {
    color: #e8e6e7;
}
</style>