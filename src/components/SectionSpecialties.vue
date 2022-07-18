<!-- HTML -->
<template>
    <section>
        <div class="container content-bg">
            <!-- Section-Tilte -->
            <div class="text-center">
                <h2>Our specialties</h2>
                <div class="subtitle-point">
                    <i class="fa-solid fa-circle"></i>
                </div>
                <div>Lorem ipsum dolor sit amet, consectetur adipiscing elit </div>
                <div class="center-line"></div>
            </div>

            <!-- Specialties -->
            <div class="specialties text-center">
                <!-- Single-Specialtie -->
                <div class="single-specialtie">
                    <img src="../assets/svg/svg-0.svg" alt="">
                    <h4>Knowing</h4>
                    <div>Lorem ipsum dolor sit amet, <br> quis consect.</div>

                </div>
                <!-- Single-Specialtie -->
                <div class="single-specialtie">
                    <img src="../assets/svg/svg-1.svg" alt="">
                    <h4>Selling</h4>
                    <div>Lorem ipsum dolor sit amet, quis <br> consect.</div>

                </div>
                <!-- Single-Specialtie -->
                <div class="single-specialtie">
                    <img src="../assets/svg/svg-2.svg" alt="">
                    <h4>Learning</h4>
                    <div>Lorem ipsum dolor sit amet, quis <br> consect.</div>

                </div>
                <!-- Single-Specialtie -->
                <div class="single-specialtie">
                    <img src="../assets/svg/svg-3.svg" alt="">
                    <h4>Contact</h4>
                    <div>Lorem ipsum dolor sit amet, <br> quis consect.</div>

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
    background-color: #fafafa;

    .content-bg{
        background-color: white;
        padding: 70px;
        position: relative;
        bottom: 120px;

        .specialties{

            .single-specialtie{
                width: calc(100% / 4);
                padding: 0px 10px;
                display: inline-block;

                h4{
                    font-size: 20px;
                    margin: 10px 0;
                }

            }

        }
    }

    
}


</style>