<template>
  <!--Promotion header-->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <section class="header-promotion">
              <div class="first dev"><div class="dev">WELCOME TO 168 CLOTHES STORE</div></div>
              <div class="second dev"><div class="dev">NEW PROMOTION IS COMING SOON</div></div>
      </section>  
      <header>
              <!--Store name-->
              <div class="main-header" id="home">
                  <div class="head-right">
                      <h1 class="name-store" style="padding-left: 10px;">168 CLOTHES STORE</h1>
                      <nav class="head-left">
                          <a href="#" style="text-decoration: none; color: black;" class="find-store">Find Store</a> | <a class="english">English</a> | 
                            <button type="submit" class="sign-up" style="font-size: 18px; margin-top: 3px;">Sign In</button>
                      </nav>
                  </div>
              </div>        
      </header>
      <br>
      <body>
          <!--Nav bar -->
              <div class="nav-bar">
                  <nav class="menu">
                    <a class="meu1" href="#home">HOME</a>
                    <a class="meu" href="#men">MEN</a> 
                    <a class="meu" href="#women">WOMEN</a> 
                    <a class="meu" href="#kid">KIDS</a> 
                    <a class="meu" href="#accessories">ACCESSORIES</a> 
                    <a class="meu" href="#AboutUs">ABOUT US</a> 
                  </nav>
          </div>    
          <br>
              <!--Search-->
              <div class="search-part">
                  <h2 class="first-h2" style="font-weight: 900;">MAKE YOUR LIFE HAPPY WITH US</h2>
                  <p class="first-p" style="padding-top: 15px;">Shopping is always a good idea. let's grab something you like.</p>
                  <div class="input-icons">
                      <i class="fa fa-search icon"></i>
                      <input class="search-icon" type="text" placeholder="Search" name="search">
                  </div>
              </div>
              <br>
              <!--Advertise-->
              <div class="commercial">
                  <div class="box1">
                      <img class="women" src="../assets/images/women.jpg" alt="women">
                  </div>
                  <div class="box2">
                      <h3 class="promo">Promotion Of The Month</h3>
                      <p class="bestsell">Best Sell In Shop</p>
                      <button class="shop-now">Shop Now</button>
                  </div>
                  <div class="box3">
                      <img class="men" src="../assets/images/Men-cloth.jpeg" alt="men">
                  </div>
              </div>
              <br>
              <!--slide-->
              <!-- <div class="slideshow-container" style="margin-top: 60px;">
                <transition-group name="fade" tag="div">
                  <div v-for="i in [currentIndex]" :key="i">
                    <img :src="currentImg" />
                  </div>
                </transition-group>
                  <a class="prev" @click="prev" href="#">&#10094; Previous</a>
                  <a class="next" @click="next" href="#">&#10095; Next</a>
              </div>
                  <br>
                  <br>
   -->
                  <!--Benefit-->
                  <div class="benefit">
                      <div class="delivery">
                          <img class="img-deli" src="../assets/images/delivery-icon.png" alt="delivery-icon" style="margin-top: 10px;">
                          <p class="deli-text" style="font-family: 'Oswald', sans-serif;">Free Delivery</p>
                          <p class="deli-text1" style="font-size: 12px;">buy up to 50$</p>
                      </div>
                      <div class="coupon">
                          <img class="img-dis" src="../assets/images/dis.png" alt="discount" style="margin-top: 15px;">
                          <p class="deli-text2" style="font-family: 'Oswald', sans-serif;">Discount Coupon</p>
                          <p class="deli-text-2" style="font-size: 12px;">up to 70%</p>
                      </div>
                      <div class="membership">
                          <img class="img-member" src="../assets/images/member.png" alt="membership" style="margin-top: 14px;">
                          <p class="deli-text3" style="font-family: 'Oswald', sans-serif;">Membership</p>
                          <p class="deli-text-3" style="font-size: 12px;">always get 10% off</p>
                      </div>
                  </div>
                  <br><br>
                  <!--men collection-->
                  <div id="men" class="collection" style="border: 1px solid #d9d9d9;">
                      <div class="title-text">
                          <p style="font-size: 25px; margin: 65px 0 0 60px ; font-weight: 800;">NEW ARRIVAL</p>
                          <p style="font-size: 20px; margin: 30px 0 0 60px;">MEN COLLECTION</p>
                          <p style="font-size: 15px; margin: 15px 0 0 50px;">Check out our men clothes</p>
                          <button class="shoping-button" style="margin: 25px 0 0 70px; padding: 10px 30px 10px 30px; border-radius: 10px; ">SHOP NOW</button>
                      </div>
                      <div class="new-arrive1">
                          <img class="arrival-image" src="../assets/images/men-cloth1.jpeg" alt="men shirt" style="width: 230px; height: 230px; margin: 10px 10px 0 29px; border-radius: 10px;">
                          <p style="margin: 10px 0 5px 120px;">SHIRT</p>
                          <p style="margin: 5px 0 5px 117px;">10,00$</p>
                          <a href="#" style="color: black; font-size: small; margin: 0 0 0 110px;">VIEW MORE</a>
                      </div>
                      <div class="new-arrive2">
                          <img class="arrival-image"  src="../assets/images/Hoodie.webp" alt="men hoodie" style="width: 230px; height: 230px; margin: 10px 10px 0 29px; border-radius: 10px;">
                          <p style="margin: 10px 0 5px 115px;">HOODIE</p>
                          <p style="margin: 5px 0 5px 119px;">20,00$</p>
                          <a href="#" style="color: black; font-size: small; margin: 0 0 0 110px;">VIEW MORE</a>
                      </div>
                      <div class="new-arrive3">
                          <img class="arrival-image"  src="../assets/images/Short.jpeg" alt="men short" style="width: 230px; height: 230px; margin: 10px 10px 0 29px; border-radius: 10px;">
                          <p style="margin: 10px 0 5px 121px;">SHORT</p>
                          <p style="margin: 5px 0 5px 124px;">5,00$</p>
                          <a href="#" style="color: black; font-size: small; margin: 0 0 0 112px;">VIEW MORE</a>
                      </div>
                      <div class="new-arrive4">
                          <img class="arrival-image"  src="../assets/images/men-jeans.webp" alt="men jeans" style="width: 230px; height: 230px; margin: 10px 10px 0 29px; border-radius: 10px;">
                          <p style="margin: 10px 0 5px 120px;">JEANS</p>
                          <p style="margin: 5px 0 5px 117px;">15,00$</p>
                          <a href="#" style="color: black; font-size: small; margin: 0 0 0 110px;">VIEW MORE</a>
                      </div>
                  </div>
                  <br><br>
                  <!--men thing you may like-->
                  <div class="thingYouMayLike">
                      <h2 style="text-align: center;">THING YOU MAY LIKE</h2>
                      <br>
                      <div class="category1">
                          <div class="thing1">
                              <img class="thing-img" src="../assets/images/addidas-shoes.webp" alt="Shoes" style="width: 260px; height: 260px; margin: 10px 50px 0 100px; border-radius: 10px;">
                              <p style="margin: 10px 0 5px 180px;">MEN SHOES</p>
                              <a href="#" style="color: black; font-size: small; margin: 0 0 0 186px;">VIEW MORE</a>
                          </div>
                          <div class="thing2">
                              <img class="thing-img" src="../assets/images/wallet.jpeg" alt="Wallet" style="width: 260px; height: 260px; margin: 10px 50px 0 100px; border-radius: 10px;">
                              <p style="margin: 10px 0 5px 200px;">WALLET</p>
                              <a href="#" style="color: black; font-size: small; margin: 0 0 0 196px;">VIEW MORE</a>
                          </div>
                          <div class="thing3">
                              <img class="thing-img" src="../assets/images/watch.jpg" alt="Watch" style="width: 260px; height: 260px; margin: 10px 50px 0 100px; border-radius: 10px;">
                              <p style="margin: 10px 0 5px 200px;">WATCH</p>
                              <a href="#" style="color: black; font-size: small; margin: 0 0 0 194px;">VIEW MORE</a>
                          </div>
                      </div>
                  </div>
                  <br><br>
                  <!--men trending-->
                  <div class="trending">
                    <h2 style="text-align: center;">TRENDING</h2>
                    <br>
                  </div>
                  <div class="treding-cate">
                    <div class="treding1">
                      <img src="../assets/images/men-treding1.png" alt="men shirt" style="width: 250px; height: 250px; margin: 30px 10px 0 25px; border-radius: 10px;"><br><br>
                      <a href="#" style="color: black; font-size: small; margin: 0 0 0 111px;">VIEW MORE</a>
                    </div>
                    <div class="trending2">
                      <img src="../assets/images/men-treding2.jpeg" alt="men hoodie" style="width: 250px; height: 250px; margin: 30px 10px 0 25px; border-radius: 10px;"><br><br>
                      <a href="#" style="color: black; font-size: small; margin: 0 0 0 111px;">VIEW MORE</a>
                    </div>
                    <div class="trending3">
                      <img src="../assets/images/men-treding3.jpeg" alt="men jeans" style="width: 250px; height: 250px; margin: 30px 10px 0 25px; border-radius: 10px;"><br><br>
                      <a href="#" style="color: black; font-size: small; margin: 0 0 0 111px;">VIEW MORE</a>
                    </div>
                    <div class="trending4">
                      <img src="../assets/images/men-trending4.png" alt="men trouser" style="width: 250px; height: 250px; margin: 30px 10px 0 25px; border-radius: 10px;"><br><br>
                      <a href="#" style="color: black; font-size: small; margin: 0 0 0 111px;">VIEW MORE</a>
                    </div>
                  </div>
                  <br><br><br>
                  <!--women collection-->
                  <div id="women" class="collection" style="border: 1px solid #d9d9d9;">
                      <div class="title-text">
                          <p style="font-size: 25px; margin: 65px 0 0 60px ; font-weight: 800;">NEW ARRIVAL</p>
                          <p style="font-size: 20px; margin: 30px 0 0 45px;">WOMEN COLLECTION</p>
                          <p style="font-size: 15px; margin: 15px 0 0 50px;">Check out our men clothes</p>
                          <button class="shoping-button" style="margin: 25px 0 0 70px; padding: 10px 30px 10px 30px; border-radius: 10px; ">SHOP NOW</button>
                      </div>
                      <div class="new-arrive1">
                          <img class="arrival-image" src="../assets/images/women-shirt.jpeg" alt="women shirt" style="width: 230px; height: 230px; margin: 10px 10px 0 29px; border-radius: 10px;">
                          <p style="margin: 10px 0 5px 122px;">SHIRT</p>
                          <p style="margin: 5px 0 5px 120px;">10,00$</p>
                          <a href="#" style="color: black; font-size: small; margin: 0 0 0 110px;">VIEW MORE</a>
                      </div>
                      <div class="new-arrive2">
                          <img class="arrival-image"  src="../assets/images/women-trouser.webp" alt="women trouser" style="width: 230px; height: 230px; margin: 10px 10px 0 29px; border-radius: 10px;">
                          <p style="margin: 10px 0 5px 109px;">TROUSER</p>
                          <p style="margin: 5px 0 5px 119px;">15,00$</p>
                          <a href="#" style="color: black; font-size: small; margin: 0 0 0 110px;">VIEW MORE</a>
                      </div>
                      <div class="new-arrive3">
                          <img class="arrival-image"  src="../assets/images/women-jacket.webp" alt="women jacket" style="width: 230px; height: 230px; margin: 10px 10px 0 29px; border-radius: 10px;">
                          <p style="margin: 10px 0 5px 120px;">JACKET</p>
                          <p style="margin: 5px 0 5px 122px;">25,00$</p>
                          <a href="#" style="color: black; font-size: small; margin: 0 0 0 112px;">VIEW MORE</a>
                      </div>
                      <div class="new-arrive4">
                          <img class="arrival-image"  src="../assets/images/women-dress.jpeg" alt="dress" style="width: 230px; height: 230px; margin: 10px 10px 0 29px; border-radius: 10px;">
                          <p style="margin: 10px 0 5px 117px;">DRESS</p>
                          <p style="margin: 5px 0 5px 117px;">20,00$</p>
                          <a href="#" style="color: black; font-size: small; margin: 0 0 0 110px;">VIEW MORE</a>
                      </div>
                  </div>
                  <br><br>
                  <!--women thing you may like-->
                  <div class="thingYouMayLike">
                      <h2 style="text-align: center;">THING YOU MAY LIKE</h2>
                      <br>
                      <div class="category1">
                          <div class="thing1">
                              <img class="thing-img" src="../assets/images/women-shoes.avif" alt="women shoes" style="width: 260px; height: 260px; margin: 10px 50px 0 100px; border-radius: 10px;">
                              <p style="margin: 10px 0 5px 165px;">WOMEN SHOES</p>
                              <a href="#" style="color: black; font-size: small; margin: 0 0 0 186px;">VIEW MORE</a>
                          </div>
                          <div class="thing2">
                              <img class="thing-img" src="../assets/images/women-purse.jpeg" alt="purse" style="width: 260px; height: 260px; margin: 10px 50px 0 100px; border-radius: 10px;">
                              <p style="margin: 10px 0 5px 204px;">PURSE</p>
                              <a href="#" style="color: black; font-size: small; margin: 0 0 0 196px;">VIEW MORE</a>
                          </div>
                          <div class="thing3">
                              <img class="thing-img" src="../assets/images/women-watch.jpeg" alt="women watch" style="width: 260px; height: 260px; margin: 10px 50px 0 100px; border-radius: 10px;">
                              <p style="margin: 10px 0 5px 200px;">WATCH</p>
                              <a href="#" style="color: black; font-size: small; margin: 0 0 0 194px;">VIEW MORE</a>
                          </div>
                      </div>
                  </div>
                  <br><br>
                  <!--women trending-->
                  <div class="trending">
                    <h2 style="text-align: center;">TRENDING</h2>
                    <br>
                  </div>
                  <div class="treding-cate">
                    <div class="treding1">
                      <img src="../assets/images/women-treding1.jpeg" alt="women jacket" style="width: 250px; height: 250px; margin: 30px 10px 0 25px; border-radius: 10px;"><br><br>
                      <a href="#" style="color: black; font-size: small; margin: 0 0 0 111px;">VIEW MORE</a>
                    </div>
                    <div class="trending2">
                      <img src="../assets/images/women-trending2.jpeg" alt="women hoodie" style="width: 250px; height: 250px; margin: 30px 10px 0 25px; border-radius: 10px;"><br><br>
                      <a href="#" style="color: black; font-size: small; margin: 0 0 0 111px;">VIEW MORE</a>
                    </div>
                    <div class="trending3">
                      <img src="../assets/images/women-trending3.jpeg" alt="women dress" style="width: 250px; height: 250px; margin: 30px 10px 0 25px; border-radius: 10px;"><br><br>
                      <a href="#" style="color: black; font-size: small; margin: 0 0 0 111px;">VIEW MORE</a>
                    </div>
                    <div class="trending4">
                      <img src="../assets/images/women-trending4.webp" alt="women jacket" style="width: 250px; height: 250px; margin: 30px 10px 0 25px; border-radius: 10px;"><br><br>
                      <a href="#" style="color: black; font-size: small; margin: 0 0 0 111px;">VIEW MORE</a>
                    </div>
                  </div>
                  <br><br>
                  <!--KID COLLECTION-->
                  <div id="kid" class="collection" style="border: 1px solid #d9d9d9;">
                      <div class="title-text">
                          <p style="font-size: 25px; margin: 65px 0 0 60px ; font-weight: 800;">NEW ARRIVAL</p>
                          <p style="font-size: 20px; margin: 30px 0 0 60px;">KID COLLECTION</p>
                          <p style="font-size: 15px; margin: 15px 0 0 50px;">Check out our men clothes</p>
                          <button class="shoping-button" style="margin: 25px 0 0 70px; padding: 10px 30px 10px 30px; border-radius: 10px; ">SHOP NOW</button>
                      </div>
                      <div class="new-arrive1">
                          <img class="arrival-image" src="../assets/images/kid-shirt.webp" alt="kid shirt" style="width: 230px; height: 230px; margin: 10px 10px 0 29px; border-radius: 10px;">
                          <p style="margin: 10px 0 5px 120px;">SHIRT</p>
                          <p style="margin: 5px 0 5px 117px;">10,00$</p>
                          <a href="#" style="color: black; font-size: small; margin: 0 0 0 110px;">VIEW MORE</a>
                      </div>
                      <div class="new-arrive2">
                          <img class="arrival-image"  src="../assets/images/kid-hoodie.jpeg" alt="kid hoodie" style="width: 230px; height: 230px; margin: 10px 10px 0 29px; border-radius: 10px;">
                          <p style="margin: 10px 0 5px 113px;">HOODIE</p>
                          <p style="margin: 5px 0 5px 119px;">15,00$</p>
                          <a href="#" style="color: black; font-size: small; margin: 0 0 0 110px;">VIEW MORE</a>
                      </div>
                      <div class="new-arrive3">
                          <img class="arrival-image"  src="../assets/images/kid-sport.webp" alt="kid sport shirt" style="width: 230px; height: 230px; margin: 10px 10px 0 29px; border-radius: 10px;">
                          <p style="margin: 10px 0 5px 121px;">SPORT</p>
                          <p style="margin: 5px 0 5px 122px;">15,00$</p>
                          <a href="#" style="color: black; font-size: small; margin: 0 0 0 112px;">VIEW MORE</a>
                      </div>
                      <div class="new-arrive4">
                          <img class="arrival-image"  src="../assets/images/kid-jacket.webp" alt="kid jacket" style="width: 230px; height: 230px; margin: 10px 10px 0 29px; border-radius: 10px;">
                          <p style="margin: 10px 0 5px 116px;">JACKET</p>
                          <p style="margin: 5px 0 5px 117px;">20,00$</p>
                          <a href="#" style="color: black; font-size: small; margin: 0 0 0 110px;">VIEW MORE</a>
                      </div>
                  </div>
                  <br><br>
                  <!--kid thing you may like-->
                  <div class="thingYouMayLike">
                      <h2 style="text-align: center;">THING YOU MAY LIKE</h2>
                      <br>
                      <div class="category1">
                          <div class="thing1">
                              <img class="thing-img" src="../assets/images/kid-glasses.jpeg" alt="kid-glasses" style="width: 260px; height: 260px; margin: 10px 50px 0 100px; border-radius: 10px;">
                              <p style="margin: 10px 0 5px 188px;">GLASSES</p>
                              <a href="#" style="color: black; font-size: small; margin: 0 0 0 186px;">VIEW MORE</a>
                          </div>
                          <div class="thing2">
                              <img class="thing-img" src="../assets/images/kid-hat.jpeg" alt="kid-hat" style="width: 260px; height: 260px; margin: 10px 50px 0 100px; border-radius: 10px;">
                              <p style="margin: 10px 0 5px 204px;">HAT</p>
                              <a href="#" style="color: black; font-size: small; margin: 0 0 0 196px;">VIEW MORE</a>
                          </div>
                          <div class="thing3">
                              <img class="thing-img" src="../assets/images/kid-watch.jpeg" alt="Wakid-watch" style="width: 260px; height: 260px; margin: 10px 50px 0 100px; border-radius: 10px;">
                              <p style="margin: 10px 0 5px 200px;">WATCH</p>
                              <a href="#" style="color: black; font-size: small; margin: 0 0 0 194px;">VIEW MORE</a>
                          </div>
                      </div>
                  </div>
                  <br><br>
                  <!--kid trending-->
                  <div class="trending">
                    <h2 style="text-align: center;">TRENDING</h2>
                    <br>
                  </div>
                  <div class="treding-cate">
                    <div class="treding1">
                      <img src="../assets/images/kid-trending1.jpeg" alt="kid shirt" style="width: 250px; height: 250px; margin: 30px 10px 0 25px; border-radius: 10px;"><br><br>
                      <a href="#" style="color: black; font-size: small; margin: 0 0 0 111px;">VIEW MORE</a>
                    </div>
                    <div class="trending2">
                      <img src="../assets/images/kid-trending2.webp" alt="kid hoodie" style="width: 250px; height: 250px; margin: 30px 10px 0 25px; border-radius: 10px;"><br><br>
                      <a href="#" style="color: black; font-size: small; margin: 0 0 0 111px;">VIEW MORE</a>
                    </div>
                    <div class="trending3">
                      <img src="../assets/images/kid-trending3.jpeg" alt="kid jacket" style="width: 250px; height: 250px; margin: 30px 10px 0 25px; border-radius: 10px;"><br><br>
                      <a href="#" style="color: black; font-size: small; margin: 0 0 0 111px;">VIEW MORE</a>
                    </div>
                    <div class="trending4">
                      <img src="../assets/images/kid-trending4.jpeg" alt="kid dress" style="width: 250px; height: 250px; margin: 30px 10px 0 25px; border-radius: 10px;"><br><br>
                      <a href="#" style="color: black; font-size: small; margin: 0 0 0 111px;">VIEW MORE</a>
                    </div>
                  </div>
                  <br><br><br><br>
                  <!--Accessories-->
                  <div id="accessories" class="trending">
                    <h2 style="text-align: center;">ACCESSORIES</h2>
                    <br>
                  </div>
                  <div class="treding-cate">
                    <div class="treding1">
                      <img src="../assets/images/bag.jpeg" alt="bag" style="width: 250px; height: 250px; margin: 30px 10px 0 25px; border-radius: 10px;"><br><br>
                      <a href="#" style="color: black; font-size: small; margin: 0 0 0 111px;">VIEW MORE</a>
                    </div>
                    <div class="trending2">
                      <img src="../assets/images/hat.jpeg" alt="hat" style="width: 250px; height: 250px; margin: 30px 10px 0 25px; border-radius: 10px;"><br><br>
                      <a href="#" style="color: black; font-size: small; margin: 0 0 0 111px;">VIEW MORE</a>
                    </div>
                    <div class="trending3">
                      <img src="../assets/images/small-bag.jpeg" alt="small bag" style="width: 250px; height: 250px; margin: 30px 10px 0 25px; border-radius: 10px;"><br><br>
                      <a href="#" style="color: black; font-size: small; margin: 0 0 0 111px;">VIEW MORE</a>
                    </div>
                    <div class="trending4">
                      <img src="../assets/images/sunglasses.jpeg" alt="sunglasses" style="width: 250px; height: 250px; margin: 30px 10px 0 25px; border-radius: 10px;"><br><br>
                      <a href="#" style="color: black; font-size: small; margin: 0 0 0 111px;">VIEW MORE</a>
                    </div>
                    
                  </div>
                  <br><br><br>
                  <!--About Us-->
                  <section id="AboutUs">
                      <div class="about-container">
                          <div class="box">
                            <h3 class="upper-text">follow us on</h3>
                              <a href="#"><i class="fa fa-facebook"></i> FACEBOOK</a>
                              <a href="#"><i class="fa fa-instagram"></i> INSTAGRAM</a>
                          </div>
                          <div class="box">
                            <h3 class="upper-text">BANK WE ACCEPTED</h3>
                            <img class="leading-img" src="../assets/images/aba.png" alt="ABA BANK">
                            <img src="../assets//images/canadian.jpeg" alt="CANADIAN BANK">
                            <img src="../assets/images/wing.png" alt="WING BANK">
                            <img src="../assets/images/aceleda.png" alt="ACELEDA BANK">
                            <img src="../assets/images/ftb.png" alt="FTB BANK">
                            <h3 class="upper-text">PAYMENT METHOD WE ACCEPTED</h3>
                            <img class="leading-images" src="../assets/images/visa.png" alt="VISA">
                            <img src="../assets/images/mastercard.png" alt="MASTERCARD">
                            <img src="../assets/images/paypal.png" alt="PAYPAL">
                          </div>
                      </div>
                  </section>
                </body>

  </template>
  <script>
  
  </script>
  <style>
  @import url('https://fonts.googleapis.com/css2?family=Inria+Sans:wght@300&family=M+PLUS+Rounded+1c&display=swap');
  *{
      margin: 0;
      padding: 0;
      outline: 0;
      border: 0;
  }
  body, button{
      font-family: 'Inria Sans', sans-serif;
  }
  /* Promotion header */
  .header-promotion {
      width: 100vw;
      height: 30px;
      background-color: black;
      color: white;
      overflow:hidden;
      text-align: center;
  }
  header, .head-right{
    display: flex;
  }
  .head-left{
    position: absolute;
    right: 10px;
    margin-top: 3px;
    font-size: 18px;
  }
  .sign-up{
    width: 80px;
    height: 30px;
    background-color: #d9d9d9;
    padding-bottom: 3px;
  }
  .sign-up:hover{
    background-color: #757474;
  }
  .header-promotion > .dev > .dev {
      padding: 5px 5px;
      height:2.81rem;
      margin-bottom: 2.81rem;
      display:inline-block;
  }
  .header-promotion .dev:first-child {
      animation: text-animation 10s infinite;
  }
  @keyframes text-animation {
      0% {margin-top: 0;}
      10% {margin-top: 0;}
      20% {margin-top: -5.62rem;}
      30% {margin-top: -5.62rem;}
      40% {margin-top: 0rem;}
      60% {margin-top: 0rem;}
      70% {margin-top: -5.62rem;}
      80% {margin-top: -5.62rem;}
      90% {margin-top: 0;}
      100% {margin-top: 0;}
  }
  /* nav bar  */
    .nav-bar{
      width: 100vw;
    }
    .meu{
      text-decoration: none;
      color: black;
      margin-left: 13.5rem;
    }
    .meu1{
      text-decoration: none;
      color: black;
      margin-left: 1rem;
    }
    .meu:hover, .meu1:hover{
      color: black;
      text-decoration: underline;
      font-weight: bolder;
      font-size: 18px;
    }
    .menu{
      padding-left: 10px;
      display: flex;
      justify-content: flex-start;
      box-shadow: 2px 2px rgb(210, 213, 213) ;
    }
  
  /* Search  */
  .search-part{
        padding-top: 10px;
        width: 100vw;
        height: 180px;
        margin-top: 50px;
        display: block;
        justify-content: center;
        text-align: center;
        background-color: #f2f2f2;
    }
  .input-icons i {
      position: absolute;
  }
    
  .input-icons {
      width: 100%;
      margin-bottom: 10px;
  }
    
  .icon {
      padding: 16px 0 15px 10px;
      min-width: 40px;
      margin-top: 35px;
      
  }
  .search-icon {
      text-align: center;
      margin-top: 35px;
      width: 40vw;
      height: 50px;
      font-family: 'Inria Sans', sans-serif;
      font-size: 20px;
      font-weight: 900;
      border-radius: 10px;
      background-color: #dad8d8;
      border: 1px solid black;
  } 
  /* advertise */
  .commercial{
    width: 100vw;
      height: 317px;
      margin-top: 50px;
      display: flex;
      flex-direction: row;
      justify-content: space-around;
      background: linear-gradient(
          to right,
          #82A8B4 0%,
          #82A8B4 50%,
          #d9d9d9 50%,
          #d9d9d9 100%
      );
  }
  .bestsell{
    text-align: center;
    margin-top: 20px;
    font-weight: 900;
    font-size: larger;
  }
  .shop-now{
    margin: auto;
    margin-top: 20px;
    font-family: 'Inria Sans', sans-serif;
    width: 100px;
    height: 30px;
    border: 0;
    background-color: #c1bdbd;
    justify-content: center;
    text-align: center;
    display: flex;
    padding: 4px 0 4px 0;
    border-radius: 10px;
    font-weight: 900;
  }
  .promo{
    padding-top: 100px;
    text-align: center;
    font-weight: 900;
    font-size: larger;
  }
  .men, .women{
    display: block;
    height: 317px;
    width: 217px;
    
  }
  .box1, .box2, .box3 {
    width: 217px;
    height: 317px;
  }
  .box1{
    margin-left: 50px;
  }
  .box3{
    margin-right: 50px;
  }
  button:hover{
    background-color: #757474;
  }
  /* slide */
  
  /* benefit */ 
  .benefit{
    margin-top: 50px;
    width: 100vw;
    display: flex;
    height: 150px;
  
  }
  .delivery, .coupon ,.membership{
    width: 33.33%;
    height:150px;
  }
  .img-deli{
    display: block;
    margin: auto;
  }
  .img-dis{
    display: block;
    margin: auto;
  }
  .img-member{
    display: block;
    margin: auto;
    width: 64px;
    height: 64px;
  }
  .deli-text{
    margin-left: 41%;
    margin-top: 5px;
  }
  .deli-text1{margin-left: 43%;}
  .deli-text2{margin-left: 38%;}
  .deli-text-2{margin-left: 45%;}
  .deli-text3{margin-left: 41%;}
  .deli-text-3{margin-left: 40%;}
  /*men colllection*/
  .collection{
    width: 100vw;
    height: 340px;
    display: flex;
    justify-content: space-around;
    background-color: #f6f6f6;
  }
  .title-text, .new-arrive1, .new-arrive2, .new-arrive3, .new-arrive4{width: 20%;}
  .shoping-button{background-color: #d9d9d9;}
  .shoping-button:hover{background-color: #757474;}
  .arrival-image{box-shadow: 5px 10px 18px #757474;}
  /* thing you may like*/
  .category1{
    width: 100vw;
    height: 340px;
    display: flex;
    justify-content: space-between;
    background-color: #d9d9d9;
  }
  .thing-img{border: 1px solid #d9d9d9;
    box-shadow: 5px 10px 18px #757474;}
  .thing1, .thing2, .thing3{
    width: 33.33%;
  }
  /* trending*/
  .treding-cate{
    width: 100vw;
    height: 340px;
    display: flex;
    justify-content: space-around;
    background-color: #d9d9d9;
  }
  /*about us*/
  .about-container{
    width: 100vw;
    height: 340px;
    display: flex;
    background-color: #757474;
  }
  .about-container .box{
    width: 50vw;
    height: 100%;
  }
  .about-container a,h3{
    display: block;
    text-align: center;
  }
  .about-container a{
    margin: 2em;
    text-decoration: none;
    color: black;
  }
  .about-container h3{
    margin: 3rem 4rem 3rem 4rem;
  }
  .about-container .fa:hover{
    opacity: 0.7;
  }
  .about-container .fa-facebook{
    background-color: #3b5998;
    color: white;
  }
  .about-container .fa-instagram{
    background-color: #e4405f;
    color: white;
  }
  .about-container .fa{
    padding: 5px;
    font-size: 20px;
    width: 20px;
    border: none;
    border-radius: 10px;
    text-align: center;
    margin: 5px auto;
  }
  .about-container img{
    max-width: 10%;
    height: 10%;
    margin-right: 5%;
  }
  .about-container .leading-img{
    padding-left: 30%;
  }
  .about-container .leading-images{
    padding-left: 35%;
  }
  .about-container .box{
    border: 2px solid #82A8B4;
  }
  </style>