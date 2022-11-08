<template >
    <div id="head1">
        <div>
            <div id="head11">Contact Information</div>
            <div id="contacts">
                <div class="social"><img class="logo" id="logo1" src="Group 10750.png"/>contact@coursepro.com</div>
                <div class="social"><img class="logo" id="logo2" src="Group 10749.png"/>1800-562-895, 1800-869-877</div>
                <div class="social"><img class="logo" id="logo3" src="Group 10748.png"/>102 Street, India</div>
                <div>
                    <div id="socials">Social Media Channel</div>
                    <div id="medias">
                        <img src="Media1.svg" class="media"/>
                        <img src="Media2.svg" class="media"/>
                        <img src="Media3.svg" class="media"/>
                        <img src="Media4.svg" class="media"/>
                    </div>
                </div>
            </div>
    </div>
    <div>    
        <div id="head12">Fill up the form and our team will get back to you within 24 hours</div>
        <div class="box">
            <input placeholder="Name" type="text" required/>
            <input placeholder="Email" type="email" required/>
        </div>
        <div class="box">
            <input placeholder="Phone" type="number" required/>
            <input placeholder="Subject" type="email" required/>
        </div>
        <input id="textarea" placeholder="Message" required/>
        <button id="btn">Submit</button>
    </div>
 </div>
 <div id="form">
 </div>
</template>




<script>
export default{
name:"Contact",
}
</script>

<style scoped>
#socials{
    margin-top: 95px;
}
.social{
text-align: left;
font: normal normal bold 25px/34px Noto Sans;
letter-spacing: 0.5px;
color: #201F23;
opacity: 0.8;
}
#medias{
    display: flex;
    margin-top: 25px;
    justify-content: space-between;
}
.media{
    width:50px;
}
#textarea{
    height: 152px;
    border:1px solid #01CB63;
    width:100%;
}
#socials{
    width: 384px;
height: 47px;
/* UI Properties */
text-align: left;
font: normal normal bold 35px/34px Noto Sans;
letter-spacing: 0.7px;
color: #201F23;
}
.box{
    display: flex;
    justify-content: space-between;
}
#btn{
    margin-top: 30px;
    width: 202px;
height: 60px;
/* UI Properties */
background: #000000 0% 0% no-repeat padding-box;
border-radius: 10px;
}
#btn{
font: normal normal normal 25px/50px Noto Sans;
letter-spacing: 0.5px;
color: #FFFFFF;

}
input{
    height: 20px;
/* UI Properties */
text-align: left;
font: italic normal normal 22px/31px Noto Sans;
letter-spacing: 0px;
color: #86919D;
}
.social{
    display:flex;
    align-items: center;
}
.logo{
    width: 72px;
height: 72px;
}
#head1{
    margin-left:100px;
    margin-right: 100px;
    display: flex;
    justify-content: space-between;
    margin-top: 100px;   
}
#head11{
    height: 47px;
    /* UI Properties */
    text-align: left;
    font: normal normal bold 35px/34px Noto Sans;
    letter-spacing: 0.7px;
    color: #201F23;
}
#head12{
    height: 68px;
    width: 570px;
    /* UI Properties */
    text-align: center;
    font: normal normal bold 25px/34px Noto Sans;
    letter-spacing: 0px;
    color: #201F23;
}
input{
    border: 0;
    padding: auto;
    margin-top: 40px;
    border-bottom: 2px solid #01CB63;
}
</style>