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
                    <h2 class="header_title p-2">Welcome to Fable</h2>
                </div>

            </div>
            <div class="row p-2">
                <div class="col text-center">
                    <div class="title p-2">Fable daycare. preschool and kindergarten</div>
                    <img src="fable/images/header_divider.png" alt="header_divider">
                </div>
            </div>
            <div class="row ">
                <div class="col d-flex align-items-center justify-content-center" v-for="item in cards">
                    <div class="card d-flex align-items-center justify-content-center text-center">
                        <img :src="item.image" class="card-img-top cardz" alt="...">
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
                    <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
                        <div class="carousel-inner">
                            <div class="carousel-item active">
                                <img src="/fable/images/gallery_01.jpg" class="d-block w-100" alt="...">
                            </div>
                            <div class="carousel-item">
                                <img src="'/fable/images/gallery_07-690x506.jpg'" class="d-block w-100" alt="...">
                            </div>
                            <div class="carousel-item">
                                <img src="'/fable/images/gallery_08-690x506.jpg'" class="d-block w-100" alt="...">
                            </div>
                        </div>
                        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls"
                            data-bs-slide="prev">
                            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                            <span class="visually-hidden">Previous</span>
                        </button>
                        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls"
                            data-bs-slide="next">
                            <span class="carousel-control-next-icon" aria-hidden="true"></span>
                            <span class="visually-hidden">Next</span>
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>


    <section class="graphic">
        <div class="container m-auto">
            <div class="row ">
                <div class="col" v-for="item in graphics">
                    <div class="card text-center">
                        <div class="number_graphic card-img-top">{{ item.number }}</div>
                        <div class="card-body graphic_body">
                            <h5 class="card-title">{{ item.title }}</h5>
                            <p class="card-text">{{ item.text }}
                            </p>

                        </div>
                    </div>

                </div>

            </div>

        </div>


    </section>

    <section class="our_classes">
        <div class="container m-auto">
            <div class="row">
                <div class="col text-center">
                    <h2 class="header_title p-4">Our Classes</h2>
                </div>

            </div>
            <div class="row p-2">
                <div class="col text-center">
                    <div class="title p-2">Our preschool program has four dedicated classes</div>
                    <img src="fable/images/header_divider.png" alt="header_divider">
                </div>
            </div>
            <div class="row m-auto">
                <div class="col-6">
                    <h4>We provided four classes with nine to twenty children each aged twelve month to five years of age.
                    </h4>
                </div>
                <div class="col-6">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum quam delectus culpa fugiat suscipit
                        corrupti modi quisquam expedita, nam quos voluptatum ab libero rerum facilis repudiandae ex,
                        repellendus, minus optio!</p>
                </div>
            </div>
            <div class="row">
                <div class="col col_class d-flex m-2">
                    <div class="d-flex flex-column flex-grow-1">
                        <h6>Little Lambs</h6>
                        <p>Class name</p>
                        <div class="d-flex">
                            <span class="p-1">
                                <div>12-24</div>
                                <div>Month olds</div>
                            </span>
                            <span class="size_class p-1">
                                <div>9</div>
                                <div>Class size</div>
                            </span>
                        </div>
                    </div>
                    <div><img class="img_classes" src="fable/images/gallery_04.jpg" alt=""></div>
                </div>
                <div class="col col_class d-flex m-2">
                    <div class="d-flex flex-column flex-grow-1">
                        <h6>Little Lambs</h6>
                        <p>Class name</p>
                        <div class="d-flex">
                            <span class="p-1">
                                <div>12-24</div>
                                <div>Month olds</div>
                            </span>
                            <span class="size_class p-1">
                                <div>9</div>
                                <div>Class size</div>
                            </span>
                        </div>
                    </div>
                    <div><img class="img_classes" src="fable/images/class_02-690x506.jpg" alt=""></div>
                </div>
            </div>
            <div class="row">
                <div class="col col_class d-flex m-2">
                    <div class="d-flex flex-column flex-grow-1">
                        <h6>Little Lambs</h6>
                        <p>Class name</p>
                        <div class="d-flex">
                            <span class="p-1">
                                <div>12-24</div>
                                <div>Month olds</div>
                            </span>
                            <span class="size_class p-1">
                                <div>9</div>
                                <div>Class size</div>
                            </span>
                        </div>
                    </div>
                    <div><img class="img_classes" src="fable/images/class_03-690x506.jpg" alt=""></div>
                </div>
                <div class="col col_class d-flex m-2">
                    <div class="d-flex flex-column flex-grow-1">
                        <h6>Little Lambs</h6>
                        <p>Class name</p>
                        <div class="d-flex">
                            <span class="p-1">
                                <div>12-24</div>
                                <div>Month olds</div>
                            </span>
                            <span class="size_class p-1">
                                <div>9</div>
                                <div>Class size</div>
                            </span>
                        </div>
                    </div>
                    <div><img class="img_classes" src="fable/images/class_04-690x506.jpg" alt=""></div>
                </div>
            </div>

        </div>




    </section>


    <section class="education">
        <div class="container m-auto">
            <div class="row">
                <div class="col-6">
                    <h4>We have been educating children for over fifteen years.Our goal is to create a place that engages
                        each child.</h4>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fugiat debitis alias maxime consectetur
                        aliquam esse sequi, placeat dolorem iste rerum iusto quasi fugit, quisquam aliquid veritatis? Hic
                        sequi eius alias.</p>

                    <ul>
                        <li>Comprehensive reporting on individual achievement</li>
                        <li>Educational field tripa and school presentations</li>
                        <li>Individual attention in a small class setting</li>
                        <li>Learning program with after-school care</li>
                        <li>Opporyunities to carry out scientific investigations</li>
                        <li>Positive learning environment for your child</li>
                    </ul>
                </div>
                <div class="col d-flex ">
                    <div class="col">
                        <div class="card text-center d-flex justify-content-center align-items-center">
                            <img src="fable/images/toy.png" class="card-img-top card_education" alt="toy">
                            <div class="card-body">
                                <h5 class="card-title">Learning & Fun</h5>
                                <p class="card-text">lorem ipsum vida loca bla bla bla gears of war
                                </p>

                            </div>
                        </div>
                        <div class="card text-center d-flex justify-content-center align-items-center">
                            <img src="fable/images/toy.png" class="card-img-top card_education" alt="toy">
                            <div class="card-body">
                                <h5 class="card-title">Learning & Fun</h5>
                                <p class="card-text">lorem ipsum vida loca bla bla bla gears of war
                                </p>

                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card text-center d-flex justify-content-center align-items-center">
                            <img src="fable/images/toy.png" class="card-img-top d-flex card_education " alt="toy">
                            <div class="card-body">
                                <h5 class="card-title">Learning & Fun</h5>
                                <p class="card-text">lorem ipsum vida loca bla bla bla gears of war
                                </p>

                            </div>
                        </div>
                        <div class="card text-center d-flex justify-content-center align-items-center">
                            <img src="fable/images/toy.png" class="card-img-top card_education" alt="toy">
                            <div class="card-body">
                                <h5 class="card-title">Learning & Fun</h5>
                                <p class="card-text">lorem ipsum vida loca bla bla bla gears of war
                                </p>

                            </div>
                        </div>

                    </div>


                </div>






            </div>
        </div>
    </section>

    <section class="random_images d-flex">
        <img class="rand_img" src="fable/images/gallery_01.jpg" alt="">
        <img class="rand_img" src="fable/images/gallery_02.jpg" alt="">
        <img class="rand_img" src="fable/images/gallery_03.jpg" alt="">
        <img class="rand_img" src="fable/images/gallery_04.jpg" alt="">

    </section>

    <section class="view_gallery">
        <div class="container">
            <div class="row">
                <div class="col text-end">
                    <h4 class="title_gallery">See our Kindergarten Photo Gallery!</h4>
                </div>
                <div class="col d-flex align-items-center justify-content-center">
                    <button class="gallery_button">VIEW GALLERY &#8811;</button>

                </div>
            </div>

        </div>
    </section>
