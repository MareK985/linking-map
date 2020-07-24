<template>
    <div>
        <section class="hero-section">
            <div class="card-grid">
                <a class="card"       
                @click="showModal"
>
                    <div class="card__background expar-img"></div>
                    <div class="card__content">
                        <p class="card__category">Digital solutions</p>
                        <h3 class="card__heading">Expar Store</h3>
                        <p class="card__description">Multi-unit & on-demand <br/> m-commerce platform. <br/><br/>Web application for clients <br/> specialized in short-term rental business</p>

                    </div>
                </a>
                <a class="card" href="#">
                    <div class="card__background" style="background-image: url(https://images.unsplash.com/photo-1557187666-4fd70cf76254?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60)"></div>
                    <div class="card__content">
                        <p class="card__category">Category</p>
                        <h3 class="card__heading">Example Card Heading</h3>
                    </div>
                </a>
                <!-- <a class="card" href="#">
                    <div class="card__background" style="background-image: url(https://images.unsplash.com/photo-1556680262-9990363a3e6d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60)"></div>
                    <div class="card__content">
                        <p class="card__category">Category</p>
                        <h3 class="card__heading">Example Card Heading</h3>
                    </div>
                </a>
                <a class="card" href="#">
                    <div class="card__background" style="background-image: url(https://images.unsplash.com/photo-1557004396-66e4174d7bf6?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60)"></div>
                    <div class="card__content">
                        <p class="card__category">Category</p>
                        <h3 class="card__heading">Example Card Heading</h3>
                    </div>
                </a> -->
            </div>
        </section>
        <section>
            <div id="app">
              <modal
                v-show="isModalVisible"
                @close="closeModal"
              >
                <template v-slot:header>
                  <h2>Case study #1: <span style="font-size: 1.5em;">ExpAR Store</span></h2>
                </template>
                <template v-slot:body>
                  <b-container class="bv-example-row">
                    <b-row>
                      <b-col sm="8" class="block">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ad veniam repellendus eius reprehenderit. Aliquam vero cumque incidunt, in molestiae ipsa laboriosam aut exercitationem neque, iste officiis? Veniam dolores hic aspernatur.</b-col>
                      <b-col sm="4" class="block">Lorem ipsum dolor sit amet consectetur adipisicing elit. Rem veritatis a, ad eligendi voluptatum deserunt labore! Deserunt, sit fugit atque fugiat, reiciendis deleniti reprehenderit architecto quaerat aperiam a, culpa praesentium.</b-col>
                    </b-row>

                    <b-row>
                      <b-col sm class="block">Lorem ipsum dolor sit amet consectetur adipisicing elit. Rem, aliquam eum incidunt qui laboriosam odio rerum cumque commodi accusamus, alias omnis, consequuntur mollitia pariatur corrupti sit consequatur perferendis numquam praesentium?</b-col>
                      <b-col sm class="block">Lorem ipsum dolor sit amet consectetur adipisicing elit. Et consequuntur minima facere id iusto debitis vitae, temporibus impedit nobis aperiam, ratione pariatur perferendis velit voluptate ut explicabo nulla recusandae non?</b-col>
                      <b-col sm class="block">Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam sit obcaecati perspiciatis consectetur ducimus possimus velit. Necessitatibus aliquid suscipit pariatur fugiat sed a neque ex laboriosam harum et? Harum, error.</b-col>
                    </b-row>
                  </b-container>
                </template>
                </modal>
            </div>
            
        </section>
    </div>
</template>

<script>
import modal from '~/components/Modal.vue'

  export default {
    name: 'app',
    components: {
      modal,
    },
    data () {
      return {
        isModalVisible: false,
      };
    },
    methods: {
      showModal() {
        this.isModalVisible = true;
      },
      closeModal() {
        this.isModalVisible = false;
      }
    },
  };
</script>

<style lang="css" scoped>

/* :root{
  --background-dark: #2d3548;
  --text-light: rgba(255,255,255,0.6);
  --text-lighter: rgba(255,255,255,0.9);
  --spacing-s: 8px;
  --spacing-m: 16px;
  --spacing-l: 24px;
  --spacing-xl: 32px;
  --spacing-xxl: 64px;
  --width-container: 1200px;
} */

*{
  border: 0;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

 html{
  height: 100%;
  font-family: 'Montserrat', sans-serif;
  font-size: 14px;
} 
 body{
  height: 100%;
}

.hero-section{
  align-items: flex-start;

  /* background-image: linear-gradient(15deg, #0f4667 0%, #2a6973 150%); */
  display: flex;
  min-height: 100%;
  justify-content: center;
  padding: 64px 24px;
}

.card-grid{
  display: grid;
  grid-template-columns: repeat(1, 1fr);
  grid-column-gap:  64px;
  grid-row-gap:  64px;
  max-width: 1200px;
  width: 100%;
}

.expar-img {
    background-image: linear-gradient(rgba(0, 0, 0, 0.1),rgba(0, 0, 0, 0.1)), url("~assets/img/hero-expar.jpg");
}

.block {
  background: white;
  margin: 1em;
}

@media(min-width: 420px){
  .card-grid{
    grid-template-columns: repeat(1, 1fr);
    margin: 4em;
    grid-row-gap: 12em;
  }
}

@media(min-width: 780px){
  .card-grid{
    grid-template-columns: repeat(2, 1fr); 
  }
}

@media(min-width: 960px){
  .card-grid{
    grid-template-columns: repeat(3, 1fr); 
  }
}

.card{
  list-style: none;
  position: relative;
  cursor: pointer;
}

.card:before{
  content: '';
  display: block;
  padding-bottom: 150%;
  width: 100%;
}

.card__background{
  background-size: cover;
  background-position: center;
  border-radius: 38px;
  bottom: 0;
  filter: brightness(0.75) saturate(1.2) contrast(0.85);
  left: 0;
  position: absolute;
  right: 0;
  top: 0;
  transform-origin: center;
  transform: scale(1.1) translateZ(0);
  transition: 
    filter 200ms linear,
    transform 200ms linear;
}

.card:hover .card__background{
  transform: scale(1.12) translateZ(0);
}

.card-grid:hover > .card:not(:hover) .card__background{
  filter: brightness(0.5) saturate(1) contrast(1.2) blur(10px);
}

.card__content{
  left: 0;
  padding:  24px;
  position: absolute;
  top: 0;
}

.card__category{
    color: white;
  font-size: 1.3rem;
  margin-bottom: 8px;
  letter-spacing: 1vw;
  text-transform: uppercase;
}

.card__heading{
  color: white;
  font-weight: 600;
  font-size: 2.6rem;
  margin-top: 1.3em;
  text-shadow: 2px 2px 20px rgba(0,0,0,0.2);
  line-height: 1.4;
}

.card__description {
  color: white;
  font-weight: 300;
  font-size: 1.5rem;
  margin-top: 2em;
  text-shadow: 2px 2px 20px rgba(0,0,0,0.2);
  line-height: 1.3;
}

</style>