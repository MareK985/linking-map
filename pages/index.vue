<template>
  <div>
      <section class="hero">
      <div class="hero-inner">
        <h1>LINKING MAP</h1>
        <h2>Challenging the status quo</h2>
        <a href="/case-study-expar" to="/case-study-expar" class="btn">See our projects...</a>
      </div>
    </section>
    <main>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec nibh molestie, efficitur leo sed, viverra nunc. Donec vehicula accumsan erat facilisis ullamcorper. Donec commodo quis dui nec placerat. Donec mi orci, scelerisque eget nisl ac, hendrerit condimentum odio. Nam dictum odio eget quam tempus, a mattis odio ornare. Nullam auctor libero ut libero suscipit, ut accumsan nunc condimentum. Donec ullamcorper maximus sapien quis egestas.</p>
      <p>Mauris viverra scelerisque lobortis. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Fusce ultrices enim sit amet elit tincidunt maximus. Suspendisse vitae pellentesque lectus. Duis commodo leo suscipit augue mollis, non venenatis dolor ullamcorper. Duis tincidunt scelerisque lacus, vel vehicula leo consectetur vel. Duis posuere nisl non odio consequat ultrices. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      <p>Etiam a leo nec mi blandit euismod. Etiam fringilla odio vitae risus ornare, id bibendum velit consequat. Fusce posuere risus sollicitudin condimentum ultrices. Fusce gravida, purus eget laoreet mattis, velit sapien ultrices diam, id dapibus erat leo id quam. Maecenas quis risus convallis, placerat elit non, iaculis tortor. Nullam porttitor magna risus, quis bibendum metus tincidunt in. Etiam vel ligula ac risus mattis tincidunt vel sit amet ante. Morbi et viverra ligula. Ut ac dignissim nisi, condimentum imperdiet mauris. Pellentesque ut ipsum vel diam tristique faucibus eu et lectus. Maecenas posuere neque non lacus bibendum, sit amet pharetra justo semper. Sed mi risus, tempor sit amet ligula eget, varius pretium est. Sed a odio in orci accumsan pretium suscipit ut quam.</p>
    </main>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css?family=Lato:100,300,400,700,900&display=swap');

body {
    margin: 0;
    font-family: Lato;
}
.hero {
    /* Sizing */
    width: 100vw;
    height: 100vh;
    
    /* Flexbox stuff */
    display: flex;
    justify-content: center;
    align-items: center;
    
    /* Text styles */
    text-align: center;
    color: white;
    
    /* Background styles */
    background-image: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5)), url("~assets/img/hero_1.jpg");
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
    background-attachment: fixed;
}
.hero h1 {
    /* Text styles */
    font-size: 5em;
    
    /* Margins */
    margin-top: 0;
    margin-bottom: 0.5em;
}
.hero .btn {
    /* Positioning and sizing */
    display: block;
    width: 200px;
    
    /* Padding and margins */
    padding: 1em;
    margin-top: 50px;
    margin-left: auto;
    margin-right: auto;
    
    /* Text styles */
    color: white;
    text-decoration: none;
    font-size: 1.5em;
    
    /* Border styles */
    border: 3px solid white;
    border-radius: 5px;
    
    /* Background styles */
    background-color: rgba(125, 207, 182, 0.8);
}
  </style>
