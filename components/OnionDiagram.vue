<template>
    <div class="diagram">
        <div class="square1">
            <div class="content">
                <h2 class="title-square" style="top: -23vh;">Bx</h2>
                <p>dsokdsmd</p>  

                <div class="square2a">
                    <div class="content">
                    <h2 class="title-square" style="left: 2vh;">Cx</h2>
                    <p>dksjskjdsoi</p>
                    </div>
                <div class="square2b">
                    <div class="content">
                    <h2 class="title-square" style="left: 6vh;">Ex</h2>
                    <p>dksjskjdsoi</p>
                    </div>

                    <div class="square3">
                        <div class="content">
                        <h2 class="title-square" style="top: -10vh;">Ux</h2>
                        <p>dsokdsmd</p>
                        </div>

                        <div class="square4">
                            <div class="content">
                            <h2 class="title-square">UI</h2>
                            <p>dsokdsmd</p>
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
.square1 {
    width: 80%;
    height: 60vh;
    margin: auto;
    padding: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1px solid rgb(125, 207, 182);
    clear:both;
    border-radius: 38% 62% 63% 37% / 41% 44% 56% 59%;
    z-index: 99;
    position: absolute; 
    left:0;
    right: 0;
    top: 0;
    bottom: 10px;   
}
.square2a {
    width: 50%;
    height: 45vh;
    margin: auto;
    padding: 10px;
    display: flex;
    border: 1px solid rgb(125, 207, 182);
    clear:both;
    border-radius: 38% 62% 63% 37% / 41% 44% 56% 59%;
    z-index: 100;
    position:absolute; 
    left: -10vh;
    right: 0;
    top: 0;
    bottom:-10vh; 
}
.square2b {
    width: 60%;
    height: 40vh;
    margin: auto;
    padding: 10px;
    display: flex;
    border: 1px solid rgb(125, 207, 182);
    border-radius: 38% 62% 63% 37% / 41% 44% 56% 59%;
    z-index: 100;
    position:absolute; 
    left: 10vw;
    right: -40vh;
    top: 0;
    float: right;
    bottom: 5vh; 
}
.square3 {
    width: 150%;
    height: 30vh;
    margin: auto;
    padding: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1px solid rgb(125, 207, 182);
    clear:both;
    border-radius: 38% 62% 63% 37% / 41% 44% 56% 59%;
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
    border: 1px solid rgb(125, 207, 182);
    clear:both;
    border-radius: 38% 62% 63% 37% / 41% 44% 56% 59%;
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
        font-size: 0.8em;
        padding: 20px 30px;
    }
}
</style>