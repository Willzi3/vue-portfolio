<template>
  <div id="About">
    
   <div class="container">
    <div class="row">
      <div class="col">
        <div class="about_img">
      <img src="../assets/Zachary1.jpg" />
    </div>
      </div>
      <div class="col">
        <div class="about_text">
          <h1>About ME</h1>
          <p>I like to describe myself as focused and dedicated. If I do something, I do it to the best of my abilities. If I do not know the answer to something, I won't just sit back and have the answer handed to me. I will make sure to find the answer.</p>
          <div class="about_d">
     <div class="about_details">
      <h6>Full Name</h6>
      <p>Zachary Williams</p>
    </div>
    <div class="about_details">
      <h6>Date Of Birth</h6>
      <p>2000/26/09</p>
    </div>
    <div class="about_details">
      <h6>Address</h6>
      <p>Melkbosstrand</p>
    </div>
    <div class="about_details">
      <h6>Drivers</h6>
      <p>None</p>
    </div>
    <div class="about_details">
      <h6>Criminal Record</h6>
      <p>None</p>
    </div>
   </div> 
        </div>
      </div>
    </div>
   </div>
  </div>

</template>
<style scoped>
 #About{
  height: 60vh;
  margin-inline: 5%;
  box-shadow: 5px 5px 5px 5px lightgray;
  border-radius: 10px;
  display: flex;
  justify-content: center;
  align-items: center;
 }

 .about_img img {
  width: 400px;
  height: 400px;
  border-radius: 10px;
  margin-top: 30px;
 }
 .about_text{
  margin-inline: 5%;
 }
 .about_details{
  display: flex;
  justify-content: space-between;
  padding: 0;
 }
 .container .row{
  display: flex;
  padding: 20px;
 }
</style>
