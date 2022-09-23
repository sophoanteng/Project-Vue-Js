<template>
  <div class="home">
    <p class="text-info">Designed for the future</p>
     <div class="contain-info">
         <div class="text">
          <h1 style="text-align: start;">Introducing an extensible editor</h1>
          <p style="text-align: start;">Blogr features an exceedingly intuitive interface which lets you focus on one thing: creating content. The editor supports management of multiple blogs and allows easy manipulation of embeds such as images, videos, and Markdown. Extensibility with plugins and themes provide easy ways to add functionality or change the looks of a blog.</p>
          <br><br>
          <h1 style="text-align: start;">Robust content management</h1>
          <p style="text-align: start;">Flexible content management enables users to easily move through posts. Increase the usability of your blog by adding customized categories, sections, format, or flow. With this functionality, you’re in full control.</p>
         </div>
         <div class="image-box">
          <img class="img-1" src="../assets/img-1.svg" alt="">
         </div>
     </div>
     <div class="box-phone">
        <img class="phone-img" src="../assets/img-2.svg" alt="">
        <div class="text-phone">
          <h1>State of the Art Infrastructure</h1>
          <p>With reliability and speed in mind, worldwide data centers provide the backbone for ultra-fast connectivity. This ensures your site will load instantly, no matter where your readers are, keeping your site competitive.</p>
        </div>
     </div>
     <div class="contain-info" style="margin-top: 8%">
       <div class="image-box">
        <img class="img-3" src="../assets/img-3.svg" alt="">
       </div>
         <div class="text">
          <h1 style="text-align: start;">Free, open, simple</h1><br>
          <p style="text-align: start;">Blogr is a free and open source application backed by a large community of helpful developers. It supports features such as code syntax highlighting, RSS feeds, social media integration, third-party commenting tools, and works seamlessly with Google Analytics. The architecture is clean and is relatively easy to learn.</p>
          <br><br>
          <h1 style="text-align: start;">Powerful tooling</h1><br>
          <p style="text-align: start;">Batteries included. We built a simple and straightforward CLI tool that makes customization and deployment a breeze, but capable of producing even the most complicated sites.</p>
         </div>
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
  .text {
    width: 626px;
}
.text-phone {
  color: white;
  width: 559px;
    text-align: start;
    margin-left: 12%;
    margin-top: 137px;
}
.phone-img {
  width: 36%;
    height: 620px;
    margin-top: -74px;
    margin-left: 14%;
}
.box-phone {
  background: #363853;
  height: 432px;
  margin-top: -40px;
  border-top-right-radius: 152px;
  border-bottom-left-radius: 152px;
  display: flex;
}
.img-1{
  width: 85%;
  margin-left: 22%;
}
.img-3{
  width: 886px;
  margin-left: -27%;
}
.text-info {
  font-size: 40px;
  margin-top: 6%;
}
.contain-info {
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>