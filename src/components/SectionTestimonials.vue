<!-- HTML -->
<template>
    <section class="mobile-padding">
        <!-- Section-bg-txt -->
        <div class="section-bg-txt text-center">
            Testimonials.
        </div>

        <div class="wrapper">
            <!-- Arrow-Left -->
            <div class="arrow">
                <i class="fa-solid fa-arrow-left-long"></i>
            </div>

            <!-- Section-Content -->
            <div class="section-content text-center">
                <!-- Testimonial-Info -->
                <div class="testimonial-info">
                    <img src="../assets/img/h3-img-04.png" alt="">
                    <div class="testimonial-name">Cynthia Clark</div>
                    <div class="testimonial-text"> 
                        "Lorem ipsum dolor sit, amet consectetur adipisicing elit sed eiusmod <br> tempor incididunt ut labore et dolore mangna aliqua."
                    </div>

                </div>
                
                <!-- Current-Testimonial -->
                <div class="current-testimonial">
                    <span>01</span>
                    <div class="testimonial-bar">
                        <div class="current-testimonial-bar">

                        </div>

                    </div>
                    <span>03</span>
                </div>
            </div>

            <!-- Arrow-Right -->
            <div class="arrow">
                <i class="fa-solid fa-arrow-right-long"></i>
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
    background-color: #1e1c1c;
    .section-bg-txt{
        color: #181515;
        font-size: 250px;
        font-weight: bold;

    }

    .arrow{
        color: white;

    }

    .wrapper{
        display: flex;
        justify-content: space-between;
        align-items: center;

        .section-content{

            .testimonial-name{
                color: white;
                padding: 20px 0;
                font-size: 20px;
            }

            .testimonial-text{
                font-size: 25px;
                color: #a4a3a3;
                padding-bottom: 20px;
            }

        }

        .current-testimonial{
            padding-bottom: 100px;
            
            span{
                vertical-align: middle;
                color: #a4a3a3;
            }

            .testimonial-bar{
                display: inline-block;
                background-color: #a4a3a3;
                width: 100px;
                height: 1px;
                vertical-align: middle;
                margin: 0 10px;

                .current-testimonial-bar{
                    width: 33%;
                    height: 1px;
                    background-color: white;

                }
            }

        }

        
    }
}

</style>