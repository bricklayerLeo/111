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
   <div class="left">
   <div class="logo"></div>
   </div>
   <div class="right">
   <div class="title"></div>
   <div class="info"></div>
   <div class="rate"></div>
   <div class="rate1"></div>
   </div>
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
  .main{
    width:p2r(690);
    height:p2r(263);
    background:rgba(255,255,255,1);
    box-shadow:p2r(0) p2r(6) p2r(8) p2r(0) rgba(35,35,35,0.07);
    border-radius:p2r(18);
    
    
    .left{

      .logo{

      }
    }
    .right{

      .title{

      }
      .info{

      }
      .rate{

      }
      .rate1{

      }
    }
  }
  .header{
    width: p2r(750);
    height: p2r(303) !important; 
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
