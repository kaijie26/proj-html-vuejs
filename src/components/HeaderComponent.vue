<!-- HTML -->
<template>
    <header>
        <div class="wrapper mobile-padding">
            <!-- Logo -->
            <img class="logo" src="../assets/img/logo-img-01.png" alt="logo">
            <!-- Nav-Bar -->
            <nav class="nav-bar">
                <!-- List-Links -->
                <ul class="list-links">
                    <li>
                        <span class="arrow">
                            <i class="fa-solid fa-arrow-right-long"></i>
                        </span>
                    </li>
                    <li v-for="(link, index) in menuLinks" :key="index"  >
                        <a :class="{'current' : link.current ===  true }" class="single-link" :href="link.url">{{link.text}}</a>
                    </li>
                    <li>
                        <span>
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </span>
                    </li>
                    <li>
                        <span>
                            <i class="fa-solid fa-bars"></i>
                        </span>
                    </li>
                </ul>

            </nav>

        </div>

        <div class="header-content mobile-padding">
            <div class="arrow">
                <i class="fa-solid fa-arrow-left-long"></i>
            </div>

            <div class="center-content">
                <!-- Title -->
                <h1>Our Team</h1>
                <div class="point">
                    <i class="fa-solid fa-circle"></i>
                </div>

                <!-- Content-text-->
                <p>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ut sequi quibusdam explicabo deserunt tempore 
                </p>

                <!-- Btn -->
                <div class="btn">
                    <button class="white">
                        <a href="#">READ MORE</a>
                        <span>
                            <i class="fa-solid fa-arrow-right-long"></i>
                        </span>
                    </button>

                    <button class="orange">
                        <a href="#">PURCHASE</a>
                        <span>
                            <i class="fa-solid fa-arrow-right-long"></i>
                        </span>
                        
                    </button>
                </div>

            </div>


            <div class="arrow"> 
                <i class="fa-solid fa-arrow-right-long"></i>
            </div>

        </div>

        
        
        
    </header>
    
</template>


<!-- JAVASCRIPT -->
<script>

export default {
    name:'HeaderComponent',
    props: {
        menuLinks: Array,
    }
}
</script>

<!-- CSS -->
<style lang="scss" scoped>

header{
    background-image: url('../assets/img/rev-slider-main-home-img-03.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;

    .wrapper{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    

    .logo{
        width: 200px;
    }

    .list-links{
        display: flex;

        li{
            padding: 10px;

            .single-link{
                text-decoration: none;
                color: black;
                
            }

            .current{
                color: #ff4612;
            }

            .arrow{
                color: #ff4612;
            }
        }
    }

    .header-content{
        display: flex;
        justify-content: space-between;
        padding-top: 350px;
        padding-bottom: 200px;


        .arrow{
            line-height: 100px;
            cursor: pointer;
        }

        .center-content{
            padding-right: 700px;
        
            p{
                max-width: 350px;
                padding: 10px 0;
            }

            h1{
                font-size: 60px;
                display: inline-block;

            }

            .point{
                font-size: 10px;
                line-height: 30px;
                color: #ff4612;
                display: inline-block;
                
            }

            .btn{
                margin-top: 20px;

                button{
                    padding: 15px 10px;
                    margin-right: 15px;
                    border: none;
                }

                a{
                    margin: 0 20px;
                    text-decoration: none;
                    color: black;
                }

                .white{
                    background-color: white;

                }

                .orange{
                    background-color: #ff4612;
                    color: white;

                    a{
                        color: white;
                    }
                }
            }
        }
    }

    



    
    
    

    
}

</style>