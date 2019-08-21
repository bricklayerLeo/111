<template>
  <div class="hello">
   <div class="header">
     <div class="header1">
     <div class="avator"></div>
     <div class="desc">
       <div class="desc1">客户您好，我是李牛逼</div> <br>
       <div class="desc2">邀请您申请大数时代-XXX</div>
     </div>
     </div>
   </div>
 
 <div class="main">
   <div class="main1">
   <div class="left">
   <div class="logo"></div>
   </div>
   <div class="right">
   <div class="title">大数时贷-XXX</div>
   <div class="info">
     <span class="info1">当天放款</span>
     <span class="info1">白户可做</span>
     <span class="info1">先息后本</span>
   </div>
   <div class="rate">
     <span class="rate-1">0.6%</span>
     <span >3-30万</span>
   </div>
   <div class="rate1">
     <span class="rate1-1">月利率</span>
     <span >额度</span>
   </div>
   </div>
   </div>
  </div>

 <div class="footer">
    <input class="shuru" placeholder="请输入您的姓名" type="text">
    <input class="shuru"   placeholder="请输入您的手机号" type="text">
    <input class="shuru"  placeholder="请输入验证码"   type="text">     
    <input class="submit" type="button"  value="提交">
    <p class="agreement">点击按钮表示同意<a href="">《用户协议》</a> </p>
 </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  components:{
   
  },
  data () {
    return {
     
    }
  }
  
}
</script>
<style lang="scss" scoped>

@function p2r($size){
    @return ($size/32)*1rem;
}

.hello{
  .footer{
    position: absolute;
    top: p2r(540);
    display: flex;
    flex-direction: column;
     margin-left: p2r(72);
  
    .shuru{
    padding-left: p2r(35);
  width: p2r(460);
  height:p2r(75);
  background:rgba(243,243,243,1);
  border-radius:p2r(45); 
  border: none;
  margin-bottom: p2r(45);
  font-size:p2r(26);
  font-weight:500;
  color:rgba(153,153,153,1);
    }
    .submit{
      font-size: p2r(36);
      color:rgba(255,255,255,1);
      margin: 0 auto;
      width:p2r(326);
height:p2r(75);
background:linear-gradient(270deg,rgba(227,182,111,1) 0%,rgba(252,200,121,1) 100%);
box-shadow:p2r(0) p2r(6) p2r(10) p2r(0) rgba(186,65,5,0.25);
border-radius:p2r(42);
border: none;
    }
    .agreement{
       margin: 0 auto;
        padding-top: p2r(16);
        padding-left: p2r(8);
      width: p2r(336);
font-size:p2r(24);
font-family:PingFang SC;
font-weight:400;
color:rgba(153,153,153,1);
    }
  }
  .main{
    display: flex;
    justify-content: center;
    .main1{
    width:p2r(580);
    height:p2r(263);
    background:rgba(255,255,255,1);
    box-shadow:p2r(0) p2r(6) p2r(8) p2r(0) rgba(35,35,35,0.07);
    border-radius:p2r(18);
    position: absolute;
    top: p2r(190);
    display: flex;
    flex-direction: row;
    .left{
      margin-right: p2r(21);
      .logo{
        margin-top:p2r(97);
        margin-left: p2r(20);
        width:p2r(140);
        height:p2r(70);
        border: 1px solid black;
      }
    }
    .right{
      .title{
        margin-top: p2r(30);
        font-size:p2r(36);
        font-family:PingFang SC;
        font-weight:bold;
        color:rgba(51,51,51,1);
      }
      .info{
        margin-top: p2r(30);
        font-size:p2r(20);
        font-family:PingFang SC;
        font-weight:500;
        color:rgba(255,154,38,1);
        .info1{
          margin-right: p2r(10);
          background-color: #FFEBD4;
          padding: p2r(6) p2r(16) p2r(5) p2r(19);
          border-radius: p2r(19);
        }
      }
      .rate{
        margin-top: p2r(24);
        font-size:p2r(36);
        font-family:PingFang SC;
        font-weight:500;
        color:rgba(255,85,85,1);
        .rate-1{
          margin-right: p2r(38.5);
        } 
      }
      .rate1{
        margin-top: p2r(9);
        font-size:p2r(24);
        font-weight:500;
        color:rgba(102,102,102,1);
        font-family:PingFang SC;
        .rate1-1{
          margin-right: p2r(54);
        }
      }
      }
    }
  }
  .header{
   
    height: p2r(303); 
     background:rgba(242,243,245,1);
    .header1{
      display: flex;
      flex-direction: row; 
      position: absolute;
      top: p2r(46);
      left: p2r(80);
      .avator{
        width: p2r(123);
        height: p2r(123);
        border-radius: 50%;
        border: p2r(1) solid black;
      }
      .desc{
        margin-top: p2r(20);
        font-size:p2r(32);
        padding-left: p2r(32);
        font-family:PingFang SC;
        font-weight:500;
        color:rgba(51,51,51,1);
        .desc1{
         padding-bottom: p2r(11);
         display: inline-block;
         
        }
        .desc2{
         
          display: inline-block;
         
        }
      }
    }
  }
}



</style>
