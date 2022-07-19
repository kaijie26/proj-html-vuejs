<!-- HTML -->
<template>
    <section>
        <div class="content-container">
            <!-- Left-Col -->
            <div class="left-col">
                <img src="../assets/img/h1-img-01.jpg" alt="">
                
            </div>

            <!-- Right-Col -->
            <div class="right-col">
                <!-- Description -->
                <h3>Jason Bickford</h3>
                <div>Founder and Executive Director</div>
                <div class="left-line"></div>
                <div>
                    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quidem, reiciendis deserunt nihil commodi...
                </div>
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

            <!-- Donuts -->
            <div class="donuts">
                <img src="../assets/svg/svg-4.svg" alt="">
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
    background-color: #fafafa;
    position: relative;

    .left-col{
        width: 55%;
        display: inline-block;
        position: relative;

        img{
            width: 100%;
            
        }
    }

    .right-col{
        width: 45%;
        display: inline-block;
        background-color: white;
        padding: 50px 0px;
        padding-left: 30px;
        padding-right: 50px;
        position: absolute;
        transform: translate(-15%, 15%);
        z-index: 1;
        h3{
            font-size: 35px;
        }

        .social-icons{
            margin-top: 20px;
            display: flex;

            div{
                background-color: #ff4612;
                color: white;
                margin-right: 5px;
                border-radius: 50%;
                text-align: center;
                padding: 5px;
                width: 25px;
                height: 25px;
            }
        }

    }

    .donuts{
        position: absolute;
        transform: translate(150%,-120%);
    }
}

</style>