<template>
    <div class="wrapper">
        <div  class="container">
            <header>
                <a href="#" class="logo">NatureComp</a>
                <nav>
            <img src="~/assets/img/logo-1.svg" alt="menu">
                </nav>
            </header>
            <h1> Preserve Nature</h1>

            <div class="line"></div>
        </div>

        <div class="container secondary">
            <h2>Strategic</h2>
            <p class="subtext">Alliances</p>

            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque doloribus error repellendus! Dolorem ad necessitatibus illum cumque ipsam odio velit. Soluta facere exercitationem ducimus enim delectus sunt deserunt sapiente ut!</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque doloribus error repellendus! Dolorem ad necessitatibus illum cumque ipsam odio velit. Soluta facere exercitationem ducimus enim delectus sunt deserunt sapiente ut!</p>
        </div>

        <img class="mountains" src="~assets/img/team.jpg" alt="hero-expar" />          
        <img class="trees" src="~assets/img/path.jpg" alt="hero-expar" />          



    
    </div>


</template>

<script>
import lax from 'lax.js'

window.onload = function() {
	lax.setup() // init

	const updateLax = () => {
		lax.update(window.scrollY)
		window.requestAnimationFrame(updateLax)
	}

	window.requestAnimationFrame(updateLax)
}

</script>


<style lang="scss" scoped>
.wrapper {
    margin: 0;
    height: 100vh;
    background: rgb(46, 44, 44);

}

*, *:before, *:before {
    box-sizing: border-box;
}
.container {
    padding: 2em;
    height:100vh;

    &:first-child {
        display: grid;
        grid-template-rows: 10% 30% auto;
    }

    h1 {
        text-align: center;
        margin-top: 2em;
        font-weight: normal;
        font-size: 3em;
        line-height: 0.9em;
    }
    p {
        line-height: 1.5em;
        color: rgb(194,194,194);
    }
    .line {
        align-self: end;
        width: 50%;
        border-right: 1px solid white;
        height: 50%;
        margin-bottom: 4em;
        position: relative;

        &::after {
            content:"";
            position: absolute;
            width: 0;
            height: 0;
            border-style: solid;
            border-width: 11px 11px 0px 11px;
            border-color: white transparent transparent transparent;
            right: -.7em;
            bottom: -.2em;
        }
    }

}
header {
    display: flex;
    justify-content: space-between;
}
.logo {
 color: black;
 text-decoration: none;
 font-weight: bold;
 font-size: 1.1em;
}

.mountains {
    position: absolute;
    z-index: 0;
    width: 100%;
}
.trees {
    position: absolute;
    z-index: 0;
    width: 100%;
}
.subtext {
    margin-top: 0;
    font-size: 1.4em;
    text-transform: uppercasse;
}
.mountains {
    top:0;
}
.trees {
    top:30%;
}

@media only screen and (min-width: 665px) {
    .mountains {
        top: -25%;
    }
    .trees {
        top: -5%;
    }
}
@media only screen and (min-width: 930px) {
    .mountains {
        top: -60%;
    }
    .trees {
        top: -30%;
    }
}
@media only screen and (min-width: 1050px) {
    .mountains {
        top: -60%;
    }
    .trees {
        top: -40%;
    }
}
</style>