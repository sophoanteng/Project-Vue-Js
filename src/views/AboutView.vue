<template>
  <div class="about">
   <div class="box-company">
      <div class="text-info">
         <img src="../assets/logo-text.svg" alt="">
         <br>
         <h1 style="text-align: start; margin-top: 25%; font-size: 40px">Build The Community Your Fans Will Love</h1>
         <br>
         <p style="text-align: start;">Huddle re-imagines the way we build communities. You have a voice, but so does your audience. Create connections with your users as you engage in genuine discussion.</p>
         <button type="submit" class="button-start">Get Started For Free</button>
      </div>
      <div class="img-info">
        <img class="img-banner" src="../assets/logo-person.svg" alt="">
        <button type="submit" class="try">Try It Free</button>
      </div>
   </div>
    <div class="box-person1">
       <div class="text-person-info">
         <h1 style="">Grow Together</h1>
         <p style="color: grey; font-size: 20px;">Generate meaningful discussions with your audience and build a strong, loyal community. Think of the insightful conversations you miss out on with a feedback form.</p>
       </div>
       <img class="img-person" src="../assets/person-1.svg" alt="">
    </div>
    <div class="box-person1">
      <img class="img-person-new" src="../assets/person-2.svg" alt="">
       <div class="text-person-info">
         <h1 style="">Flowing Conversations</h1>
         <p style="color: grey; font-size: 20px;">You wouldn't paginate a conversation in real life, so why do it online? Our threads have just-in-time loading for a more natural flow.</p>
       </div>
    </div>
    <div class="box-person1">
       <div class="text-person-info">
         <h1 style="">Your Users</h1>
         <p style="color: grey; font-size: 20px;">It takes no time at all to integrate Huddle with your app's authentication solution. This means, once signed in to your app, your users can start chatting immediately.</p>
       </div>
       <img class="img-person" src="../assets/person-3.svg" alt="">
    </div>
    <div class="box-getStart">
      <h1>Ready To Build Your Community?</h1>
      <button type="submit" class="btn-free">Get start for free</button>
    </div>
    <div class="box-footer">
        <h1 style="color: white; margin-left: 10%; padding-top: 25px;">UIFrondEnd</h1>
        <h3 style="color: white; margin-left: 15%; padding-top: 38px;">Product</h3>
        <br>
        <ul class="nav">
          <li>Overview</li>
          <li>Pricing</li>
          <li>Marketplace</li>
          <li>Feature</li>
          <li>Integrations</li>
        </ul>
        <h3 style="color: white; margin-left: 15%; padding-top: 38px;">Company</h3>
        <br>
        <ul class="nav">
          <li>About</li>
          <li>Team</li>
          <li>Blog</li>
          <li>Careers</li>
        </ul>
        <h3 style="color: white; margin-left: 15%; padding-top: 38px;">Connect</h3>
        <br>
        <ul class="nav">
          <li>Overview</li>
          <li>Pricing</li>
          <li>Marketplace</li>
          <li>Feature</li>
          <li>Integrations</li>
        </ul>
     </div>
  </div>
</template>
<style scoped>
  .btn-free {
    padding: 20px;
    width: 50%;
    margin-top: 20px;
    border-radius: 30px;
    background: #FF52BF;
    border: none;
    color: white;
    font-size: 18px;
  }
  .box-getStart {
    bottom: -40px;
    margin-top: 5%;
    width: 40%;
    padding: 20px;
    border-radius: 10px;
    height: 200px;
    background: white;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    text-align: center;
    margin-left: 25%;
    position: relative;
  }
  .box-person1 {
    display: flex;
    width: 70%;
    align-items: center;
    justify-content: center;
    height: auto;
    text-align: center;
    border-radius: 6px;
    margin-top: 5%;
    padding: 3%;
    margin-left: 15%;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19)
  }
  .text-person-info {
    text-align: start;
    padding-left: 10%;
    padding-left: 0%;
    max-width: 505px;
}
  .img-person {
    width: 30%;
    padding-left: 23%;
  }
  .img-person-new {
    width: 30%;
    padding-right: 23%;
  }
  .img-banner {
    width: 70%;
    padding: 10%;
  }
.box-company {
  display: flex;
  padding: 60px;
  background: #EBFBFF;
}
.text-info{
  margin-top: 4%;
  width: 33%;
  text-align: start;
}
.img-info {
  display: flex;
  margin-top: 4%;
}
.button-start {
  margin-top: 20px;
  padding: 20px;
  border-radius: 35px;
  background: #FF52BF;
  border: none;
  width: 50%;
  font-size: 15px;
  color: white;
  font-weight: bold;
}
.try {
  height: 9%;
  color: #FF876E;
  border: 1px solid #FF876E;
    padding: 2%;
    width: -webkit-fill-available;
    margin-left: -11%;
    border-radius: 35px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19)
}
.box-footer {
    background: #25252D;
    width: 100%;
    height: 300px;
    display: flex;
    border-top-right-radius: 152px;
  }
  .nav {
    color: white;
    list-style-type: none;
    text-align: start;
    margin-top: 7%;
    margin-left: -6%;
  }
  .nav li {
    margin-top: 10%;
  }
</style>
