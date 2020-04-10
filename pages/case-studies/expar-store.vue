<template>
    <div>
      <main>
        <section>
          <div class="cha-header-clip">
            <header class="cha-header">
              case study: ExpAR store
            </header>
          </div>
          <div class="cha-text mt-2">
            Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance. The first line of Lorem Ipsum, "Lorem ipsum dolor sit amet..", comes from a line in section 1.10.32.
          </div>
        </section>
        
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

  <div style="background-color:#e5e5e5;text-align:center;padding:10px;margin-top:7px;">© copyright w3schools.com</div>
        </section>
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
}
section {
  width: 80%;
  height: 100vh;  //makes section full height!!!
  margin: 0 auto;
  position: relative;
  padding: 50px;

  &[data-theme="dark"] {
    background: black;
    color: white;

    .cha-header {
      background: black;
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

.paragraph {
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
// group transitions//


</style>

