<!-- HTML -->
<template>
    <section>
        <div class="wrapper">
            <!-- Arrow-Left -->
            <div class="arrow">
                <i class="fa-solid fa-arrow-left-long"></i>
            </div>

            <div class="content-container">
                <!-- Section-Title -->
                <div class="text-center">
                    <h2>Latest news</h2>
                    <div class="subtitle-point">
                        <i class="fa-solid fa-circle"></i>
                    </div>
                    <div>Lorem ipsum dolor sit amet, consectetur adipiscing elit</div>
                    <div class="center-line"></div>
                </div>

                <!-- Columns -->
                <div class="columns">
                    <!-- Col -->
                    <div class="col space-left">
                        <!-- Poster -->
                        <div class="poster">
                            <img src="../assets/img/h1-blog-img-02.jpg" alt="">
                            <!-- Info-Author -->
                            <div class="info-author">
                                <span class="icon">
                                    <i class="fa-regular fa-clock"></i>
                                </span>
                                <span>
                                    May 5, 2019
                                </span>
                                <span class="icon">
                                    <i class="far fa-user"></i>
                                </span>
                                <span>
                                    Amanda Doe
                                </span>

                            </div>

                            <!-- Label -->
                            <div class="label">
                               <i class="fa-solid fa-tag"></i>
                                Business, Leading
                            </div>
                            
                        </div>

                        <!-- Col-Content -->
                        <div class="col-content">
                            <h3>Next Investment</h3>
                            <div>
                                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fuga a perspiciatis voluptates esse 
                            </div>
                            <div class="more-info">READ MORE</div>
                        </div>
                        
                    </div>

                    <!-- Col -->
                    <div class="col space-center">
                        <!-- Poster -->
                        <div class="poster">
                            <img src="../assets/img/h1-blog-img-03.jpg" alt="">
                            <!-- Info-Author -->
                            <div class="info-author">
                                <span class="icon">
                                    <i class="fa-regular fa-clock"></i>
                                </span>
                                <span>
                                    May 5, 2019
                                </span>

                                <span class="icon">
                                    <i class="far fa-user"></i>
                                </span>
                                <span>
                                    Amanda Doe
                                </span>

                            </div>

                            <!-- Label -->
                            <div class="label">
                                <i class="fa-solid fa-tag"></i>
                                Business, Leading
                            </div>

                        </div>

                        <!-- Col-Content -->
                        <div class="col-content">
                            <h3>Team Building</h3>
                            <div>
                                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fuga a perspiciatis voluptates esse 
                            </div>
                            <div class="more-info">READ MORE</div>
                        </div>


                        
                    </div>

                    <!-- Col -->
                    <div class="col space-right">
                        <!-- Poster -->
                        <div class="poster">
                            <img src="../assets/img/h1-blog-img-04.jpg" alt="">
                            <!-- Info-Author -->
                            <div class="info-author">
                                <span class="icon">
                                    <i class="fa-regular fa-clock"></i>
                                </span>
                                <span>
                                    May 5, 2019
                                </span>

                                <span class="icon">
                                    <i class="far fa-user"></i>
                                </span>
                                <span>
                                    Amanda Doe
                                </span>

                            </div>

                            <!-- Label -->
                            <div class="label">
                                <i class="fa-solid fa-tag"></i>
                                Business, Leading
                            </div>
                            
                        </div>

                        <!-- Col-Content -->
                        <div class="col-content">
                            <h3>New Business Day</h3>
                            <div>
                                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fuga a perspiciatis voluptates esse 
                            </div>
                            <div class="more-info">READ MORE</div>
                        </div>
                        
                    </div>

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
    background-color: #fafafa;
    padding: 120px 50px;

    .wrapper{
        display: flex;
        align-items: center;
    }

    .columns{
        display: flex;
        padding-top: 30px
    }

    .col{
        width: calc(100% / 3);

        .poster{
            position: relative;
        }

        .info-author{
            padding-top: 30px;

            .icon{
                color: #ff4612;
            }

        }
        
        img{
            width: 100%;
        }

        .label{
            background-color: #ff4612;
            width: 150px;
            font-size: 14px;
            padding: 10px;
            position: absolute;
            bottom: 15%;
            right: 5%;
            color: #f4f4f4;
        }

        
    }

    .space-left{
        margin-left: -2rem;
    }

    .space-right{
        margin-right: -2rem;
    }

    .space-center{
        margin: 0 2rem;
    }

    .col-content{

        h3{
            padding: 10px 0;
            font-size: 30px;

        }

        .more-info{
            font-weight: bold;
            padding-top: 10px;
        }
    }

}

</style>