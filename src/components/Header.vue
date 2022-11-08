<template>
        <div id="header">
            <div class="up">
                <div id="logo"></div>
                <button id="login">Login</button>
                <button id="register">Register</button>
            </div>
            <div id="banner">
                <div id="bannertxt">
                    <div id="text">
                        <div>
                            <div id="t1">AnyTime, anywhere Learn on your schedule from any device</div>
                            <div id="t2">We Believe everyone has the capcity to be creative Course Pro is a place where people develop their own potential</div>
                            <button id="btn">Let's Get Start</button>
                        </div>
                    </div>
                </div>
                <img id="bannerimg" src="/jeshoots-com--2vD8lIhdnw-unsplash.jpg"/>
            </div>
        </div>
</template>


<script>
export default{
    name:"Navbar"
}
</script>

<style scoped>
   
    #Header{
       height: 893px;
       background-color:#01CB63;
    }
    .up{
        height: 20px;
        background: #FFFFFF 0% 0% no-repeat padding-box;
        opacity: 1;
        display: flex;
        align-items: center;
    }
    #logo{
        top: 31px;
        margin-left: 10em;
        width: 14em;
        height: 55px;
        flex:0.8;
        /* UI Properties */
        background: transparent url('img/Group 3.png') 0% 0% no-repeat;
    }

    #login{
      width:56px;
      height:27px;
      flex:0.06; 
      margin-top:42px;
      margin-bottom:41px;
        font: normal normal bold 20px/27px Noto Sans;
        letter-spacing: 0px;
        color: #1F2532;
        background-color: #fff;
        border: 0;
    }
    #register{
        width:144px;
        margin: 25px 0px 25px;
        margin-left: 50px;
        height: 60px;
        background: #01CB63 0% 0% no-repeat padding-box;
        box-shadow: 0px 5px 15px #01CB6359;
        border-radius: 10px;
        opacity: 1;
        border:0;
    }
    #banner{
        display: flex;
        margin-top: 45px;
    }
    #bannertxt{
        display: flex;
        flex:0.5;
        height: 520px;
        justify-content: center;
        align-items: center;
        background-color: #01CB63;
    }
    #bannerimg{
        height: 520px;
        flex:0.5;   
        background: transparent url() 0% 0% no-repeat padding-box;
        mix-blend-mode: multiply;
        opacity: 0.55;
    }
    #text{
        width:70%;
        justify-content: center;
        align-items: center;
    }
    #t1{
        text-align: left;
        font: normal normal bold 3em/1.25em Noto Sans;
        letter-spacing: 0px;
        color: #FFFFFF;
        text-transform: capitalize;
        opacity: 1;
        margin-bottom: 30px;
        
    }
    #t2{
        text-align: left;
        letter-spacing: 0px;
        opacity: 1;
        font: normal normal normal 1.75em/1.2em Noto Sans;
        letter-spacing: 0px;
        color: #1F2532;
        margin-bottom: 30px;
    }
    #btn{
        width: 9em;
        height: 60px;
        color:#FFFFFF;
        font: normal normal normal 1.3em/1.2em Noto Sans;
        font-size: 1.1em;
        letter-spacing: 0.5px;
        background: #000000 0% 0% no-repeat;
        border-radius: 10px;
        opacity: 1;
        padding-left: 20px;
        padding-right: 20px;
        float:left;
    }
</style>