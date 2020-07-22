<template>
    <div class="square" data-aos="zoom-in">
        <span></span>
        <span></span>
        <span></span>
        <div class="content" data-aos="fade">
            <h2 style="margin-bottom:0; font-size: 2.5em;">Leading sustainable solutions</h2>
            <!-- <a href="/case-studies/expar-store" to="/case-studies/expar-store">OUR PROJECTS...</a> -->
        </div>
    </div>
</template>


<style scoped>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    display: flex;
    justify-content: center;
    align-items: center;
}
.square {
    position: relative;
    width: 400px;
    height: 400px;
    display: flex;
    justify-content: center;
    align-items: center;
}
@media (max-width: 680px) {
    .square {
        width: 250px;
        height: 250px;
    }
    .content {
        font-size: 0.8em;
        padding: 20px 30px;
    }
    .content a {
        margin-top: 5px;
        border: 1px solid white;
        padding: 4px 12px;
        color: white;
        font-weight: 4;
    }
}
.square span:nth-child(1) {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 2px solid white;
    border-radius: 38% 62% 63% 37% / 41% 44% 56% 59%;
    transition: 0.5s;
    animation: animate 6s linear infinite;
}
.square:hover span:nth-child(1) {
    background: rgba(125, 207, 182, 0.4);
    border: none;
}
.square span:nth-child(2) {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 2px solid white;
    border-radius: 38% 62% 63% 37% / 41% 44% 56% 59%;
    transition: 0.5s;
    animation: animate 4s linear infinite;
}
.square:hover span:nth-child(2) {
    background: rgba(125, 207, 182, 0.4);
    border: none;
}
.square span:nth-child(3) {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 2px solid white;
    border-radius: 38% 62% 63% 37% / 41% 44% 56% 59%;
    transition: 0.5s;
    animation: animate2 10s linear infinite;
}
.square:hover span:nth-child(3) {
    background: rgba(125, 207, 182, 0.4);
    border: none;
}
@keyframes animate {
    0% {
        transform: rotate(0deg);
    }
    100% {
        transform: rotate(360deg);
    }
}
@keyframes animate2 {
    0% {
        transform: rotate(360deg);
    }
    100% {
        transform: rotate(0deg);
    }
}
.content {
    position: relative;
    padding: 40px 60px;
    color: white;
    text-align: center;
    transition: 0.5s;
    z-index: 1000;
}
.content a {
    position: relative;
    display: inline-block;
    margin-top: 10px;
    border: 2px solid white;
    padding: 6px 18px;
    text-decoration: none;
    color: white;
    font-weight: 600;
    border-radius: 3%;
}
.content a:hover {
    background: white;
    color: #333;
}


</style>