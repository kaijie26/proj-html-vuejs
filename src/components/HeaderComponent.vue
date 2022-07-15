<!-- HTML -->
<template>
    <header>
        <div class="wrapper">
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
    // TEST
    height: 1000px;

    .wrapper{
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 20px 10px;
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

    
    
    

    
}

</style>