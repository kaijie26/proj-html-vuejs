<!-- HTML -->
<template>
    <section>
        <div class="content-container">
            <!-- Table-Events -->
            <div class="table-events">
                <div class="section-title">
                    <h3>Upcoming events</h3>
                </div>
                <!-- Single-Event-clicked -->
                <div class="single-event">
                    <!-- Square data -->
                    <div class="square">
                        <div class="day text-center"> 
                            07
                        </div>

                        <div class="mm-yy text-center">
                            Jan.2022
                        </div>

                    </div>

                    <!-- Info Event  -->
                    <div class="info-event">
                        <h4>
                            Melbourne Coaching
                        </h4>

                        <div class="clock">
                            <i class="fa-regular fa-clock"></i>
                            <span>9:00 am - 5:00 p, Jan 7, 2022</span>
                        </div>

                        <div class="location">
                            <i class="fa fa-map-marker" aria-hidden="true"></i>
                           <span> Cambridge, MA 0213, USA</span>
                        </div>

                        <div class="more-info">READ MORE</div>

                    </div>

                </div>

                <!-- Single-Event-default -->
                <div class="single-event default">
                    <!-- Square data -->
                    <div class="square">
                        <div class="day text-center"> 
                            11
                        </div>

                        <div class="mm-yy text-center">
                            Jan.2022
                        </div>

                    </div>

                    <!-- Info Event  -->
                    <div class="info-event">
                        <h4>
                            New York Coaching
                        </h4>

                        <div class="clock">
                            <i class="fa-regular fa-clock"></i>
                            <span>9:00 am - 5:00 p, Jan 11, 2022</span>
                        </div>

                        <div class="location">
                            <i class="fa fa-map-marker" aria-hidden="true"></i>
                           <span> Cambridge, MA 0213, USA</span>
                        </div>

                        <div class="more-info">READ MORE</div>

                    </div>

                </div>

                <!-- Single-Event-default -->
                <div class="single-event default">
                    <!-- Square data -->
                    <div class="square">
                        <div class="day text-center"> 
                            21
                        </div>

                        <div class="mm-yy text-center">
                            Jan.2022
                        </div>

                    </div>

                    <!-- Info Event  -->
                    <div class="info-event">
                        <h4>
                            Melbourne Coaching
                        </h4>

                        <div class="clock">
                            <i class="fa-regular fa-clock"></i>
                            <span>9:00 am - 5:00 p, Jan 21, 2022</span>
                        </div>

                        <div class="location">
                            <i class="fa fa-map-marker" aria-hidden="true"></i>
                           <span> Cambridge, MA 0213, USA</span>
                        </div>

                        <div class="more-info">READ MORE</div>

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
    background-image: url('../assets/img/h1-img-09.jpg');
    background-repeat: no-repeat;
    background-position: center;
    padding-top: 120px;
    padding-bottom: 120px;

    .table-events{
        max-width: 450px;
        background-color: white;

        .section-title{
            padding-top: 20px;
            padding-bottom: 30px;
            padding-left: 40px;
            background-color: #fafafa;
            box-shadow: 0 7px #f4f4f4;
        }

        h3{
            font-size: 35px;
        }

        .single-event{
            padding: 30px;
            display: flex;

            .square{
                width: 80px;
                height: 60px;
                background-color: #ff4612;
                padding: 10px;

                .day{
                    font-size: 20px;
                    color: white;
                }

                .mm-yy{
                    color: #f4f4f4;
                }

            }

            .info-event{
                padding-left: 20px;

                h4{
                    font-size: 23px;
                }
                
                span{
                    padding-left: 10px;
                    margin: 10px 0;
                }

                .clock{
                    padding-top: 10px;
                    padding-bottom: 5px;

                    i{
                        color: #ff4612;

                    }
                }

                .location{
                    padding-top: 5px;
                    padding-bottom: 10px;

                    i{
                        color: #ff4612;

                    }
                }

                .more-info{
                    font-size: 13px;
                    font-weight: bold;
                }
   
            }
            

        }

        .default{
            background-color: #fafafa ;
            border-top: 3px solid #f4f4f4;
        }

    }

}

</style> 