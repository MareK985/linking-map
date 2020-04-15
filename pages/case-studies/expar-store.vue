<template>
    <div>
      <div class="hero">
        <figure>
         <img class="hero-image" src="~assets/img/hero-expar.jpg" alt="hero-expar" />          
         <figcaption>
           <div class="hero-title">
            <h1 class="headline">Expar store</h1>
            <p class="tagline">experience shopping in your unit</p>
           </div>
          </figcaption>
          <div class="banner-wrapper">
            <div class="banner">Platform is specialized for mobile-first multi-unit on-demand shopping from collection of high-quality local product with a great value. 
            Concepts of ˝shoppable˝ apartment, storytelling and latest AR technologies solution deliveres convenient and almost magical customer 
            experience in the comfort of their temporary stay where near enough everything is up for sale.</div>
          </div>
        </figure>
      </div>
      <main>
        <!-- CHALLENGE SECTION -->
        <section>
          <div class="cha-header-clip">
            <header class="cha-header">
              case study: ExpAR store
            </header>
          </div>
          <div class="sector-title mt-2">
            <h2 class="title">Challenge</h2>
          </div>
        
          <div class="cha-text mt-2">
            <div class="wrapper-box">
              <h1>Mission</h1>
              <p>To provide superior value for the customers (unit owners) for an affordable price, creating a 
                win-win scenario which will boost the <strong>overall profitability and viability of their business </strong>.</p>
            </div>
          </div>
          <br/>
          <div class="cha-text mt-2">
            <h1>Background</h1>
            <p>In the rise of boutique tourist destinations, personalization, bleisure travel customers nowdays seeking unique accomodations which can provide authentic interactions with local culture. For our client specialized in 
              <strong>short-term rental business</strong> who identified this increasing demand we are developing solution to enhance Cx, Bx and overall value of their service.</p>
          </div>
          <br/>
          <div class="cha-text mt-2">
              <h1>Business goal</h1>
              <p> Increase profitability / viability of the business.</p>
          </div>
          <br/>
          <div class="cha-text mt-2">
            <h3>Success metric</h3>
            <p>Average Order Value (AOV) increased by <strong>10%</strong>.</p>
          </div>
          <br/>
          <div class="cha-text mt-2">
              <h1>Timeline</h1>
              <ul>
                <li>Within 6 months <strong>MVP testing in 10 units</strong>.
                </li>
                <li>Within 12 months <strong>launch of platform</strong> and offering service to other clients.</li>
              </ul>
          </div>
        </section>
        <!-- end of CHALLENGE SECTION -->
        
        <!-- RESEARCH SECTION -->
        <section class="content" data-theme="dark">
          <div class="cha-header-clip" aria-hidden="true">
            <header class="cha-header">
              case study: ExpAR store
            </header>
          </div>
          <!-- 1st paragraph-->
          </br>
          <section class="paragraph">
            <div class="left">
              <img src="~/assets/img/path.jpg" width="400px" alt="image" class="image amim" data-delay="0s"/>
              <p class="anim" data-delay=".5s">Line in section 1.10.32.
              </p>
              <img src="~/assets/img/logo-1.svg" width="400px" alt="symbol" class="symbol anim" data-delay=".7s"/>
            </div>
            <div class="right">
              <div class="anim" data-delay="1s">
                <h2>Activity#1: Interviews</h2>
                <p>T you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses a dictionary of over 200 Latin words, combined with a handful of model sentence structures, to generate Lorem Ipsum which looks reasonable. The generated Lorem Ipsum is therefore always free from repetition, injected humour, or non-characteristic words etc
                </p>
              </div>
            </div>
          </section>
            <!-- END 1st paragraph-->
          <!-- 2nd paragraph-->

            <!-- END 2nd paragraph-->
        </section>

        <section data-theme="green">
          <div class="cha-header-clip" aria-hidden="true">
            <header class="cha-header">
              case study: ExpAR store
            </header>
          </div>
          <div style="background-color:#e5e5e5;padding:15px;text-align:center;">
            <h1>Hello World</h1>
          </div>

          <div style="overflow:auto">
            <div class="menu">
              <a href="#">Link 1</a>
              <a href="#">Link 2</a>
              <a href="#">Link 3</a>
              <a href="#">Link 4</a>
            </div>

            <div class="main">
              <h2>Lorum Ipsum</h2>
              <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.</p>
            </div>

            <div class="right">
              <h2>About</h2>
              <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</p>
            </div>
          </div>

          <div class="box">
            <div class="wrapper-box">
              <h1>Mission</h1>
              <p>To provide superior value for the customers (unit owners) for an affordable price, creating a win-win scenario which will boost the overall profitability and viability of their business</p>
            </div>
          </div>

          <div style="background-color:#e5e5e5;text-align:center;padding:10px;margin-top:7px;">© copyright w3schools.com</div>
        </section>
        <footer>
          <div class="shape">
          <div class="content">
            ExpAR store ©2020 
          </div>
          </div>
        </footer>


      </main>
    </div>
</template>

<script>


export default {
  layout: 'case-study'
  // page component definitions
}
//Intersection observer API//
 //  const images = document.querySelectorAll('.anim');

 //  observer = new IntersectionObserver((entries) => {
 //    entries.forEach(entry => {
 //      if(entry.intersectionRatio > 0) {
