<template>
   <div id="stat">
        <div>
            <div class="head">Total Students</div>
            <div class="num">5140</div>
            <div class="line"></div>
        </div>
        <div>
            <div class="head">Partners</div>
            <div class="num">4123</div>
            <div class="line"></div>
        </div>
        <div>
            <div class="head">Affiliate Distribution</div>
            <div class="num">4.18 Lac</div>
            <div class="line" id="line3"></div>
        </div>
   </div>
</template>


<script>
export default{
name:"Stats"
}
</script>

<style scoped>
    #stat{
        display: flex;
        justify-content: space-around;
        height:349px;
        align-items: center;
        background: transparent url('img/Group 12141.png') 0% 0% no-repeat padding-box;
    }
    .head{
        width: 10em;
        height: 47px;
        text-align: left;
        font: normal normal bold 2em/1.5em Noto Sans;
        letter-spacing: 0px;
        color: #86919D;
        opacity: 1;
    }
    .num{
        text-align: left;
        font: normal normal bold 3em/1.3em Noto Sans;
        letter-spacing: 0px;
        color: #1F2532;
        opacity: 1;
    }
    .line{
        width:6.2em;
        height: 7px;
        /* UI Properties */
        background: #01CB63 0% 0% no-repeat padding-box;
        opacity: 1;
    }
    #line3{
        width:11.5em;
    }
</style>