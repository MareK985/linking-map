<template>
    <div class="footer">
        <div id="button"></div>
         <div id="container">
                <div id="cont">
                <div class="footer_center">
                    <h3 style="color: white; font-size: 1.8em; font-weight: 100; margin-top: 50px;">Hire us</h3>
                    <div class="footer-text"> We are currently taking on new projects. Would you like to discuss yours?</div>
                    <p style="color: white; font-size: 0.8rem; font-weight: 300; margin-left: 30px"> +386 40 899 409</p>
                    <a href="https://www.linkedin.com/" target="_blank"><font-awesome-icon style="margin-left: 30px; margin-right: 10px;" :icon="['fab', 'linkedin-in']"/></a>
                    <a href="mailto:hello@linking-map.com" target="_blank"><font-awesome-icon :icon="['fas', 'envelope']"/></a>

                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

body{
  font-weight:300;
  background-color:lightblue;
  color:#FFF;
}
section{
  text-align:center;
}
.footer #button{
    width:35px;
    height:35px;
    border: rgb(125, 207, 182) 12px solid;
    border-radius:35px;
    margin:0 auto;
    position:relative;
    -webkit-transition: all 1s ease;
    -moz-transition: all 1s ease;
    -o-transition: all 1s ease;
    -ms-transition: all 1s ease;
    transition: all 1s ease;
}
.footer #button:hover{
    width:35px;
    height:35px;
    border: #3A3A3A 12px solid;
    -webkit-transition: all 1s ease;
    -moz-transition: all 1s ease;
    -o-transition: all 1s ease;
    -ms-transition: all 1s ease;
    transition: all 1s ease;
    position:relative;
}
.footer {
    bottom:0;
    left:0;
    position:fixed;
    width: 100%;
    height: 2.4em;
    overflow:hidden;
    margin:0 auto;
    -webkit-transition: all 1s ease;
    -moz-transition: all 1s ease;
    -o-transition: all 1s ease;
    -ms-transition: all 1s ease;
    transition: all 1s ease;
    z-index:999;
}
.footer:hover {
    -webkit-transition: all 1s ease;
    -moz-transition: all 1s ease;
    -o-transition: all 1s ease;
    -ms-transition: all 1s ease;
    transition: all 1s ease;
    height: 10em;
}
.footer #container{
    margin-top:5px;
    width:100%;
    height:100%;
    position:relative;
    top:0;
    left:0;
    background: rgb(125, 207, 182);
}
.footer #cont{
    position:relative;
    top:-45px;
    right:190px;
    width:150px;
    height:auto;
    margin:0 auto;
}
.footer_center{
    width:500px;
    float:left;
    text-align:center;
}
.footer h3{
    font-family: 'Helvetica';
    font-size: 30px;
    font-weight: 100;
    margin-top:70px;
    margin-left:40px;
}

.footer-text {
    color: white; 
    font-size: 0.85rem; 
    font-weight: 300; 
    margin-left: 10px;
}

@media screen and (min-width: 601px) {
.footer-text {
    font-size: 0.9em;
    margin-left: 30px;
  }
}

@media screen and (max-width: 600px) {
.footer-text {
    font-size: 0.55em;
    margin-left: 30px;
  }
}

</style>