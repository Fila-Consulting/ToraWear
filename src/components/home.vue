<template>
  <div class="main">
   <div class="toraWearPic"></div>

<div class="secondLine">
   <div class="leftPicTora"></div>
<div class="rightPicTora"></div>
</div>

  </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {

    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.secondLine{
       width: 100%;
     height:400px ;
     border: 1px solid black;
  display: flex;
}
   .toraWearPic{
     width: 100%;
     height:400px ;
     border: 1px solid black;

   }
   .leftPicTora{
    border: 1px solid black;

    flex-direction: column;
    height:400px ;
    width:50%;

   }
  .rightPicTora{
    border: 1px solid black;
    flex: 1;
    flex-direction: column;
    height:400px ;
    width:50%;

  }
</style>
