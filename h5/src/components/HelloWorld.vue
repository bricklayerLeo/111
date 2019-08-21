<template>
  <div class="hello">
   <div class="header">
     <div class="header1">
     <div class="avator"></div>
     <div class="desc">
       <span class="desc1">客户您好，我是李牛逼</span> 
       <span class="desc2">邀请您申请大数时代-XXX</span>
     </div>
     </div>
   </div>
   <haha/>
  </div>
</template>

<script>
import haha from './haha'
export default {
  name: 'HelloWorld',
  components:{
    haha,
  },
  data () {
    return {
     
    }
  }
  
}
</script>


<style scoped>

.header{
  width: 62.5rem;
  height: 25.25rem;
  background:rgba(242,243,245,1);
}
.header1{
  padding-top: 4rem;
  padding-left: 10rem;
  display: flex;
  flex-direction: row;
}
.avator{
  width:10.25rem;
  height:10.24rem;
   border-radius:50%;
   border: 1px solid black;
   padding-right: 3rem;
}
.desc{
   padding-top: 1rem;
   padding-left: 3rem;
   font-size:2.67rem;
   font-family:PingFang SC;
   font-weight:500;
   color:rgba(51,51,51,1);
}
.desc1{
  display: inline-block;
  margin-bottom: 1rem;
}
.desc2{
  display: inline-block;

}
</style>
