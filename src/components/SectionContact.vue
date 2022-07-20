<!-- HTML -->
<template>
    <section>
        <div class="content-container">
            <div class="wrapper">
                <!-- Map-Col -->
                <div class="map-col">
                    <img class="world-map" src="../assets/img/h1-contact-rev-01.png" alt="world-map">
                    <img class="america" src="../assets/img/h1-contact-rev-02.png" alt="dot">
                    <img class="sweden" src="../assets/img/h1-contact-rev-02.png" alt="dot">
                    <img class="australia" src="../assets/img/h1-contact-rev-02.png" alt="dot">
                    <div class="world-position">
                        <h4>New York Coaching</h4>
                        <div>READ MORE</div>
                    </div>

                </div>
                <!-- Contact-Col -->
                <div class="contact-col">
                    <div class="section-title">
                        <h2>Contact-us</h2>
                        <div class="subtitle-point">
                            <i class="fa-solid fa-circle"></i>
                        </div>
                        <div>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit
                        </div>
                        <div class="left-line"></div>

                    </div>

                    <!-- User-Form -->
                    <div class="user-form">
                        <div>
                            <label for="name"></label>
                            <input type="text" placeholder="Your Name" id="name">
                            <label for="email"></label>
                            <input type="email" placeholder="Your Email" id="email">
                        </div>

                        <textarea name="message" id="" cols="50" rows="5" placeholder="Write Message"></textarea>

                    </div>

                    <!-- Button -->
                    <button>
                        <a href="#">SEND</a>

                        <div class="arrow">
                            <i class="fa-solid fa-arrow-right-long"></i>
                        </div>
                    </button>


                </div>

            </div>
            
            <!-- Icons -->
            <div class="icons">
                <div class="default">
                    <img src="../assets/img/h4-clients-img-03.png" alt="">
                    <img src="../assets/img/h4-clients-img-05.png" alt="">
                    <img src="../assets/img/h4-clients-img-07.png" alt="">
                    <img src="../assets/img/h4-clients-img-09.png" alt="">
                    <img src="../assets/img/h4-clients-img-01.png" alt="">
                </div>
                <div class="hovered">
                    <img src="../assets/img/h4-clients-img-04-1.png" alt="">
                    <img src="../assets/img/h4-clients-img-06-1.png" alt="">
                    <img src="../assets/img/h4-clients-img-08-1.png" alt="">
                    <img src="../assets/img/h4-clients-img-10-1.png" alt="">
                    <img src="../assets/img/h4-clients-img-02.png" alt="">

                </div>
            </div>

        </div>
        
    </section>

</template>

<!-- JAVASCRIPT -->
<script>
export default {
    
}
</script>

<!-- CSS -->
<style lang="scss" scoped>
section{
    padding: 120px 0;
    background-color: #fafafa;
    .wrapper{
        display: flex;
    }

    .map-col{
        position: relative;

        .america{
            position: absolute;
            top: 33%;
            right: 73%;
        }

        .sweden{
            position: absolute;
            top: 20%;
            right: 46%;
        }

        .australia{
            position: absolute;
            top: 72%;
            right: 14%;
        }

        .world-position{
            background-color: white;
            width: 225px;
            padding: 20px;
            position: absolute;
            top: 44%;
            left: 21%;

            h4{
                font-size: 20px;
            }
        }
    }

    .contact-col{
        padding-left: 50px;

        input{
            margin-right: 20px;
            padding: 10px;
            border: none;
            border-bottom: 1px solid #cfcfcf;
            background-color: #fafafa;
        }

        textarea{
            margin-top: 20px;
            border: none;
            border-bottom: 1px solid #cfcfcf;
            padding: 10px;
            background-color: #fafafa;
        }

        button{
            background-color: #ff4612;
            border: none;
            padding: 10px;
            margin-top: 20px;

            a{
                text-decoration: none;
                color: white;
                margin: 0 15px;
            }

            .arrow{
                display: inline-block;
                color: white;
            }
        }

        
    }

    .icons{
        padding-top: 80px;
        position: relative;
        .default{

            img{
                padding-right: 100px;
            }
        }

        .default :last-child{
            padding-right: 0;
        }

        .hovered{
            position: absolute;
            top: 52%;
            left: 0%;
            display: none;

            img{
                padding-right: 100px;

            }
        }

        .hovered :last-child{
            padding-right: 0;
        }
        
    }

    //HOVER
    .hovered:hover{
        display: block;
        cursor: pointer;
    }


}

</style>