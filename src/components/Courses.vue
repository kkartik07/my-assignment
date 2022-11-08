<template>
    <div id="container">
        <div id="courses">Courses</div>
        <div id="morecourse">Our most popular courses</div>
        <div id="coursecontainer">
            <CourseCard instructor="Albert Hitler" image="img/carla-oliveira-21FqSKZQGzI-unsplash.jpg" students="46995" duration="11 hr 20 mins" coursename="Ultimate Business Intelligence Analyst A to Z Course 2021" lectures="44"/>
            <CourseCard instructor="Wanda Willson" image="img/woodwatch-5fiibEXMHRI-unsplash.jpg" students="6995" duration="6 hr 20 mins" coursename="Adobe Photoshop Training: From Beginner to Pro" lectures="24"/>
            <CourseCard instructor="Albert Hitler" image="img/hunters-race-hNoSCxPWYII-unsplash.jpg" students="46995" duration="11 hr 20 mins" coursename="Social Media Marketing - A to Z Content Marketing class 2021" lectures="44"/>
        </div>
        <div id="blank"></div>
    </div>
 </template>
 
 
 <script>
 import CourseCard from './CourseCard.vue'

 export default{
 name:"Courses",
 components:{
    CourseCard
 }
 }
 </script>
 
 <style scoped>
   #coursecontainer{
        display: flex;
        justify-content: space-around;
        margin-left: 5em;
        margin-right: 5em;
        margin-top: 20px;
    }
 hr {
  width: 25em;
  margin-left: 0;
  height:1px;
  background-color: #86919d07;
}
 #container{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    
 }
 #courses{
    width: 88px;
    height: 34px;
    /* UI Properties */
    text-align: center;
    font: normal normal normal 25px/34px Noto Sans;
    letter-spacing: 0px;
    color: #01CB63;
    opacity: 1;
    margin-top: 60px;
    margin-bottom: 20px;
 }
 #morecourse{
    /* UI Properties */
text-align: center;
font: normal normal bold 40px/54px Noto Sans;
letter-spacing: 0px;
color: #1F2532;
text-transform: capitalize;
opacity: 1;
 }
 #blank{
    height:300px;
 }
   
 </style>