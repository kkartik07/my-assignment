<template >
    <div id="heads">
        <div id="head1">Testimonials</div>
        <div id="head2">Check out What Our Students Think About Us</div>
    </div>

    <div id="container">
        <div class="card">
            <div class="txt">It's a comprehensive online learning platform for everyone looking to learn and course pro. provinding this platform which is very beneficial for practicals. Students can revise everything at home like dissection and slides</div>
            <div class="person">
                <img src="./img/person.png"/>
                <div>
                    <div class="name">Anshul Jain</div>
                    <div>Yesterday</div>
                </div>
                <img src="./img/right-quotation-sign.svg" class="quote"/>
            </div>
        </div>
        <div class="card">
            <div class="txt">It's A Comprehensive Online Learning Platform For Everyone Looking To Learn And Course Pro. Provinding This Platform Which Is Very Beneficial For Practicals. Students Can Revise Everything At Home Like Dissection And Slides</div>
            <div class="person">
                <img src="./img/person.png"/>
                <div>
                    <div class="name">Anshul Jain</div>
                    <div class="time">Yesterday</div>
                </div>
                <img src="./img/right-quotation-sign.svg" class="quote"/>
            </div>
        </div>
    </div>

    <div id="heads2">
        <div id="head3">Contact Us</div>
        <div id="head4">Reach Out with any question you have</div>
    </div>
</template>


<script>
export default{
name:"Testomonial",
}
</script>

<style scoped>
#heads{
    margin-left: 4%;
    margin-top: 70px;
}
#heads2{
    margin-top: 100px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
    #head1{
        width: 137px;
        height: 34px;
        /* UI Properties */
        text-align: left;
        font: normal normal normal 25px/34px Noto Sans;
        letter-spacing: 0px;
        color: #01CB63;
    }
    #head2{
        width: 494px;
        height: 109px;
        /* UI Properties */
        text-align: left;
        font: normal normal bold 40px/54px Noto Sans;
        letter-spacing: 0px;
        color: #1F2532;
        text-transform: capitalize;
    }
    #container{
        margin-top: 30px;
        display: flex;
        justify-content: space-around;
        margin-left: 5%;
        margin-right: 5%;
    }
    #head3{
        height: 34px;
        /* UI Properties */
        text-align: left;
        font: normal normal normal 25px/34px Noto Sans;
        letter-spacing: 0px;
        color: #01CB63;
    }
    #head4{
        height: 109px;
        width:410px;
        /* UI Properties */
        text-align: center;
        font: normal normal bold 40px/54px Noto Sans;
        letter-spacing: 0px;
        color: #1F2532;
        text-transform: capitalize;
        opacity: 1;
    }
    .txt{
        text-align: left;
        font: normal normal normal 23px/35px Noto Sans;
        letter-spacing: 0px;
        color: #000000;
        text-transform: capitalize;
        opacity: 0.7;
    }
    .name{
        height: 24px;
        /* UI Properties */
        text-align: left;
        font: normal normal bold 18px/24px Noto Sans;
        letter-spacing: 0px;
        color: #10182F;
    }
    .time{
        height: 22px;
        /* UI Properties */
        text-align: left;
        font: normal normal normal 16px/22px Noto Sans;
        letter-spacing: 0px;
        color: #545D7A;
    }
    .card{
        width: 40%;
        /* UI Properties */
        background: #FFFFFF 0% 0% no-repeat padding-box;
        box-shadow: 0px 20px 30px #1F25321A;
        border-radius: 15px;
        display: flex;
        padding: 3em 3em 0 3em;
        flex-direction: column;
    }
    .person{
        display: flex;
        margin-top: 35px;
        margin-bottom: 20px;
    }
    .quote{
        width: 45px;
height: 36px;
opacity: 0.5;
float: right;
margin-left: 250px;
    }
</style>