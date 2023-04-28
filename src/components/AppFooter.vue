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
</style>