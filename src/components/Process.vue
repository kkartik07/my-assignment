<template >
        <div id="head1">Refer</div>
        <div id="head2">How it's Work</div>
        <img id="roadmap" src="/Group 12142.png" alt="img" />
        <hr id="cut"/>
</template>




<script>
export default{
name:"Process",
}
</script>

<style scoped>
#cut{
    color:#ffffff;
    height: 0px;
}
    #head1{
        width: 57px;
        height: 34px;
        text-align: left;
        font: normal normal normal 25px/34px Noto Sans;
        letter-spacing: 0px;
        color: #01CB63;
        margin-left: 80px;
    }
    #head2{
        width: 278px;
        height: 55px;
        /* UI Properties */
        text-align: left;
        margin-left: 80px;
        font: normal normal bold 40px/54px Noto Sans;
        letter-spacing: 0px;
        color: #1F2532;
        text-transform: capitalize;
    }
    #roadmap{
        height: 726px;
        width:90%;
        float: left;
        margin-right: 10%;
    }
</style>