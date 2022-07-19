<!-- HTML -->
<template>
    <section>
        <div class="content-container">
            <div class="wrapper">
                <!-- Text-Col -->
                <div class="text-col">
                    <!-- Section-Title -->
                    <h2>Creative Leader</h2>
                    <!-- Point -->
                    <div class="subtitle-point">
                        <i class="fa-solid fa-circle"></i>
                    </div>
                    <!-- Left-Line -->
                    <div class="left-line"></div>
                    <!-- text  -->
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestiae sunt perspiciatis, nam, dignissimos officiis optio quisquam modi, eligendi quidem laudantium provident tenetur obcaecati laboriosam perferendis animi debitis ad illum possimus!
                    </p>
                    <!-- More-info -->
                    <div>READ MORE</div>

                </div>

                <!-- Analytics-Col -->
                <div class="analytics-col">
                    <!-- Single-type-analytic -->
                    <div class="type">
                        <div class="wrapper">
                            <h4>Mentorship</h4>
                            <div class="rate">78%</div>

                        </div>
                        <div class="line">
                            <div class="colored-line mentorship"></div>
                        </div>
                    </div>

                    <!-- Single-type-analytic -->
                    <div class="type">
                        <div class="wrapper">
                            <h4>Education</h4>
                            <div class="rate">95%</div>

                        </div>
                        <div class="line">
                            <div class="colored-line education"></div>
                        </div>
                    </div>

                    <!-- Single-type-analytic -->
                    <div class="type">
                        <div class="wrapper">
                            <h4>Learning</h4>
                            <div class="rate">65%</div>

                        </div>
                        <div class="line">
                            <div class="colored-line learning"></div>
                        </div>
                    </div>
                    
                    <!-- Single-type-analytic -->
                    <div class="type">
                        <div class="wrapper">
                            <h4>Motivation</h4>
                            <div class="rate">83%</div>

                        </div>
                        <div class="line">
                            <div class="colored-line motivation"></div>
                        </div>
                    </div>
                    

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
    padding-top: 120px;
    padding-bottom: 120px;
    .wrapper{
        display: flex;
        justify-content: space-between;
    }

    .text-col{
        width: 50%;

        p{
            padding: 10px 0;
        }
    }

    .analytics-col{
        width: 50%;
        margin-left: 50px;

        .type{
            padding-bottom: 20px;
        
        }
        
        h4{
            font-size: 20px;
        }

        .rate{
            font-weight: bold;
            font-size: 20px;
        }

        .line{
            width: 530px;
            height: 1px;
            display: inline-block;
            background-color: #e1e1e1;
            

            .colored-line{
                height: 3px;
                background-color: #ff4612;

            }

            .mentorship{
                width: 78%;
            }

            .education{
                width: 93%;
            }

            .learning{
                width: 65%;
            }

            .motivation{
                width: 83%;
            }
        }

    }
}

</style>