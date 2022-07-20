<!-- HTML -->
<template>
    <footer>
        <div class="content-container">
            <!-- Footer-Top -->
            <div class="footer-top">
                <div class="columns">
                    <!-- Col -->
                    <div class="col">
                        <h3>About</h3>
                        <div class="left-line"></div>
                        <p>
                            We created Everlead to effectively become the stepping stone towards meeting all your goals & achieving business success.
                        </p>
                        <!-- Social-Icons -->
                        <div class="social-icons">
                            <div>
                                <i class="fab fa-linkedin-in"></i>
                            </div>
                            <div>
                                <i class="fa-brands fa-facebook-f"></i>
                            </div>
                            <div>
                                <i class="fa-brands fa-twitter"></i>
                            </div>

                        </div>


                    </div>

                    <!-- Col -->
                    <div class="col">
                        <h3>Twitter</h3>
                        <div class="left-line"></div>
                        <!-- Twitter-Contact -->
                        <div class="twitter-contact">
                            <div class="twitter-icon">
                                <i class="fa-brands fa-twitter"></i>
                            </div>
                            <p>
                                @<a href="#">aliasadadm</a> Hi @<a href="#">aliasadadm</a>, can you please submit a ticket at <a href="#">https://t.co/JVL61aXG7d</a> and one of our support agent... <a href="#">https://t.co/vk57k1S9bS</a>
                                
                            </p>
                            
                        </div>

                        <!-- Twitter-Contact -->
                        <div class="twitter-contact">
                            <div class="twitter-icon">
                                <i class="fa-brands fa-twitter"></i>
                            </div>
                            <p>
                                @<a href="#">HenrySefaBoaky1</a> Check out our theme Gioia which has all necessary elements to build a multi vendor marketplace. <a href="#">https://t.co/c9BlYxZBlL</a>
                            </p>
                            
                        </div>

                    </div>

                    <!-- Col -->
                    <div class="col">
                        <h3>Important links</h3>
                        <div class="left-line"></div>
                        <!-- Links -->
                        <div class="links">
                            <a href="#">About me</a>
                            <a href="#">About us</a>
                            <a href="#">Language packs</a>
                            <a href="#">Become a coach</a>
                            <a href="#">Monthlyn events</a>

                        </div>


                    </div>

                    <!-- Col -->
                    <div class="col">
                        <h3>Contact me</h3>
                        <div class="left-line"></div>
                        <!-- List-Contact -->
                        <ul class="list-conatct">
                            <!-- Adress -->
                            <li>
                                <span class="icon">
                                    <i class="fa fa-map-marker" aria-hidden="true"></i>
                                </span>
                                <span>457 BigBlue Street, NY 10013 </span>
                            </li>
                            <!-- Phone-Number -->
                            <li>
                                <span class="icon">
                                    <i class="fa-solid fa-phone"></i>
                                </span>
                                <span>(315) 5512-2579</span>
                            </li>
                            <!-- Email -->
                            <li>
                                <span class="icon">
                                    <i class="fa fa-envelope" aria-hidden="true"></i>
                                </span>
                                <span>everlead@mikado.com</span>
                            </li>

                        </ul>
                        
                        <!-- Subscribe -->
                        <div class="subscribe">
                            <div class="flex-container">
                                <div>Your name</div>
                                <div>SUBSCRIBE</div>
                            </div>
                            <hr>
                        </div>


                    </div>

                </div>

            </div>
        </div>
            <!-- Footer-Bottom -->
        <div class="footer-bottom">
            <div class="text-center">
                Copyright Everlead&copy;MikadoThemes
            </div>
        </div>
        
    </footer>

</template>

<!-- JAVASCRIPT -->
<script>
export default {

    
}
</script>

<!-- CSS -->
<style lang="scss" scoped>
footer{
    background-color: black;
    
    .footer-top{
        padding: 120px 0;

    }
    .columns{
        display: flex;
        
        .col{
            width: calc(100% / 4);
            padding-right: 20px;

            h3{
                font-size: 25px;
                color: white;
            }

            p{
                color: #8d8c8c;
                
                a{
                    color: #8d8c8c;
                }
            }

            .left-line::before{
            content: '';
            width: 30px;
            height: 2px;
            background-color: #ff4612;
            margin: 10px 0;
            display: inline-block;   
            }

            .social-icons{
                margin-top: 20px;
                display: flex;

                div{
                    background-color: white;
                    color: black;
                    margin-right: 5px;
                    border-radius: 50%;
                    text-align: center;
                    padding: 5px;
                    width: 25px;
                    height: 25px;
                }
            }

            .twitter-contact{
                display: flex;
                padding-bottom: 20px;

                .twitter-icon{
                    padding-right: 10px;
                    color: #ff4612;
                }
            }

            hr{
                margin-top: 5px;
                background-color: white;
                border: white;
                height: 1px;
                
            }

            .links{

                a{
                    color: #8d8c8c;
                    text-decoration: none;
                    display: block;
                    padding-bottom: 10px;
                }
            }

            .icon{
                color: #ff4612;
                padding-right: 10px;
            }

            li{
                color: #8d8c8c ;
            }

            .subscribe{
                color: #8d8c8c;
                padding-top: 30px;
            }

        }
    }

    .footer-bottom{
        background-color: #ff4612;
        color: #f4f4f4;
        padding: 10px;
        font-size: 13px;

    }
}

</style>