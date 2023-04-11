<template>
    <div class="totalContainerCourses">
    <div class="mainContainer">
        <div class="mainCoursesPart">
            <div class="intro d-flex d-column a-c j-c">
                <span>STIMULATED TO LEARN?</span>
                <h2>Featured Online Courses</h2>
            </div>
            <div class="cardCourses d-flex wrap">
                <!--course card-->
                <div class="course d-flex">
                    <div class="courseLeft">
                        <img class="courseImg" src="../assets/course-02-480x298.jpg" alt="">
                    </div>
                    <div class="courseRight d-flex d-column a-c j-c">
                        <h3 class="price green">£40</h3>
                        <span>Learning to Write as a Professional
                            Author</span>
                        <span>20 lessons</span>
                        <span>50 students</span>
                    </div>
                </div>

                <div class="course d-flex">
                    <div class="courseLeft">
                        <img class="courseImg" src="../assets/course-02-480x298.jpg" alt="">
                    </div>
                    <div class="courseRight d-flex d-column a-c j-c">
                        <h3 class="price green">£40</h3>
                        <span>Learning to Write as a Professional
                            Author</span>
                        <span>20 lessons</span>
                        <span>50 students</span>
                    </div>
                </div>

                <div class="course d-flex">
                    <div class="courseLeft">
                        <img class="courseImg" src="../assets/course-02-480x298.jpg" alt="">
                    </div>
                    <div class="courseRight d-flex d-column a-c j-c">
                        <h3 class="price green">£40</h3>
                        <span>Learning to Write as a Professional
                            Author</span>
                        <span>20 lessons</span>
                        <span>50 students</span>
                    </div>
                </div>

                <div class="course d-flex">
                    <div class="courseLeft">
                        <img class="courseImg" src="../assets/course-02-480x298.jpg" alt="">
                    </div>
                    <div class="courseRight d-flex d-column a-c j-c">
                        <h3 class="price green">£40</h3>
                        <span>Learning to Write as a Professional
                            Author</span>
                        <span>20 lessons</span>
                        <span>50 students</span>
                    </div>
                </div>

                <div class="course d-flex">
                    <div class="courseLeft">
                        <img class="courseImg" src="../assets/course-02-480x298.jpg" alt="">
                    </div>
                    <div class="courseRight d-flex d-column a-c j-c">
                        <h3 class="price green">£40</h3>
                        <span>Learning to Write as a Professional
                            Author</span>
                        <span>20 lessons</span>
                        <span>50 students</span>
                    </div>
                </div>

                <div class="course d-flex">
                    <div class="courseLeft">
                        <img class="courseImg" src="../assets/course-02-480x298.jpg" alt="">
                    </div>
                    <div class="courseRight d-flex d-column a-c j-c">
                        <h3 class="price green">£40</h3>
                        <span>Learning to Write as a Professional
                            Author</span>
                        <span>20 lessons</span>
                        <span>50 students</span>
                    </div>
                </div>
            </div>
        </div>
        </div>
        <div class="mainTutoringPart">
            <h1>main tutoring part</h1>
        </div>
        <div class="mainFeedbackPart">
            <h1>main feedback part</h1>
        </div>
        <div class="mainStatisticPart">
            <h1>main statistic part</h1>
        </div>
        <div class="mainBlogPart">
            <h1>main blog part</h1>
        </div>
    </div>
</template>

<script>

</script>

<style scoped>
.mainContainer{
    padding: 30px 0;
}
.totalContainerCourses{
    background-color: var(--bgDeepGray);
}
/*setup card*/

.course{
    width: calc(100% / 2);
    padding: 15px;
}
.courseImg {
    display: inline;
    margin: 0 auto;
    margin-left: -25%;
    height: 100%;
    width: auto;
}

.courseLeft {
    width: 150px;
    height: 150px;
    position: relative;
    overflow: hidden;
    border-radius: 50%;
}



.mainTutoringPart {
    height: 450px;
    background-color: rgb(169, 196, 130);
}

.mainFeedbackPart {
    height: 450px;
    background-color: rgb(197, 197, 132);
}

.mainStatisticPart {
    height: 200px;
    background-color: rgb(197, 129, 129);
}

.mainBlogPart {
    height: 300px;
    background-color: rgb(165, 188, 124);
}
</style>