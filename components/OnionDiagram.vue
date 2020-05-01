<template>
    <div class="diagram">
        <div class="square1 boarder-line" data-aos="zoom-in">
            <div class="content">
                <h2 class="title-square" style="top: -23vh;">Bx</h2>

                <div class="square2a boarder-line">
                    <div class="content">
                    <h2 class="title-square" style="left: 2vh;">Cx</h2>
                    </div>
                <div class="square2b boarder-line">
                    <div class="content">
                    <h2 class="title-square" style="left: 6vh;">Ex</h2>
                    </div>

                    <div class="square3 boarder-line">
                        <div class="content">
                        <h2 class="title-square" style="top: -10vh;">Ux</h2>
                        </div>

                        <div class="square4 boarder-line">
                            <div class="content">
                            <h2 class="title-square">UI</h2>
                            </div>
                        </div>

                    </div>

                </div>
            </div>
        </div>

        </div>  
  
    </div>

</template>


<style>
.diagram {
      top:0;
      left:0;
      width:100%;
      height:100%;
      margin:0 auto;
      position:relative;
      overflow-x: auto;
      overflow-y: hidden;
    }
.boarder-line {
    border: 6px solid rgb(125, 207, 182);
    border-radius: 38% 62% 63% 37% / 41% 44% 56% 59%;

}
.square1 {
    width: 60%;
    height: 60vh;
    margin: auto;
    padding: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
    clear:both;
    z-index: 99;
    position: absolute; 
    left:0;
    right: 0;
    top: 0;
    bottom: 30px;   
}
.square2a {
    width: 45%;
    height: 45vh;
    margin-left: 10vh;
    margin-top: 10vh;
    padding: 10px;
    display: flex;
    z-index: 100;
    position:absolute; 
    left: 0;
    right: 0;
    top: 0;
    bottom: 0; 
}
.square2b {
    width: 70%;
    height: 43vh;
    margin-left: 40vh;
    margin-top: -3vh;
    padding: 10px;
    display: flex;
    z-index: 100;
    position:absolute; 
    left: 0vw;
    top: 0;
    right: -50vh;
    bottom: 0vh; 
}
.square3 {
    width: 150%;
    height: 30vh;
    margin: auto;
    padding: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
    clear:both;
    z-index: 101;
    position:absolute;                  
    left: -30vh;
    right: 0;
    top: 0;
    bottom:-10vh; 

}
.square4 {
    width: 60%;
    height: 20vh;
    margin: auto;
    padding: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
    clear:both;
    z-index: 101;
    position:absolute;                  
    bottom:10px; 

}

.square1:hover {
    background: rgba(125, 207, 182, 0.2);
    border: none;
    transform: scale(1.05);
    color: white;
}
.square2a:hover {
    background: rgba(125, 207, 182, 0.4);
    border: none;
    transform: scale(1.05);
    color: white;

}
.square2b:hover {
    background: rgba(125, 207, 182, 0.4);
    border: none;
    transform: scale(1.05);
    color: white;

}

.square3:hover {
    background: rgba(125, 207, 182, 0.6);
    border: none;
    transform: scale(1.05);
    color: white;

}
.square4:hover {
    background: rgba(125, 207, 182, 0.8);
    transform: scale(1.05);
    border: none;
    color: white;
}

.title-square {
    font-size: 4.5em;
    color: rgba(125, 207, 182, 0.6);
    font-weight: 900;
    position: relative;

}

@media (max-width: 680px) {
    .content {
        font-size: 0.9rem;
        padding: 20px 30px;
    }
    .square1 {
    width: 80%;
    height: 60vh;
    }
    .square2b {
        width: 60%;
        height: 40vh;
        right: -50vh;
        left: -20vh;
        bottom: 0vh; 
        margin: auto;

    }
    .square2a{
        width: 50%;
        height: 45vh;
        left: -5vh;
        bottom: -3vh; 
    }
    .square3{
    width: 150%;
    height: 30vh;
    margin: auto;
    left: -20vh;
    right: 0;
    top: -5vh;
    bottom:-10vh; 
    }
}

    
</style>