<template>
<div class="up">
    <div class="up1">
      <div class="logo"></div>
      <div class="desc">
         <div class="title">大数时贷-XXX</div>
         <div class="desc1">
           <span class="desc1-1"> 当天放款</span>
           <span class="desc1-1">白户可做</span>
           <span class="desc1-1">先息后本</span>
         </div>
         <div class="desc2">
           <span class="desc2-1">0.6%</span>
           <span>3-30万</span>
         </div>
         <div class="desc3">
           <span class="desc3-1">月利率</span>
           <span>额度</span>
         </div>
      </div>
    </div>
</div>
</template>

<script>
export default {

  data () {
    return {
     
    }
  }
}
</script>


<style scoped>
.desc3-1{
  margin-right: 6.4rem;
}
.desc2-1{
  margin-right: 5rem;
}
.desc3{
   margin-top: 0.75rem;
  font-size:2rem;
font-family:PingFang SC;
font-weight:500;
color:rgba(102,102,102,1)
}
.desc2{
   margin-top: 1.5rem;
  font-size:3rem;
font-family:PingFang SC;
font-weight:500;
color:rgba(255,85,85,1);
}
.desc1-1{

margin-right: 1rem;
width:12rem;
height:3.17rem;
font-size:2.33rem;
font-family:PingFang SC;
font-weight:500;
color:rgba(255,154,38,1);
background-color:#FFEBD4;
text-align: center;
border-radius:2rem;
padding: .3rem 1rem .6rem 1rem;
}
.desc1{
   margin-top: 2rem;
}
.desc{
  margin-left: 3rem;
}
.title{
margin-top: 1.8rem;
font-size:3rem;
font-family:PingFang SC;
font-weight:bold;
color:rgba(51,51,51,1);
}
.logo{
  width:11.67rem;
  height:5.83rem;
  border: .12rem solid black;
  margin-top: 8rem;
  margin-left: 3rem;
}
.up1{
    position: absolute;
    top: 16rem;
    left: 2.5rem;
    width:57.5rem;
    height:21.92rem;
    background:rgba(255,255,255,1);
    box-shadow:0rem 1rem 1rem 0rem rgba(35,35,35,0.07);
    border-radius:2rem;
    display: flex;
    flex-direction: row;
}
</style>