</template>



<style lang="scss" >
h2,
h4 {
    color: #554e9e;
}

.title {
    color: rgb(180, 178, 178);
}

.card {
    border: none;
    margin: 1rem;
    background-color: transparent !important;

}

//use child property!!!
.cardz:nth-child(1) {
    background-color: #fe6601;
    border-radius: 50%;
    height: 80px;
    width: 80px;

}

.cardz:nth-child(3) {
    background-color: #fe6601;
    border-radius: 50%;
    height: 80px;
    width: 80px;

}

.cardz:nth-child(2) {
    background-color: #554e9e;
    border-radius: 50%;
    height: 80px;
    width: 80px;

}

.cardz:nth-child(4) {
    background-color: #554e9e;
    border-radius: 50%;
    height: 80px;
    width: 80px;

}

.Overwiew_section {
    background-color: #e8e6e7;
    padding: 1rem;

}

.overwiew {
    background-color: #fe6601;
    color: #fff;
}

.mission {
    color: #e8e6e7;
}

.graphic {
    background-image: url('fable/images/parallax_01.jpg');
}

.number_graphic {
    border: 1px solid white;
    border-radius: 50%;
    font-size: 3rem;
    padding: 3rem;
    color: white;
}

.graphic_body {
    color: white;
}

.col_class {

    background-color: #554e9e;
    color: white;
}

.size_class {

    border-left: 1px solid white;
}

.img_classes {
    height: 120px;
    width: 100%;
}

.education {
    background-color: #e8e6e7;
}

.card_education {
    border-radius: 50%;
    height: 80px;
    width: 80px;
}

.rand_img {
    height: 280px
}

.view_gallery {
    background-image: url('fable/images/pattern.png');
}

.title_gallery {
    padding: 1rem;
    color: white;
}

.gallery_button {
    background-color: transparent;
    color: white;
    font-weight: bolder;
    padding: 0.5rem;
    border: 1px solid white;
}
</style>