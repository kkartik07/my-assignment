<template >
         <div id="head1">Top Earners</div>            
         <div id="head2">Transforming your ideas into reality</div> 
         <div id="container">
             <div>
                 <div class="pic" id="pic1"></div>
                 <div class="salary"><div class="green"></div><div>₹6,00,000</div></div>
            </div>          
             
             <div>
                 <div class="pic" id="pic2"></div>
                 <div class="salary"><div class="green"></div><div>₹6,00,000</div></div>
            </div>          
             
             <div>
                 <div class="pic" id="pic3"></div>
                 <div class="salary">
                    <div class="green"></div>
                    <div>₹6,00,000</div>
                </div>

            </div>          
             
             <div>
                 <div class="pic" id="pic4"></div>
                 <div class="salary"><div class="green"></div><div>₹6,00,000</div></div>
            </div>          
        </div> 
</template>
 
 
 <script>
 export default{
 name:"Students",
 }
 </script>
 
 <style scoped>
    #container{
        display: flex;
        justify-content: space-around;
        margin-left: 45px;
        margin-right: 45px;
        margin-bottom: 120px;
    }
    #head1{
        width: 131px;
        height: 34px;
        /* UI Properties */
        text-align: left;
        font: normal normal normal 25px/34px Noto Sans;
        letter-spacing: 0px;
        color: #01CB63;
        margin-left: 4.5rem
    }
    #head2{
        width: 490px;
        height: 109px;
        /* UI Properties */
        text-align: left;
        font: normal normal bold 40px/54px Noto Sans;
        letter-spacing: 0px;
        color: #1F2532;
        text-transform: capitalize;
        margin-left: 4.5rem;
        margin-bottom: 40px;
    }
    .pic{
        width: 300px;
        height: 300px;
        /* UI Properties */
        border-radius: 5px;
        opacity: 1;
    }
    #pic1{
        background: transparent url('img/luis-villasmil-hh3ViD0r0Rc-unsplash.png') 0% 0% no-repeat padding-box;
    }
    #pic2{
        background: transparent url('img/craig-mckay-jmURdhtm7Ng-unsplash.png') 0% 0% no-repeat padding-box;
    }
    #pic3{
        background: transparent url('img/christopher-campbell-rDEOVtE7vOs-unsplash.png') 0% 0% no-repeat padding-box;
    }
    #pic4{
        background: transparent url('img/jonas-kakaroto-mjRwhvqEC0U-unsplash.png') 0% 0% no-repeat padding-box;
    }
    .green{
        display:inline-block;
        width: 10px;
        height: 60px;
        background-color: #01CB63;
        margin-right: 10px;
        /* UI Properties */
        /* background: transparent url('img/Rectangle 1989.png') 0% 0% no-repeat padding-box; */
    }
    .salary{
        height: 34px;
        /* UI Properties */
        text-align: left;
        font: normal normal bold 25px/35px Noto Sans;
        letter-spacing: 0px;
        color: #1F2532;
        display: flex;
        align-items: center;
        margin-top: 1em;
    }
 </style>