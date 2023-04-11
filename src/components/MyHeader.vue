<template>
    <div class="headerTop d-flex s-b">
        <!--parte sinistra header top-->
        <div class="leftPartTopHeader">
            <img class="logo" src="../assets/dark-logo.png" alt="">
        </div>
        <!--parte destra header top-->
        <div class="rigthPartHeaderTop d-flex">
            <ul class="listTopHeader d-flex">
                <li> Home <i class="fa-solid fa-chevron-down"></i></li>
                <li>Pages <i class="fa-solid fa-chevron-down"></i></li>
                <li>Courses <i class="fa-solid fa-chevron-down"></i></li>
                <li>Features <i class="fa-solid fa-chevron-down"></i></li>
                <li>Blog <i class="fa-solid fa-chevron-down"></i></li>
                <li>Shop <i class="fa-solid fa-chevron-down"></i></li>
            </ul>
            <!--profile button-->
            <i class="fa-regular fa-circle-user"></i>
            <!--search bar-->
            <input type="search" placeholder="Search">
        </div>

    </div>
    <!--header bottom-->
    <div class="mainContainer">
        <div class="headerBottom">
            <div class="hero d-flex">
                <!--header left-->
                <div class="heroLeft d-flex d-column">
                    <h2>Distant learning for
                        further expansion</h2>
                    <p>Learning is a life-long journey that in fact we never find
                        the terminate stop. Stop searching, enjoy the</p>
                    <button>
                        Download the free guide
                    </button>
                    <span class="">
                        Have questions? <a class="green" href="#"> Get Free Sample <i
                                class="fa-solid fa-arrow-right fa-xs"></i> </a>
                    </span>
                </div>
                <!--header rigth-->
                <div class="heroRigth d-flex">
                    <img class="bgImg one" src="../assets/maxcoach-shape-08.png" alt="">
                    <img class="bgImg two" src="../assets/maxcoach-shape-08.png" alt="">
                    <img class="bgImg three" src="../assets/maxcoach-shape-07-150x150.png" alt="">ù
                    <img class="bgImg four" src="../assets/maxcoach-shape-02.png" alt="">
                    <img class="aboutMeImg" src="../assets/about-me-profile-ohm4dxoearqbxny7q3bq1pzbdgofdx0tobbeqcvzd0.jpg"
                        alt="">
                </div>
            </div>
            <div class="partnerLogo d-flex s-b a-c">
                <img class="clientLogo one" src="../assets/client-logo-01.png" alt="">
                <img class="clientLogo two" src="../assets/client-logo-02.png" alt="">
                <img class="clientLogo three" src="../assets/client-logo-03.png" alt="">
                <img class="clientLogo four" src="../assets/client-logo-04.png" alt="">
                <img class="clientLogo five" src="../assets/client-logo-05.png" alt="">
                <img class="clientLogo six" src="../assets/client-logo-06.png" alt="">
            </div>
        </div>
    </div>
</template>

<script></script>

<style>
.bgImg.one {
    position: absolute;
    top: 115px;
    left: 65px;
    height: 90px;
}

.bgImg.two {
    position: absolute;
    top: 215px;
    left: 65px;
    height: 90px;
}

.bgImg.three {
    position: absolute;
    top: 307px;
    right: 56px;
    height: 90px;
}

.bgImg.four {
    height: 70px;
    position: absolute;
    right: -58px;
    top: 68px;
}

.partnerLogo {
    filter: opacity(0.8);
    padding: 20px 0;
}

.clientLogo {
    height: 35px;
}

.clientLogo.two {
    height: 50px;
}

.clientLogo.six {
    height: 20px;
}

.heroLeft {
    width: 40%;
    justify-content: center;
}

.heroRigth {
    position: relative;
    justify-content: flex-end;
    align-items: center;
    width: 60%;
}

.aboutMeImg {
    height: 400px;
    border-radius: 50%;
    z-index: 9999;
}

.headerTop {
    padding: 10px 15%;
    border-bottom: 2px solid rgb(244, 244, 244);
}

.headerBottom {
    padding: 30px 0;

}

.logo {
    height: 20px;
    color: var(--blueWrite);
}

.listTopHeader li {
    list-style: none;
    margin-right: 20px;
}

.listTopHeader li i {
    font-size: 8px;
    margin-bottom: 10px;
}

input {
    margin-left: 20px;
}</style>