//       entry.target.style.animation = `anim1 2s $(entry.target.dataset.delay} forwards ease-out`;
 //      }
 //      else {
 //        entry.target.style.animation = 'none';
 //      }
//    })
// })

// images.forEach(image => {
//  observer.observe(image)
// })


</script>


<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Lato:100,300,400,700,900&display=swap');

body {
   // height: 100vh;
    margin: 0;
    font-family: Lato;
    text-align: justify;
}

.hero-title {
  margin-top: -45%;
}

.headline {
    font-size: 9vw;
  }
.tagline {
    font-size: 5vw;
  }

.sector-title {
margin-top: 0%;

  .title {
      color: rgb(125, 115, 160);
  font-size: 10vw;
  text-transform: lowercase;
  letter-spacing: 0.1rem;
  }
}

//banner in hero
.banner {
  background: rgba(125, 115, 160, 0.7);;
  margin-top: -60%;
  position: absolute;
  line-height: 1.5em;
  letter-spacing: 0.08em;
  font-weight: 400;
  font-size: 2.5vw;
  padding: 6rem;
}

@media screen and (max-width: 600px) {
  .banner {
    padding: 2em;
    letter-spacing: 0.09em;
    font-weight: 300;
    font-size: 3vw;
    line-height: 15px;
  }
}

.banner-wrapper {
  margin: 20px;
}
// slanted edge here
.hero img {
  clip-path: polygon(0 0, 100% 0, 100% 90%, 0 100%);
}

.hero {
  color: #fff;
  position: relative;
  text-align: center;
  height: 100%;
  text-shadow: 0px 0px 1px rgba(0,0,0,0.5);
  
  img {
    width: 100%;
  }

  figure {
    width: 100%;
    margin:0;
  }
  
  figcaption {
    left: 50%;
    position: absolute;
    top: 50%;
    transform: translate(-50%, -50%);
    width: 100%;
  }
    
  p {
    font-size: 25px;
    font-weight: 300;
    margin-top: 0.5em;
    line-height: 120%;
  }
}

 strong {
       font-size: 20px;
       color: #454655;

 }

section {
  width: 80%;
  margin: 0 auto;
  position: relative;
  padding: 50px;

  &[data-theme="dark"] {
    background: rgb(125, 115, 160);;
    color: white;

    .cha-header {
      background: rgb(125, 115, 160);;
    }
  }

  &[data-theme="green"] {
    background: white;
    color: green;

    .cha-header {
      background: white;
    }
  }
}

.box {
  background-color: skyblue;
  margin-top: 50px;
  padding: 5% 20px; /* Added a percentage value for top/bottom padding to keep the wrapper inside of the parent */
  
  -webkit-transform: skewY(-5deg);
  -moz-transform: skewY(-5deg);
  -ms-transform: skewY(-5deg);
  -o-transform: skewY(-5deg);
  transform: skewY(-5deg);
}

.box > .wrapper-box {
  -webkit-transform: skewY(5deg);
  -moz-transform: skewY(5deg);
  -ms-transform: skewY(5deg);
  -o-transform: skewY(5deg);
  transform: skewY(5deg);
}

.content {
  //display: grid;
  //grid-template-columns: 70% auto;

    .left {
      position: relative;
      text-align: center;
      display:grid;
      float: left;
      place-items: center;
      width: 60%; /* The width is 20%, by default */

      p {
        background: white;
        position: absolute;
        margin-top: -35%;
        right: 5%;
        color: black;
        padding: 1em;
        border-radius: 15px;
        width: 20vw;
        text-align: left;
      }

    }
    .image {
      width: 80%;
      max-width:100%;
      height:auto;
     // opacity: 0;
    }
    .symbol {
      position:absolute;
      margin-top: 32;
      left: 19%;
      width: 35vh;
    }
    .right {
      display: grid;
      place-items: center;
      float: left;
      width: 40%; /* The width is 4%, by default */

      h2 {
        color: white;
        font-size: 1.7rem;

      }
    }

.anim {
  // opacity: 0;
}

@media screen and (max-width: 800px) {
  .left, .right {
    width: 100%; /* The width is 100%, when the viewport is 800px or smaller */
  }
}

@keyframes anim1 {
  from {
    transform: translateY(-100px);
    opacity: 0;
  }
  to {
    transform: translateY(0);
    opacity: 1;
  }
 
}

}

.cha-header-clip {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  pointer-events: none;
  z-index: 20;
  clip-path: polygon(0% 0%, 100% 0%, 100% 100%, 0% 100%);
}

.cha-header {
  background: white;
  font-size: 24px;
  text-align: center;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 1;
}

.cha-text {
  font-size: 18px;
  max-width: 700px;
  margin: 0 auto;
}

// FOOTER // 
.shape {
  position: relative;
  width: 100%;
  height: 290px;
  background-image: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5)), url("~assets/img/hero-expar.jpg");  background-size: 100% 290px;
  color: #fff;
}

footer { 
  display: flex;
  height: 100%;
  align-items: center;
  justify-content: center;
  width: 100%;

}

.shape:before {
  position: absolute;
  width: 100%;
  height: 20%;
  content: "";
  background: linear-gradient(to right bottom, rgba(255, 255, 255, 1) 50%, transparent 50%);
}


</style>

