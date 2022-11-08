<template >
    <div class="course">
                <div class="pic" id="course1"></div>
                <div>
                    <div class="txt">{{coursename}}</div>
                        <div id="students"><b>{{students}}</b> Student</div>
                        <div class="time">
                            <div class="duration"><div id="clock"></div>{{duration}}</div>
                            <div class="duration"><div id="calender"></div> {{lectures}} Lectures</div>
                        </div>
                        <hr>
                    <div class="instructor">
                        <div>
                            <div id="instructor"><div id="profile"></div><span id="teacher">{{instructor}}</span>
                            <div id="cost">₹2000<span id="cut">2000</span></div>
                        </div>
                        </div>
                    </div>
                    </div>
    </div>
            
</template>
 
 
 <script>
 export default{
 name:"CourseCard",
 props: ['coursename','lectures','duration','students','instructor','image']
 }
 </script>
 
 <style scoped>
 #cost{
    margin-left: 130px;
    width: 58px;
    height: 27px;
    /* UI Properties */
    text-align: left;
    font: normal normal bold 20px/27px Noto Sans;
    letter-spacing: 0.2px;
    color: #01CB63;
 }
  #cut{
    height: 19px;
    /* UI Properties */
    text-align: left;
    text-decoration: line-through;
    font: normal normal bold 14px/19px Noto Sans;
    letter-spacing: 0.14px;
    color: #1F2532;
  }
    .course{
        height: 300px;
        flex:0.3;
        background: transparent url("img/wes-hicks-4-EeTnaC1S4-unsplash.jpg") 0% 0% no-repeat padding-box;
        border-radius: 15px 15px 0px 0px;
        opacity: 1;
        display: flex;
        flex-direction: column;

    }
    #profile{
        width: 50px;
        height: 50px;
        border-radius: 50%;
        margin-right: 7px;
        /* UI Properties */
        background: transparent url('img/carla-oliveira-21FqSKZQGzI-unsplash.jpg') 0% 0% no-repeat padding-box;
        opacity: 1;
    }
    #teacher{
        height: 27px;
/* UI Properties */
text-align: left;
font: normal normal bold 20px/27px Noto Sans;
letter-spacing: 0px;
color: #1F2532;
    }
    .pic{
        flex:0.5;
    }
    .txt{
        margin-top: 320px;
        flex:0.5;
        height: 68px;
        text-align: left;
        font: normal normal bold 25px/34px Noto Sans;
        letter-spacing: 0px;
        color: #1F2532;
        display: flex;
    }
    .time{
        margin-top: 15px;
        display: flex;
        justify-content: space-between;
    }
    .duration{
        display: flex;
        align-items: center;
    }
    #students{
        height: 22px;
        text-align: left;
        letter-spacing: 0px;
        color: #1F2532;
        opacity: 1;
        margin-top: 20px;
    }
    #clock{
        width: 24px;
        height: 24px;
        /* UI Properties */
        background: transparent url('img/schedule-24px.png') 0% 0% no-repeat padding-box;
        opacity: 1;
    }
    #calender{
        width: 18px;
        height: 20px;
        /* UI Properties */
        background: transparent url('img/date_range-24px.svg') 0% 0% no-repeat padding-box;
    }
    #instructor{
        display: flex;
        align-items: center;
    }
 </style>