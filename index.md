---
layout: main
# Hero
hero_title: "Edmonton's best <span class='blue'>boardgame cafe</span>"
hero_content: "Table Top cafe is special blend of coffee shop, board game library and retail store."

shop_intro: "Looking for a game to take home?"

# About
about_title: "The perfect place to come together and get your game on"
about_content: "One flat rate lets you play as many games as you like. Our staff on hand can help you pick the right game for your group and teach you how to play it. Many of the games are also available for sale giving you an excellent try-it-before-you-buy-it experience. The store is a comfortable place where people can meet with friends, play a game, share a drink, and connect face to face.
"

about_feature_1: "500+ Board Games"
about_feature_1_content: "With everything from games for kids, to intense thematics and games with adult themes, our staff can help you choose the right game for your group and even teach a wide range of games to get you playing quickly."
about_feature_2: "Games For Sale"
about_feature_2_content: "If you like the game you are playing, there is a good chance we also have it for sale in our retail section and you can take it home with you right then!"
about_feature_3: "Food & Drink"
about_feature_3_content: "There are plenty of made in house food and snacks available (including Edmonton's best carrot cake) as well as a wide range of espresso drinks and craft beer."

price: $10.00*

---

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
  <a href="#">About</a>
  <a href="#">Services</a>
  <a href="#">Clients</a>
  <a href="#">Contact</a>
</div>


<div class="hero">
  <div class='hero-info' data-aos="fade-up">
    <h1 class="hero-title">{{ page.hero_title }}</h1>
    <p class="hero-content">{{ page.hero_content }}</p>
    <!-- Reservation Widget -->
    <div class="reservation-widget" style="display:inline-block">
    <script id="dine_script_tag_booker" src="https://www.tbdine.com/inject/booker?format=1col&name=table-top-board-game-cafe&idApp=69092&force=true&language=en-us" type="text/javascript"></script></div>
    <!-- End Reservation Widget -->
    <div class='hero-actions'>
      <!-- <a href="#" class="btn reservations">Make a reservation</a> -->
      <p class="shop-intro">{{ page.shop_intro }}</p>
      <a href="https://store.tabletopcafe.ca" class="btn-secondary">Shop online</a>
    </div>
  </div>
  <div class="hero-image-container">
    <img class='hero-image' src="{{ 'images/hero.jpg' | relative_url }}" alt="" data-aos="fade">
  </div>
  <!-- <div class='row reverse center'>
    <div class='col'>
      <div class='hero-info'>
        <h1 class="hero-title">You're favourite <span class="blue">coffee shop</span></h1>
        <p class="hero-content">Tabletop cafe is special blend of cofee shop, board game library and retail store.</p>
        <div class='hero-actions'>
          <a href="#" class="btn reservations">Make a reservation</a>
          <a href="#" class="btn-secondary">Shop online</a>
        </div>
      </div>
    </div>
    <div class='col'>
      <div class="hero-image-container">
        <img class='hero-image' src="{{ 'images/hero.jpg' | relative_url }}" alt="">
      </div>
    </div>
  </div> -->
</div>

<span id="about"></span>
<div class="about" data-aos="fade-up" data-aos-anchor-placement="top">
  <div class="row">
    <div class="col">
      <div class="about-wrapper">
        <h2 class="section-heading">About us</h2>
        <h3 class="section-title">{{ page.about_title }}</h3>
        <p>{{ page.about_content }}</p>
      </div>
    </div>
    <div class="col space-between">
      <div class="feature">
        <img class='feature-image' src="{{ 'images/tic-tac-toe.svg' | relative_url }}" alt="">
        <div>
          <h1 class="feature-title">{{ page.about_feature_1 }}</h1>
          <p>{{ page.about_feature_1_content }}</p>
        </div>
      </div>
      <div class="feature">
        <img class='feature-image' src="{{ 'images/view-2.svg' | relative_url }}" alt="">
        <div>
          <h1 class="feature-title">{{ page.about_feature_2 }}</h1>
          <p>{{ page.about_feature_2_content }}</p>
        </div>
      </div>
      <div class="feature">
        <img class='feature-image' src="{{ 'images/shopping-basket-1.svg' | relative_url }}" alt="">
        <div>
        <h1 class="feature-title">{{ page.about_feature_3 }}</h1>
        <p>{{ page.about_feature_3_content }}</p>
        </div>
      </div>
    </div>
  </div>
</div>

<span id="prices"></span>
<div class="prices" data-aos="fade-up">
  <h2 class="section-heading">Pricing</h2>
  <div class="row space-around center">
    <div class="col">
      <h3 class="section-title">Flex pricing</h3>
      <p class="pricing-description">You can play as many board games as you like for as long as you want. We run tabs for each individual so you don't have to pay until you leave, all we need is your name to get you going.</p>
    </div>
    <div class="col">
      <span class="price">
        {{ page.price }}<span class='price-unit'>per person</span>
        <p class="pricing-notes">For every item purchased from the kitchen or store your fee is reduced by $1.</p>
      </span>
    </div>
  </div>

  <div class="hours">
    <h2 class="section-heading">Hours of Operation</h2>
    <p class='hour-section'><span class='day'>Monday-Thursday:</span><span class="time">12:00PM - 11:00PM</span></p>
    <p class='hour-section'><span class='day'>Friday:</span><span class="time">12:00PM - 1:00AM</span></p>
    <p class='hour-section'><span class='day'>Saturday:</span><span class="time">11:00AM - 1:00AM</span></p>
    <p class='hour-section'><span class='day'>Sunday:</span><span class="time">11:00AM - 11:00PM</span></p>
  </div>
</div>

<span id="contact"></span>
<div class="contact" data-aos="fade-up">
  <div class="row reverse space-around">
    <div class="col">
      <div class="map">
        <iframe width="600" height="450" frameborder="0" style="border:0"
          src="https://www.google.com/maps/embed/v1/place?q=place_id:ChIJH_Isbe0YoFMRrlJ4-zvuhV4&key=AIzaSyA-J6GMai1cJ2Opjrjd-WulXe01AmUMEFc"
          allowfullscreen></iframe>
      </div>
    </div>
    <div class="col">
      <div class='contact-form'>
        <form action="https://getform.io/f/e64332e1-17cc-413c-8fe8-1085d7f35e7d" method="POST">
          <h1 class="section-heading">Contact us</h1>
          <h1 class="section-title">We're here to help</h1>
          <div class="contact-info">
          <a class  ="contact-link">587-524-5223</a>
            <a class="contact-link">brian@tabletopcafe.ca</a>
            <a class="contact-link">5716 75 Street NW, Edmonton</a>
          </div>
          <label for="full_name">Full Name</label>
          <input type="text" name="full_name">
          <div>
            <label for="email">Email</label>
            <input type="text" name="email">
            <label for="phone">Phone</label>
            <input type="text" name="phone">
          </div>
          <label for="message">Message</label>
          <textarea name="message"></textarea>
          <input class="btn" type="submit">
        </form>
      </div>
    </div>

  </div>
</div>