<template>
   
    <div class="mainContainer">
        <div class="footerTop">
            <div class="footer d-flex a-c j-c d-column">
                <span class="mb20 textBlue">Subscribe <span class="green">Newsletter</span></span>
                <p class="ptop mb20">Enter your emad address to register to our newsletter Subscription <br>
                    delivered on a regdar basis!</p>
                <div><input class="inputEmail" type="text" name="" id="" placeholder="Enter your email"><a href="#"><button
                            class="buttonSubscribe bgGreen">Subscribe</button></a> </div>
            </div>
        </div>
     </div>
        <div class="totalContainerCourses">
            <div class="mainContainer">
        <div class="footerBottom d-flex">
            <div class="columnFooter">
                <span> {{ titleone }}</span>
                <ul>
                    <li class="textGray sm">382 NE 191st St # 87394 Miami, FL 33179-3899</li>
                    <li class="textGray sm">+1 (305) 547-9909 (9am - sprn EST. Monday - Friday)</li>
                    <li class="mb20 textGray sm">support@rnaxcoachcorn</li>
                    <li class="textGray sm"><i class="fa-brands fa-instagram"></i><i class="fa-brands fa-facebook"></i><i class="fa-brands fa-pinterest"></i><i class="fa-brands fa-youtube"></i></li>
                </ul>
            </div>
            <div class="columnFooter d-flex">
                <div class="miniColumnFooter">{{ titletwo }}
                    <ul>
                        <li class="textGray sm">Start Here</li>
                        <li class="textGray sm">Blog us</li>
                        <li class="textGray sm">About us</li>
                    </ul>
                </div>
                <div class="miniColumnFooter">
                    <span class="trsp">titolotrasparente</span>
                    <ul>
                        <li class="textGray sm">succes story</li>
                        <li class="textGray sm">Courses</li>
                        <li class="textGray sm">contact us</li>
                    </ul>

                </div>
                <div class="miniColumnFooter">{{ titlethree }}
                <ul>
                    <li class="textGray sm">Membership</li>
                    <li class="textGray sm">Purchase guide</li>
                    <li class="textGray sm">Pricacy policy</li>
                    <li class="textGray sm">Terms of service</li>
                </ul></div>
            </div>
        </div>

        </div></div>
   
</template>
<script>
export default {
    name: 'MyFooter',
    props: {
        titleone: String,
        titletwo: String,
        titlethree: String

    }

}


</script>
<style>
i{
    margin-right: 10px;

}
.miniColumnFooter {
    width: calc(100% / 3);
}

.columnFooter {
    width: calc(100% / 2);
}

.ptop {
    text-align: center;
}

.inputEmail {
    height: 33px;
    margin-right: -10px;
}

.buttonSubscribe {
    padding: 5px 20px;
    color: white;
    border-radius: 5px;
}

.footerTop {
  
    padding: 40px 0;
}

.footerBottom {
   padding: 40px 0;
}
.totalContainerCourses{
    background-color:rgb(248, 248, 248)}

</style>