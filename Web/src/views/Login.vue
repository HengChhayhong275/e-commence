<template>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <div class="Login">
    <section id="header">
      <div class="first dev"><div class="dev">WELCOME TO 168 CLOTHES STORE</div></div>
      <div class="second dev"><div class="dev">NEW PROMOTION IS COMING SOON</div></div>
    </section>
    <header>
      <div  class="store-name">
        <h1>168 CLOTHES STORE</h1>
      </div>
      <div class="right-side">
        <a href=""><i class="fa fa-map-marker"></i> Find Store</a> | <a>English</a>
      </div>
    </header>
    <!-- <button @click="$emit('cancel')">Cancel</button> -->
  </div>
  <br/>
  <br/>
  <section id="body">
    <div class="image">
      <img src="../assets/images/login-picture.png" alt="">
    </div>
    <div class="login">
      <div class="login-container">
        <h3 class="upper-text">sign in</h3>
          <form action="#">
            <label for="email">Email</label>
            <input type="email" id="email" name="email" placeholder="Enter Your Email">
            <label for="password">Password</label>
            <input type="password" id="password" name="password" placeholder="Enter Your Password">
            <a href="#">Forget Password?</a>
            <!-- <button @click="$emit('cancel')">Cancel</button> -->
            <button type="submit" class="upper-text">sign in</button>
            <button class="upper-text">sign up</button>
          </form>
      </div>
    </div>
  </section>

</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inria+Sans:wght@300&family=M+PLUS+Rounded+1c&display=swap');

@media (min-width: 1024px) {
  .Login {
  }
}
*{
  margin: 0;
  padding: 0;
  outline: 0;
  border: 0;
  }
.Login{
  height: 4vh;
}
#header{
  width: 100vw;
  height: 100%;
  background-color: black;
  color: white;
  overflow: hidden;
  text-align: center;
  font-size: large;
}
#header > .dev > .dev{
  padding: 5px 5px;
  height: 2.81rem;
  margin: 2.81rem;
  display: inline-block; 
}
#header .dev:first-child{
  animation: text-animation 10s infinite;
}
@keyframes text-animation{
  0%  {margin-top: 0;}
  10% {margin-top: 0;}
  20% {margin-top: -5.62rem;}
  30% {margin-top: -5.62rem;}
  40% {margin-top: 0;}
  60% {margin-top: 0;}
  70% {margin-top: -5.62rem;}
  80% {margin-top: -5.62rem;}
  90% {margin-top: 0;}
  100% {margin-top: 0;}
}
header h1{
  margin-left: 1rem;
}
header{
  display: flex;
}

.right-side, .store-name, .image, .login{
  width: 50%;
}
.right-side a{
  color: black;
  text-decoration: none;
  font-size: larger;
}
.right-side{
  text-align: end;
  margin-right: 1rem;
  margin-top: 5px;
}
#body{
  width: 100%;
  height: 80vh;
  margin-top: 2rem;
  display: flex;
}
.image, .login{
  width: 50%;
}
.upper-text{
  text-transform: uppercase;
}
/* .image{
  border: 1px solid black;
} */
.image img{
  width: 70%;
  height: 70%;
  margin: 15%;
}

.login-container{
  width: 60%;
  height: 63%;
  margin: 16% auto;
  padding: 20px;
  background-color: #F5F5F5;
  border: 1px solid #ccc;
  border-radius: 10%;
  font-size: x-large;
}
.login-container h3{
  text-align: center;
  padding: 10px 0 20px 0;
}
.login-container input[type=email], input[type=password]{
  width: 95%;
  padding: 10px;
  margin: 10px 0;
  border: 1px solid #8f8989;
  font-family: 'Inria Sans', sans-serif;
}
.login-container button{
  width: 45%;
  padding: 5px;
  margin: 10px;
  background-color: #c1bfbf;
  color: white;
  border: none;
  font-size: x-large;
  border-radius: 10px;
}
.login-container button:hover{
  opacity: 0.8;
}
.login-container a{
  display: block;
  text-align: end;
  font-size: medium;
  margin-bottom: 25px;
  text-decoration: none;
}

</style>