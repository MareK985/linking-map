<template>
    <div id="form-main" data-aos="fade-up" data-aos-anchor-placement="bottom-center">
        <div id="form-div">
            <form class="form" id="form1">
                <p class="name">
                    <input name="name" type="text" class="validate[required,custom[onlyLetter],length[0,100]] feedback-input" placeholder="Name" id="name" />
                </p>
                
                <p class="email">
                    <input name="email" type="text" class="validate[required,custom[email]] feedback-input" id="email" placeholder="Email" />
                </p>
                
                <p class="text">
                    <textarea name="text" class="validate[required,length[6,300]] feedback-input" id="comment" placeholder="Message"></textarea>
                </p>
                <div class="submit">
                    <input type="submit" value="SEND" id="button-blue"/>
                    <div class="ease"></div>
                </div>
            </form>
        </div>
    </div>
</template>

<style scoped>
#feedback-page{
	text-align:center;
}

#form-main{
	width:100%;
	float:left;
	padding-top:0px;
}

#form-div {
	background: #fff;
	padding-left:35px;
	padding-right:35px;
	padding-top:35px;
	padding-bottom:35px;
	width: 450px;
	float: left;
	left: 50%;
	position: absolute;
  margin-top:30px;
	margin-left: -260px;
}

.feedback-input {
	color:#000;
	font-family: Montserrat, Arial, sans-serif;
  font-weight:300;
	font-size: 14px;
	border-radius: 0;
	line-height: 22px;
	background-color: #fff;
	padding: 13px 13px 13px 13px;
	margin-bottom: 10px;
	width:100%;
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	-ms-box-sizing: border-box;
	box-sizing: border-box;
  border: 0px solid transparent;
  border-bottom: 1px solid #000;
}

.feedback-input:focus{
	background: #fff;
	box-shadow: 0;
	color: #000;
	outline: none;
  padding: 13px 13px 13px 13px;
}

.focused{
	color:#000;
	border:#30aed6 solid 2px;
}

textarea {
    width: 100%;
    height: 150px;
    line-height: 150%;
    resize:vertical;
}

input:hover, textarea:hover,
input:focus, textarea:focus {
	background-color:white;
}

#button-blue{
	float:left;
	width: 100%;
	border: 0px solid transparent;
	cursor:pointer;
	background-color: #000;
	color:white;
	font-size:18px;
	padding-top:22px;
	padding-bottom:22px;
	-webkit-transition: all 0.3s;
	-moz-transition: all 0.3s;
	transition: all 0.3s;
  margin-top:-4px;
  font-weight:300;
}

#button-blue:hover{
	background-color: #fff;
	color: #000;
  border: 1px solid #000;
}
	
.submit:hover {
	color: #3498db;
}
	
.ease {
	width: 0px;
	height: 74px;
	background-color: #fbfbfb;
	-webkit-transition: .3s ease;
	-moz-transition: .3s ease;
	-o-transition: .3s ease;
	-ms-transition: .3s ease;
	transition: .3s ease;
}

.submit:hover .ease{
  width:100%;
  background-color:white;
}

@media only screen and (max-width: 580px) {
	#form-div{
		left: 3%;
		margin-right: 3%;
		width: 88%;
		margin-left: 0;
		padding-left: 3%;
		padding-right: 3%;
	}
	#form-main{
	margin-top: 60vh;
}
}
</style>