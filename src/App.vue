<template>
  <Header/>
  <Stats/>
  <Courses/>
  <Students/>
  <Process/>
  <Testomonial/>
  <Contact/>
  <Footer/>
</template>


<script>

import Header from "./components/Header"
import Stats from "./components/Stats"
import Courses from "./components/Courses"
import CourseCard from "./components/CourseCard"
import Students from "./components/Students"
import Process from "./components/Process"
import Testomonial from "./components/Testomonial"
import Contact from "./components/Contact"
import Footer from "./components/Footer"
export default {  
  name: 'App',
  components: {
    Header,
    Stats,
    Courses,
    CourseCard,
    Students,
    Process,
    Testomonial,
    Contact,
    Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
*{
  margin: 0;
  padding: 0;
}
</style>
