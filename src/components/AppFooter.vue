<script>
export default {
    name: 'AppFooter'

}
</script>


<template>
    <section class="contacts">
        <div class="container">
            <div class="row">
                <div class="col text-center">
                    <h2 class="header_title p-4">Contact Us</h2>
                </div>

            </div>
            <div class="row p-2">
                <div class="col text-center">
                    <div class="title p-2">Our postal address and contact details</div>
                    <img src="fable/images/header_divider.png" alt="header_divider">
                </div>
            </div>
            <div class="row">
                <div class="col d-flex ">

                    <div class="card text-center d-flex justify-content-center align-items-center">
                        <img src="fable/images/envelope (1).png" class="card-img-top img_contacts" alt="toy">
                        <div class="card-body">
                            <h5 class="card-title">Learning & Fun</h5>
                            <p class="card-text">lorem ipsum vida loca bla bla bla gears of war
                            </p>

                        </div>
                    </div>
                    <div class="card text-center d-flex justify-content-center align-items-center">
                        <img src="fable/images/mobile.png" class="card-img-top img_contacts" alt="toy">
                        <div class="card-body">
                            <h5 class="card-title">Learning & Fun</h5>
                            <p class="card-text">lorem ipsum vida loca bla bla bla gears of war
                            </p>

                        </div>
                    </div>


                    <div class="card text-center d-flex justify-content-center align-items-center">
                        <img src="fable/images/clock.png" class="card-img-top  img_contacts " alt="toy">
                        <div class="card-body">
                            <h5 class="card-title">Learning & Fun</h5>
                            <p class="card-text">lorem ipsum vida loca bla bla bla gears of war
                            </p>

                        </div>
                    </div>
                    <div class="card text-center d-flex justify-content-center align-items-center">
                        <img src="fable/images/document (1).png" class="card-img-top img_contacts" alt="toy">
                        <div class="card-body">
                            <h5 class="card-title">Learning & Fun</h5>
                            <p class="card-text">lorem ipsum vida loca bla bla bla gears of war
                            </p>

                        </div>
                    </div>




                </div>

            </div>
            <div class="row">
                <div class="col">
                    <input type="email" class="form-control m-3" id="colFormLabel" placeholder="Your Name*">
                    <input type="email" class="form-control m-3" id="colFormLabel" placeholder="Your Email*">
                    <input type="email" class="form-control m-3" id="colFormLabel" placeholder="Subject">
                </div>
                <div class="col">
                    <textarea class="form-control m-3" id="validationTextarea" placeholder="Your message*"
                        required></textarea>
                </div>

            </div>
            <div class="row">
                <div class="col d-flex justify-content-center align-items-center">
                    <button class="orange_button p-2 ">SEND MESSAGE</button>
                </div>

            </div>
        </div>
    </section>

    <section class="summary">
        <div class="container">
            <div class="row d-flex">
                <div class="col">
                    <h5>ABOUT US</h5>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Accusamus quaerat ipsum nulla libero id
                        odio, numquam itaque nobis adipisci aperiam, corrupti voluptatibus quibusdam. Ad fugit aperiam
                        itaque reprehenderit facilis ex?</p>
                    <img class="img_footer" src="fable/images/logo_footer.png" alt="logo_footer">
                </div>
                <div class="col">
                    <h5>ARCHIVES</h5>
                    <label for="validationServer01" class="form-label p-1">OCTOBER 2014 (2)</label>
                    <label for="validationServer01" class="form-label p-1">OCTOBER 2014 (2)</label>
                    <label for="validationServer01" class="form-label p-1">OCTOBER 2014 (2)</label>
                    <label for="validationServer01" class="form-label p-1">OCTOBER 2014 (2)</label>
                    <label for="validationServer01" class="form-label p-1">OCTOBER 2014 (2)</label>
                    <label for="validationServer01" class="form-label p-1">OCTOBER 2014 (2)</label>
                </div>
                <div class="col">
                    <h5>OUR FEATURES</h5>
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Minus ex quaerat incidunt, fuga quam,
                        delectus sint perferendis ipsa doloribus dignissimos rem quasi officia labore! Atque animi sed
                        molestiae perferendis eaque.</p>
                    <ul>
                        <li>Comprehensive reporting on individual achievement</li>
                        <li>Educational field tripa and school presentations</li>
                        <li>Individual attention in a small class setting</li>
                        <li>Learning program with after-school care</li>
                        <li>Opporyunities to carry out scientific investigations</li>
                        <li>Positive learning environment for your child</li>
                    </ul>
                </div>
                <div class="col">
                    <h5>RECENT POSTS</h5>
                    <div class="d-flex align-items-center">
                        <div> <img class="img_footer" src="fable/images/gallery_03-690x506.jpg" alt=""></div>
                        <div>
                            <div>Drawing and painting lessons</div>
                            <div>&#128197; October 03 2014</div>
                        </div>
                    </div>
                    <div class="d-flex align-items-center">
                        <div> <img class="img_footer" src="fable/images/gallery_03-690x506.jpg" alt=""></div>
                        <div>
                            <div>Drawing and painting lessons</div>
                            <div>&#128197; October 03 2014</div>
                        </div>
                    </div>
                    <div class="d-flex align-items-center">
                        <div> <img class="img_footer" src="fable/images/gallery_03-690x506.jpg" alt=""></div>
                        <div>
                            <div>Drawing and painting lessons</div>
                            <div>&#128197; October 03 2014</div>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <section class="link_social">
        <div class="container">
            <div class="row d-flex flex-column">
                <div class="col d-flex justify-content-center align-items-center">
                    <img class="orange_button m-1" src="fable/images/behance.png" alt="behance">
                    <img class="orange_button m-1" src="fable/images/dribbble.png" alt="dribbble">
                    <img class="orange_button m-1" src="fable/images/envato.png" alt="envato">
                    <img class="orange_button m-1" src="fable/images/facebook.png" alt="facebook">
                    <img class="orange_button m-1" src="fable/images/twitter.png" alt="twitter">

                </div>
                <div class="col d-flex justify-content-center align-items-center p-2">
                    <div>&copy;Fable-Children Kindergarten Wordpress theme by QuanticaLabs</div>
                </div>
            </div>
        </div>

    </section>
</template>



<style lang="scss" >
h2 {
    color: #554e9e;
}

.img_contacts {
    height: 30px;
    width: 30px;
}

.orange_button {
    background-color: #fe6601;
    color: white;
    border: none;

}

.summary {
    background-image: url('fable/images/pattern.png');
    color: white;
}

label {
    border: 1px solid white;
    width: 200px;
}



.img_footer {
    height: 60px;
}
</style>