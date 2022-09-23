<template>
    <div id="menu">
        <div class="contain-info">
            <div class="box-text">
                <h1 style="font-size: 50px; text-align: start;">A Simple Bookmark Manager</h1>
                <p style="font-size: 25px; color: gray">A clean and simple interface to organize your favourite websites. Open a new browser tab and see your sites load instantly. Try it for free.</p>
                <div class="keep-button">
                    <button type="submit" class="btn-chrome">Get It On Chrome</button>
                    <button type="submit" class="btn-firefox">Get It On FireFox</button>
                </div>
            </div>
            <div class="keep-img">
                <div class="back"></div>
                <img class="img-1" src="../assets/img-connect.svg" alt="">
            </div>
        </div>
        <h1>Features</h1>
        <div class="text-feature">
            <p class="sub-text">Our aim is to make it quick and easy for you to access your favourite websites. Your bookmarks sync between your devices so you can access them on the go.</p>
        </div>
        <div class="keep-info">
            <p style="color:gray; font-size: 20px; padding-right: 10%;">Simple Bookmarking</p>
            <p style="color:gray; font-size: 20px; padding-right: 10%;">Speedy Searching</p>
            <p style="color:gray; font-size: 20px">Easy sharing</p>
        </div>
        <div class="sticker">
            <img class="img-connect" src="../assets/img-connect1.svg" alt="">
            <div class="sticker-info">
                <h1>Share your bookmarks</h1>
                <p style="color: gray;  margin-top: 30px;">Easily share your bookmarks and collections with others. Create a shareable a link that you can send at the click of a button.</p>
                <button type="submit" class="info">More Info</button>
            </div>
        </div>
        <h1 style="margin-top: 8%">Download the extension</h1>
        <div class="text-feature">
            <p class="sub-text">We've got more browsers in the pipeline. Please do let us know if you've got a favourite you'd like us to prioritize.</p>
        </div>
        <div class="contain-card">
            <div class="car-1">
                    <img class="img-connect-1" src="../assets/img-chrome.svg" alt="">
              <h1 style="text-align: start; padding: 7px 20px; color: black; margin-top: 17%;">Add to Chrome</h1>
              <p style="text-align: center; padding: 7px 20px; color: gray; font-size: 20px;">Minimum Version 62</p>
              <button class="add-button">Add & INstall Extension</button>
            </div>
            <div class="car-2">
                    <img class="img-connect-1" src="../assets/fire-box.svg" alt="">
                    <h1 style="text-align: start; padding: 7px 20px; color: black; margin-top: 17%;">Add to Chrome</h1>
              <p style="text-align: center; padding: 7px 20px; color: gray; font-size: 20px;">Minimum Version 62</p>
              <button class="add-button">Add & INstall Extension</button>
            </div>
            <div class="car-3">
                    <img class="img-connect-1" src="../assets/logo-opera.svg" alt="">
                    <h1 style="text-align: start; padding: 7px 20px; color: black; margin-top: 17%;">Add to Chrome</h1>
              <p style="text-align: center; padding: 7px 20px; color: gray; font-size: 20px;">Minimum Version 62</p>
              <button class="add-button">Add & INstall Extension</button>
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
<script>

</script>
<style scoped>
    .box-footer {
    margin-top: -12%;
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
 .add-button {
    padding: 20px 45px;
    border-radius: 7px;
    border: none;
    font-size: 16px;
    color: white;
    background: #6666ed;
    margin-right: 0px; 
    margin-top: 30px;
}
.contain-card {
    display: flex;
    padding: 20%;
    margin-top: -16%;
}
.car-1, .car-2, .car-3{
    text-align: center;
    padding: 30px;
    background: #ffff;
    height: 400px;
    border-radius: 16px;
    width: 50%;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19)
}
.car-2 {
    margin-left: 44px;
}
.car-3 {
    margin-left: 44px;
}
.sticker-info {
    text-align: start;
    padding-left: 10%;
    width: 29%;
    font-size: 20px;
}
.sticker {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 7%;
}
.keep-info {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 3%;
    border-bottom: 1px solid gray;
    margin-left: auto;
    margin-right: auto;
    width: 35%;
}
.contain-info {
    display: flex;
    justify-content: center;
    align-items: center;
}
.back {
    width: 37%;
    height: 283px;
    background: #6666ed;
    bottom: -330px;
    position: absolute;
    margin-left: 28%;
    border-bottom-left-radius: 150px;
}
.text-feature {
    text-align: center;
    white-space: wrap; 
    width: 26%; 
    margin-left: auto;
    margin-right: auto;
}
p.sub-text {
    text-align: center;
    color: gray;
    font-size: 18px;
}
.img-1 {
    padding-left: 16%;
    position: relative;
}
.box-text {
    width: 27%;
    text-align: start
}
.info {
    padding: 20px;
    width: 20%;
    border-radius: 7px;
    border: none;
    font-size: 16px;
    color: white;
    background: #6666ed;
    margin-right: 25px; 
    margin-top: 30px;
}
.btn-chrome {
    padding: 20px;
    width: 40%;
    border-radius: 7px;
    border: none;
    font-size: 16px;
    color: white;
    background: #6666ed;
    margin-right: 25px;
}
.btn-firefox {
    padding: 20px;
    width: 40%;
    border-radius: 7px;
    border: none;
    font-size: 16px;
    color: black;
    background: #d7d7ef;
}
.keep-img {
    width: 58%;
    margin-top: 7%;
}
</style>