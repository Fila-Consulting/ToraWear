<template>
  <div class="main">
    <div class="toraWearPic">
      <div class="logo">
       <!-- <img src="../assets/logo.jpg" alt="Tora Shop Logo"> -->
      </div>
    </div>

  <div class="secondLine">
    <div class="leftPicTora"></div>
      <div class="rightPicTora"></div>
  </div>

  <div class="thirdLine">
    <div class="Categories1"></div>
      <div class="Categories2"></div>
        <div class="Categories3"></div>
  </div>

    <div class="fourthLine">
      <div class="Promotion"></div>
    </div>

      <div class="fifthLine">
        <div class="aboutUs "><h2>{{ About}}</h2></div>
        <div></div>

      </div>
  </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      About: "About Us",

    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* do Poprawy*/
  .toraWearPic{
    width: 100%;
    height:900px ;
    border: 1px solid black;

  background-position: center;
  display: grid;
  grid-template-columns: 50% 50%;

  }

.secondLine{
    width: 100%;
    height:400px;
    border: 1px solid black;
  background-size: cover;
  background-position: center;
  display: grid;
  grid-template-columns: 50% 50%;
}

   .leftPicTora{
    border: 1px solid black;
   }
  .rightPicTora{
    border: 1px solid black;

  }

.thirdLine
{
width: 100%;
height:400px ;
border: 1px solid black;

background-size: cover;
background-position: center;
display: grid;
grid-template-columns: 33.33% 33.33% 33.33%;
}

.Categories1{
  border: 1px solid black;
}

.Categories2{
  border: 1px solid black;
}

.Categories3{
  border: 1px solid black;
}

.fourthLine{
    width: 100%;
    height:600px ;
    /*background-color:black; */
    border: 1px solid black;
}

.fifthLine{
  width: 100%;
  height:750px ;
  border: 1px solid black;
  background-image: url("../assets/aboutUs.jpg");
  background-size: cover;
  background-position: center;
  display: grid;
  grid-template-columns: 50% 50%;
}

.aboutUs{
background: rgba(0, 0, 0, 0.726);
  color: white;
}

</style>