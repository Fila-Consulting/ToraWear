<template>
  <div class="main">

    <div class="toraWearPic">
      <div class="logo">
        <img src="../assets/logo.jpg" alt="Tora Shop Logo">
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
        <div class="aboutUs">

        <img src="../assets/aboutUs.jpg" alt="About Us">

               <div class="overlay">{{ About }}

                 </div>
        </div>

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
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* do Poprawy*/
  .toraWearPic{
    width: 100%;
    height:900px ;
    background-color:black;
    border: 1px solid black;

  }

  .logo{
    display: block;
    height: 100%;
    margin-left: auto;
    margin-right: auto;
    width: 50%;
  }


.secondLine{
    width: 100%;
    height:400px ;
    border: 1px solid black;
    display: flex;
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



.thirdLine
{
width: 100%;
height:400px ;
border: 1px solid black;
display: flex;
}


.Categories1{
  border: 1px solid black;
  flex-direction: column;
  height:400px ;
  width:33.333333%;
}

.Categories2{
  border: 1px solid black;
  flex-direction: column;
  height:400px ;
  width:33.333333%;
}

.Categories3{
  border: 1px solid black;
  flex-direction: column;
  height:400px ;
   width:33.333333%;
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
}



/* do Poprawy*/
.aboutUs{
  height: 100%;
  width: 100%;;
  background-color: black;
}


.aboutUs img{
 /* height: 100%; */
  background-size: cover;
  float: left;
  /*padding: 0px 17% 0px; */
}

.overlay{
position: absolute;
height: 100%;
width: 35%;
color:Black;
background-color: white;
filter: opacity(50%);
}


</style>
