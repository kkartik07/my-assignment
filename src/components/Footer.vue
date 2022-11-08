<template >
    <div id="foot">
        <div>2021-2022 © Course Pro Private Limited</div>
        <div id="terms"><span>Term & Condition </span><span> Privacy Policy</span></div>
    </div>
</template>




<script>
export default{
name:"Foot",
}
</script>

<style scoped>

#foot{
    display: flex;
    justify-content: space-between;
    margin-top: 150px;
    margin-left: 100px;

    height: 34px;
/* UI Properties */
text-align: left;
font: normal normal bold 25px/34px Noto Sans;
letter-spacing: 0px;
color: #1F2532;
text-transform: capitalize;
margin-bottom: 100px;
}
#terms{
    margin-right: 70px;
    display: flex;
    width:400px;
    justify-content: space-between;
}
</style>