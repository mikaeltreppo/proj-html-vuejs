<template>
    <div class="mainFeedbackPart">
        <div class="textGray txt-center mb20">GREAT WORDS ABOUT MAXCOACH</div>
        <div class="txt-center">
            <h2>Our <span class="green"> top learners'</span>verbatim</h2>
        </div>
        <div class="feedbackContainer d-flex">
            <div class="cardsFeedback opacity">
                <div class="textBlue bold mb10"> It's a choise of quality with special needs</div>
                <p class="tetxBlue mb20"> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quasi magnam recusandae
                    quidem, odio vel officiis itaque illo atque quibusdam</p>
                <div class="lowerFeed d-flex">
                    <img class="testimonial" src="../assets/testimonial-avata-03.jpg" alt="">
                    <div class="d-flex d-column mb20">
                        <div class="textBlue mb10">Flhorence Themes</div>
                        <span class="textGray fs12"> / Multimedia Admin</span>
                    </div>

                </div>
            </div>

            <div class="cardsFeedback ">
                <div class="textBlue bold mb10"> It's a choise of quality with special needs</div>
                <p class="tetxBlue mb20"> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quasi magnam recusandae
                    quidem, odio vel officiis itaque illo atque quibusdam</p>
                <div class="lowerFeed d-flex">
                    <img class="testimonial" src="../assets/testimonial-avata-03.jpg" alt="">
                    <div class="d-flex d-column mb20">
                        <div class="textBlue mb10">Flhorence Themes</div>
                        <span class="textGray fs12"> / Multimedia Admin</span>
                    </div>

                </div>
            </div>

            <div class="cardsFeedback opacity">
                <div class="textBlue bold mb10"> It's a choise of quality with special needs</div>
                <p class="tetxBlue mb20"> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quasi magnam recusandae
                    quidem, odio vel officiis itaque illo atque quibusdam</p>
                <div class="lowerFeed d-flex">
                    <img class="testimonial" src="../assets/testimonial-avata-03.jpg" alt="">
                    <div class="d-flex d-column mb20">
                        <div class="textBlue mb10">Flhorence Themes</div>
                        <span class="textGray fs12"> / Multimedia Admin</span>
                    </div>

                </div>
            </div>
        </div>
        <!--get started now section-->
        <div class="d-flex d-column a-c j-c relative">
            <div class="dots d-flex a-c j-c"><i class="fa-solid fa-circle one"></i><i class="fa-solid fa-circle" style="color: #9e9e9e;"></i><i class="fa-solid fa-circle" style="color: #9e9e9e;"></i><i class="fa-solid fa-circle" style="color: #9e9e9e;"></i></div>
            <p class="textBlue bold"> Start today for getting <span class="green">Online Certification</span></p>
            <p><h2 class="textBlue mb20"> You can be your own guiding star with our help!</h2></p>
            <button class="getStartedButton bgGreen"> Get Started now</button>
            <img class="absolute imgGetStartedOne" src="../assets/maxcoach-shape-01.png" alt="">
            <img class="absolute imgGetStartedTwo" src="../assets/maxcoach-shape-02.png" alt="">
        </div>
    </div>
        <!-------------------------------Main statistic part--------------------------------->
        <div class="mainContainer">
        <div class="mainStatisticPart">
     <div class="statisticContainer d-flex ">
        <div class="card d-flex d-column a-c j-c">
            <h2 class="textBlue bold mb20">Succescfully Trained</h2>
            <h1 class="green bold mb20">1790</h1>
            <span class="textGray bold">enrolled courses</span>
        </div>

        <div class="card d-flex d-column a-c j-c">
            <h2 class="textBlue bold mb20">Succescfully Trained</h2>
            <h1 class="green bold mb20">1790</h1>
            <span class="textGray bold">enrolled courses</span>
        </div>

        <div class="card d-flex d-column a-c j-c">
            <h2 class="textBlue bold mb20">Succescfully Trained</h2>
            <h1 class="green bold mb20">1790</h1>
            <span class="textGray bold">enrolled courses</span>
        </div>

        <div class="card d-flex d-column a-c j-c">
            <h2 class="textBlue bold mb20">Succescfully Trained</h2>
            <h1 class="green bold mb20">1790</h1>
            <span class="textGray bold">enrolled courses</span>
        </div>
     </div>
            </div>
        </div>
        <!-------------------------------Main blog part--------------------------------->
        <div class="mainBlogPart">
           
        </div>
    
</template>
<script></script>
<style>
.card{
    width: calc(100% /4);
    padding: 50px 30px;
    text-align: center;
    border: 1px solid rgb(241, 240, 240);
}
.dots{
    padding: 40px;
}
.dots i{
    margin: 5px;
font-size: 6px;
filter: opacity(0.4);
}
.dots i.one{
    font-size: 10px;
}
 .imgGetStartedTwo{
    width: 80px;
top: 142px;
right: 197px;

 }
 .imgGetStartedOne{
    width: 80px;
top: 136px;
left: 272px;


 }
.getStartedButton{
color: white;
padding: 10px 30px;
border-radius: 5px;
margin-bottom: 50px;
}
.testimonial {
    border-radius: 50%;
    height: 50px;

}

.cardsFeedback {
    margin: 40px 0;
    padding: 0 40px 0 40px;
    width: calc(100% / 3);
    border: solid 1px rgb(247, 242, 242);
}

.mainFeedbackPart {
    background-color: var(--bgGray);
    padding: 40px 0;
}



.mainBlogPart {
    height: 300px;
    background-color:rgb(245, 241, 237);
}</style>