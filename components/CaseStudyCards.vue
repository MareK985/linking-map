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
                <!-- 2ND card -->
                <!-- <a class="card" href="#">
                    <div class="card__background" style="background-image: url(https://images.unsplash.com/photo-1557187666-4fd70cf76254?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60)"></div>
                    <div class="card__content">
                        <p class="card__category">Category</p>
                        <h3 class="card__heading">Example Card Heading</h3>
                    </div>
                </a> -->
                <!-- end of 2nd card -->
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
                      <b-col sm="5" class="block">
                        <h3>CLIENT</h3>
                        <p >Specialized in <strong>short-term rental business</strong>, mostly through platforms such as AirBnB and Booking.</strong></p>
                      </b-col>
                      <b-col sm="5" class="block">
                        <h3>TIMELINE</h3>
                        <p style="text-align: left;">+3 months: <strong>Proof-of-Concept (PoC) testing</strong> </br>
                        +6 months: <strong>Testing of Min. Viable Product (MVP)</strong> in 10 units</br>
                        +12 months: <strong>Product Launch </strong></p>
                      </b-col>
                    </b-row>
                    <b-row>
                      <b-col sm="6" class="block">
                        <h3>BUSINESS CONTEXT</h3>
                        <p>In the rise of boutique turistic destinations, personalization, bleisure travel etc. customers nowdays seeking unique experiences also through accomodations. To provide superior value for the client customers (unit owners) for an affordable price, creating a win-win scenario which will <strong>boost the overall profitability and viability of their business.</strong></p>
                      </b-col>
                      <b-col sm="5" class="block">
                        <h3>OBJECTIVES (OKRs)</h3>
                        <p style="text-align: left;">Objective 1#: <strong>increase business viability</strong> by increase of: <br/> - profit (+10%), <br/> - average purchase value (+10 EUR/day), <br/> - no. of operating units (+ 20%/year)</p>
                        <br/>
                        <p style="text-align: left;">Objective 2#: <strong>increase brand value</strong> by increase of: <br> - Net Promoter Score (NPS +15%), <br/> - Customer Satisfaction (CSAT +15%) <br> and reduce Customer Effort Score (CES -20%)</p>
                      </b-col>
                    </b-row>
                    <b-row>
                      <b-col sm="11" class="block">
                        <h3>ACTIVITIES</h3>
                        <h4>Research</h4>
                        <ul>
                          <li>Market oportunity (trends, technology, other alternatives)</li>
                          <li>Competition Analysis</li>
                          <li>Persona creation (customer surveys></li>
                          <li>Customer Journey Mapping</li>
                          <li>Stakeholder Analysis (interviews)</li>
                        </ul>
                        <h4>Ideation & Design</h4>
                        <ul style="list-style-type: none;">
                          <li>#1 Sketching</li>
                          <li>#2 Prototyping</li>
                          <li>#3 Brand Identity Design</li>
                          <li>#4 Proof-of-Concept testing</li>
                          <li>#5 Creating value for each stakeholder (Business Model Canvas) </li>
                          <li>#6 UX Design (Userflow, Sitemap, Low-fidelity wireframe, Class Diagram)</li>
                          <li>#7 UI Design (Design System)</li>
                          <li>#8 Interaction Design (High-fidelity wireframe)</li>
                          <li>#9 Project Planning (RoadMap, Backlog)</li>
                        </ul>
                        <h4>Development</h4>
                        <p>Type of digital product:
                        <strong>Web-based SaaS application</strong> </p>
                        <p>Front-end development environment: <strong>Vue.js</strong></p>
                        <p>Back-end development environment: <strong>Node.js</strong></p>
                        <h4>Usability Testing</h4>
                        <ul>
                          <li>Tree testing</li>
                          <li>First click testing</li>
                          <li>5 sec. testing</li>
                        </ul>
                      </b-col>
                    </b-row>
                    <b-row>
                      <b-col sm class="block">
                        <h3>PRODUCT VISION</h3>
                        <p>“Platform designed as a <strong>multi-unit on-demand m-commerce web application</strong> offering a collection of high-quality local products with a great value (price-performance, choice from an local expert). Employing concept of a <strong>»shoppable« apartment, storytelling and latest AR technologies</strong> solution will deliver convenient and almost magical customer experience in the comfort of their temporary stay where <strong>near enough everything can be up for sale.</strong>“</p>
                      </b-col>
                      <b-col sm class="block">
                        <h3>RESULTS</h3>
                        <p>With the use of design thinking, UCD process approach and agile techniques we finished PoC testing. User feedbacks gathered through survarys, review forms will be used for iteration and confirmation of functionalites needed for MVP. <strong>At the moment we are in the phase of MVP development.</strong></p>
                      </b-col>
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

.block h3 {
  margin-bottom: 0.6em;
}
.block ul {
  margin-left: 2em;
}

.block strong {
  color: rgb(125, 207, 182);
  text-shadow: 0.3px 0.3px 0.3px rgba(0, 0, 0, 0.329);;
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
  padding: 1em;
  text-align: justify;
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
  font-size: 1.2rem;
  margin-top: 2em;
  text-shadow: 2px 2px 20px rgba(0,0,0,0.2);
  line-height: 1.3;
}

</style>