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
      Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
    </div>
  </section>
  
  <section data-theme="dark">
    <div class="cha-header-clip" aria-hidden="true">
      <header class="cha-header">
        case study: ExpAR store
      </header>
    </div>
    <div class="cha-text mt-2">
      Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance. The first line of Lorem Ipsum, "Lorem ipsum dolor sit amet..", comes from a line in section 1.10.32.
    </div>
  </section>
  
  <section data-theme="green">
    <div class="cha-header-clip" aria-hidden="true">
      <header class="cha-header">
        case study: ExpAR store
      </header>
    </div>
    <div class="cha-text">
      There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. All the Lorem Ipsum generators on the Internet tend to repeat predefined chunks as necessary, making this the first true generator on the Internet. It uses a dictionary of over 200 Latin words, combined with a handful of model sentence structures, to generate Lorem Ipsum which looks reasonable. The generated Lorem Ipsum is therefore always free from repetition, injected humour, or non-characteristic words etc
    </div>
  </section>
</main>
    </div>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Lato:100,300,400,700,900&display=swap');

body {
    margin: 0;
    font-family: Lato;
}
section {
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

</style>

