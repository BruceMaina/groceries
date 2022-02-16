<template>
<div class="home-container">
  <div class="home">
  <div class="heading-details">
   <div id="nav">
      <router-link to="/" style="padding-right:20px;">Home</router-link> |
      <router-link to="/about" style="padding-right:20px; padding-left:20px;">Product</router-link> |
      <router-link to="/about" style="padding-right:20px; padding-left:20px;">Features</router-link> |
      <router-link to="/about" style="padding-right:20px; padding-left:20px;">Blog</router-link> 
    </div>
    <div class="Header">
        <img src="../assets/imgs/heading.png" />
   </div>
   <!-- <div class="home-search-button"> -->
     <div class="home-search">
       <input 
       id="search-food"
       type="text"
       placeholder="Search"
       >
       <img src="../assets/imgs/search - Copy.png" class="search-icon">
     </div>
     <div class="cart">
       <img src="../assets/imgs/favpng_organic-food-grocery-store-supermarket.png" alt="">
     </div>
     <div class="list">
       <img src="../assets/imgs/menu.png" alt="">
     </div>
     </div>
   <!-- </div> -->
   
  
   </div>
   <div class="main-image">
     <img src="../assets/imgs/man-in-red.png" alt="">
       <!-- <img src="../assets/imgs/markus-spiske-i5tesTFPBjw-unsplash.jpg" alt="">
     <img src="../assets/imgs/sara-scarpa-AJFQGDaFP-s-unsplash.jpg" alt=""> -->
   </div>
    <div class="catch-phrase">
     <h1 style="color:#42b983;">Karibu Sokoni</h1>
     <h2>For All Your Grocery Needs</h2>
   </div>
   <div class="paraphrased" style="margin-left:1;">
     <p>For the longest time, 
        the distance <br> between the producers and consumers has been <br>
        the longest and most expensive route. <br>Imagine a world where 
        you could <br> bridge the gap by simply making your orders <br> directly from the producer 
        to your doorstep.<br>  Karibuni Sokoni
        </p>
   </div>
   <div class="button">
     <button>LogIn</button>
     <button>Sign up</button>
   </div>
   <div class="hand">
     <img src="../assets/imgs/hand.png" alt="">
   </div>
   <div class="grossy">
     <img src="../assets/imgs/kitungu.png" alt=""  style="margin-left:65%;">
     <img src="../assets/imgs/ndizi.png" alt="" style="margin-left:23%;">
     <img src="../assets/imgs/sukuma.png" alt="" style="margin-left: 56%;">
     <img src="../assets/imgs/waru.png" alt="" style="margin-left: 26%;">
     <img src="../assets/imgs/matunda-damu.png"  style="margin-left: 56%; margin-top:-30%;" alt="" >
     <img src="../assets/imgs/kukumba.png" alt="" style="margin-left: 36%; margin-top:-30%;">
     <img src="../assets/imgs/brocolli.png" alt="" style="margin-left: 66%; margin-top:-30%;">
     <img src="../assets/imgs/machungwa.png" alt="" style="margin-left: 35%; margin-top:-30%;">
   </div>
   <div class="nyanya">
     <img src="../assets/imgs/nyanya.png" alt="">
   </div>
   <div class="simplyabout">
     <h1>Our Products</h1>
   </div>
   </div>
  
</template>

<script>
// @ is an alias to /src


export default {
  name: 'Home',
  components: {
   
  }
}
</script>
<style scoped>
/* .home-container {
  height: 100%;
  width: 100%;
  background-color: rgb(214, 248, 231);
  overflow: hidden;
  position: relative;
} */
.home {
  height: 100%;
  width: 100%;
  /* border: 1px solid red; */
  display: flex;
  flex-direction: row;
  /* position: relative; */
  
}
.heading-details{
  display: flex;
  /* margin-left: 55px; */
}
.Header{
  padding-right: 40%;
  /* padding: 0px; */
  /* height: 10%;
  width: 10%; */
  background-color: transparent;
  /* border: 1px solid red; */
  justify-content: center;
  /* padding-left: 5%; */
  /* padding-top: -20px; */

}

/* .Header img {
  height: 200px;
  width: 300px;
  
} */
#nav{
  /* height: 14%;
  width: 20%; */
  font-size: 16px;
  padding-left: 15px;
  margin-right: 30%;
  margin-top: 6.5%;
  /* justify-content: left;
  justify-items: left; */
  /* border: 1px solid red; */
  justify-content: space-evenly;
  display: flex;
  flex-direction: row;
}
.home-search-button {
  display: flex;
  flex-direction: row;
}
#search-food  {
  height: 35px;
  width: 130px;
  margin: 17px 0px;
  /* display: flex; */
  border-radius: 8px;
  border: transparent;
  box-shadow: rgba(0, 0, 0, 0.20) 0px 3px 8px;
  /* border: 1px solid grey; */
  padding-left: 30px;
  /* justify-items: center; */
}
.search-icon{
  height: 15px;
  width: 15px;
  padding-top: 27px;
  position: absolute;
  padding-left: 7px;
  padding-right: 30px;
}
.home-search{
  display: flex;
  position: relative;
  margin-top: 27px;
  
 }
 .cart img{
   width: 35px;
   height: 35px;
   margin-top: 43px;
   margin-left: 40px;
   border-radius: 7px;
   /* box-shadow: rgba(0, 0, 0, 0.30) 0px 3px 8px; */
   cursor: pointer;
   /* border: 1px solid red; */
 }
 .list img{
   /* border:1px solid red; */
   height: 30px;
   width: 30px;
   margin-top: 50px;
   margin-left: 30px;
 }

.main-image{
  margin-left: 70%;
  margin-top: 3%;
}
 .main-image img{
   height: 450px;
   width: 400px;
   /* box-shadow: rgba(0, 0, 0, 0.30) 0px 3px 8px; */
   
 }
 .catch-phrase{
   margin-top: -30%;
   margin-left: 1%;
   text-shadow: rgba(0, 0, 0, 0.30) 0px 3px 8px;
   font-size: x-large;
 }
 .hand img{
  margin-left: 1%;
  margin-top: -3%;
 }
 .grossy{
   float: unset;
   margin-top: -55%;
   display: flex;
   flex-direction: column;
 }
 .grossy img{
   height: 100px;
   width: 100px;
 }
 .paraphrased p{
   font-weight: 100;
   margin-left: 1%;
 }
 .button{
   display: flex;
   margin-left: 1%;
   margin-top: 2%;
  
   
 }
 .button button {
   margin-right: 10%;
   border-radius: 15px;
   height: 40px;
   width: 100px;
   background-color: black;
   color: white;
   border: 1px solid black;
   box-shadow: rgba(0, 0, 0, 0.50) 0px 3px 8px;
   cursor: pointer;
 }
 .nyanya img{
   height: 300px;
   width: 300px;
   margin-left: 35%;
   margin-top:  5%;
 }
 .simplyabout{
   margin-left: 50%;
   margin-top: 0%;
   color: #42b983;
   text-shadow: rgba(0, 0, 0, 0.30) 0px 3px 8px;
 }
</style>
