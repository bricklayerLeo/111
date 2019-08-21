<template>
<div class="inp">
  <div class="inp1">
    <input class="shuru" placeholder="请输入您的姓名" type="text">
      <input class="shuru"   placeholder="请输入您的手机号" type="text">
      <input class="shuru"  placeholder="请输入验证码"   type="text">     
      <input class="submit" type="button" style=" background-color:#EFBE73;"  value="提交">
      <p class="agreement">点击按钮表示同意<a href="">《用户协议》</a> </p>
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
.agreement{
  font-size:2rem;
font-family:PingFang SC;
font-weight:400;
color:rgba(153,153,153,1);
}
.submit{
width:27.17rem;
height:7rem;
background:linear-gradient(270deg,rgba(227,182,111,1) 0%,rgba(252,200,121,1) 100%);
box-shadow:0rem 1rem 1rem 0rem rgba(186,65,5,0.25);
border-radius:4rem;
font-size:3rem;
font-family:PingFang SC;
font-weight:bold;
color:rgba(255,255,255,1);
border: none;
}
.shuru{
  padding-left: 3rem;
  width: 46.83rem;
  height: 7.5rem;
  background:rgba(243,243,243,1);
  border-radius:4rem; 
  border: none;
  margin-bottom: 5rem;
  font-size: 2.5rem;
  font-weight:500;
  color:rgba(153,153,153,1);
}
.inp1{
  margin-top:17rem;
  margin-left: 1.15rem;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  position: absolute;
  top: 267pt;
  left: 47pt;
}
</style>
