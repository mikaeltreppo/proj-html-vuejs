<template>
    <div class="headerTop d-flex">
        <img class="logo" src="../assets/dark-logo.png" alt="">
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
    <div class="mainContainer">
        <div class="headerBottom">
            <h1>header bottom</h1>
        </div>
    </div>
</template>

<script></script>

<style>
.headerTop {
    height: 40px;
    background-color: pink;
    padding: 10px;
}

.headerBottom {
    height: 400px;
    background-color: rgb(82, 82, 125);
}

.logo {
    height: 20px;
    margin-left: 10%;
    margin-right: 200px;
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
input{
    margin-left: 20px;
}
</style>