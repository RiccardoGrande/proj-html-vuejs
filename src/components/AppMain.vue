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

            ],
            graphics: [
                {
                    number: '507',
                    title: 'Our Pupils',
                    text: 'present interdum est gravida veicula esta noche estudas loaf morbius a dosid lucus nou est oresent.'


                },
                {
                    number: '235',
                    title: 'Teaching Hours',
                    text: 'present interdum est gravida veicula esta noche estudas loaf morbius a dosid lucus nou est oresent.'


                },
                {
                    number: '100%',
                    title: 'Satisfied Parents',
                    text: 'present interdum est gravida veicula esta noche estudas loaf morbius a dosid lucus nou est oresent.'


                },
                {
                    number: '1050',
                    title: 'Meals per Year',
                    text: 'present interdum est gravida veicula esta noche estudas loaf morbius a dosid lucus nou est oresent.'


                }


            ],
            activeImage: 0,
            images: ['fable/images/gallery_01.jpg',
                'fable/images/gallery_07.jpg',
                'fable/images/gallery_08.jpg'],

        }

    },
    methods: {


        next() {
            console.log(this.images)
            this.activeImage++
            if (activeImage > images.length - 1) {

                activeImage = 0;
            }


            console.log(this.images)
        },
        prev() {

            console.log(this.images)

            this.activeImage--
            if (activeImage < 0) {

                activeImage = 4;
            }


        },
        changeImage(index) {

            this.activeImage = index

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

    <section class="Overwiew_section">
        <div class="container m-auto">
            <div class="row d-flex">
                <div class="col">
                    <div>
                        <span class="overwiew p-1">Overwiew</span>
                        <span class="mission p-1">Our mission</span>
                    </div>

                    <h3>Our philosophy is learning trough play as we offer a stimulating enviroment for children.</h3>
                    <div class="d-flex">
                        <div>
                            <img src="fable/images/clock.png" alt="clock">
                        </div>
                        <div>

                            <h6>Full Day Sessions</h6>
                            <p>pulvinar est metro laguna blandit mecenas gravida retrum cuprum. Mecenas node stibulum
                            </p>


                        </div>
                    </div>
                    <div class="d-flex">
                        <div>
                            <img src="fable/images/school.png" alt="clock">
                        </div>
                        <div>

                            <h6>Varied Classes</h6>
                            <p>pulvinar est metro laguna blandit mecenas gravida retrum cuprum. Mecenas node stibulum
                            </p>


                        </div>
                    </div>

                </div>
                <div class="col">
                    <div class="card">

                        <img :class="index === activeImage ? 'active' : ''" :src="images" alt="image" v-for="item in images"
                            @click="changeImage(index)">

                        <div id="buttons">

                            <button @click="prev">Prev</button>
                            <button @click="next">Next</button>

                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>


    <section class="graphic">
        <div class="row ">
            <div class="col" v-for="item in graphics">
                <div class="card text-center">
                    <div class="number_graphic">{{ item.number }}</div>
                    <div class="card-body">
                        <h5 class="card-title">{{ item.title }}</h5>
                        <p class="card-text">{{ item.text }}
                        </p>

                    </div>
                </div>

            </div>

        </div>

    </section>
</template>



<style lang="scss" >
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

.graphic {
    background-image: url('fable/images/parallax_01.jpg');
}

.number_graphic {
    border: 1px solid white;
    border-radius: 50%;
}


//use child property!!!
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