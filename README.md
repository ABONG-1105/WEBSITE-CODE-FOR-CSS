# WEBSITE-CODE-FOR-CSS
CSS CODE


*{
    margin:0;
    padding: 0;
    background-color:white;
    font-family:'Poppins',sans-serif;
}
.header{
    min-height:100vh;
    width:100%;
    background-image: linear-gradient(rgba(4,9,30,0.7),rgba(4,9,30,0.7)),url(PICTURES/flower.png.jpg);
    background-position:center;
    background-size:cover;
    position:relative;
    color: green;
}
nav{
    display:flex;
    padding:0% 0%;
    justify-content: space-between;
    align-items:right;
}
nav img{
    width:40%;
    height: 50%;
    color:green;
    text-decoration: solid;
    font-size: 14px;
}
nav {
    font-size:14px;
    align-items:left;

}
.nav-links ul li{
    list-style: none;
    display: inline-block;
    padding: 8px 12px;
    position:relative;
}
.nav-links ul li{
color:black;
text-decoration: none;
font-size: 20px;
align-items:center;
}
.nav-links ul li::after{
    content:"";
    width:0%;
    height:2px ;
    background:green;
    display: block;
    margin: auto;
    transform: 0.5s;
}
.nav-links ul li:hover::after{
    width:100%;
}
.text-box{
    width: 90%;
    color:black;
    position: absolute;
    top: 50%;
    left:50%;
    transform:translate(-50%,-50%) ;
    text-align: center;
}
.text-box hi{
    font-size: 20px;
}
.text-box p{
margin: 10px 0 40px;
font-size: 24px;
color:black;
}
.hero-btn{
    display: inline-block;
    text-decoration: none;
    color: black;
    border: 1px solid #fff;
    padding: 12px 34px;
    font-size: 13px;
    background: transparent;
    position: relative;
    cursor:pointer;
}
.hero-btn:hover{
    border:1px solid;
    background:aquamarine;
    transition: 1s;
}
nav.fa{
    display:block;
}
@media(max-width:700px){
    .text-box hi{
        font-size: 20px;
    }
    .nav-links ul li{
        display:block;
    }
    .nav-links {
position: fixed;
background: aqua;
height:100vh;
width:200px;
top:0;
right:-200px;
text-align:left;
z-index: 2;
transition:1s;
    }
    nav.fa{
        display:block;
        color:#fff;
        margin: 10px;
        font-size: 22px;
        cursor: pointer;
    }
    .nav-links ul{
        padding:30px;
    }
}
/*------Crops------*/
.Crops{
    width:80%;
    margin:auto;
    text-align: center;
    padding-top:100px;
}
h1{
    font-size:36px;
    font-weight:600;
}
p{
    color:black;
    font-size: 14px;
    font-weight:300;
    line-height: 22px;
    padding:10px;
}
row{
    margin-top:5%;
    display:flex;
    justify-content:center;
    align-content: center;
    justify-content:right;
    
}

.Crops-col{
    flex-basis: 31%;
    background: aqua;
    border-radius:5px;
    margin-bottom: 5%;
    padding: 20px 12px;
    box-sizing: border-box;
    transition: 0.5s;
}
h2{
    text-align: center;
    font-weight: 600;
    margin:10px 0px;
}
.Crops-col:hover{
    box-shadow: 0 0 20px 0px rgba(rgb(255, 0, 0));
}
@media(max-width:700px){
    .row{
        flex-direction:column;
    }
}
/*-------FARM----*/
.farm{
    width:80%;
    margin:auto;
    text-align:center;
    padding-top:50px;
    text-decoration: black;
    
}
.farm-col{
    flex-basis: 32%;
    border: radius 10px;
    margin-bottom:30px;
    position:relative;
    overflow:hidden;
}
.farm img {
    width:30%;
}
.layer{
    background:transparent;
    height:100%;
    width:100%;
    position: absolute;
    top:0;
    left:0;
    transition:0.5s ;
    
}
.layer:hover{
    background:antiquewhite;
}
.layer h2{
    width:100%;
    font-weight: 500;
    color:whitesmoke;
    font-size: 26px;
    bottom: 0;
    left:50%;
    transform: translateX(-50%);
    position: absolute;
    opacity: 1;
    transition:1s;
}
.layer:hover{
    bottom:100%;
    opacity: 1;
}
/*-------Crops-------*/
.Crops{
    width: 49%;
    margin:auto;
    text-align: center;
    padding-top: 100px;

}
.Crops{
    flex-basis: 31%;
    border-radius:10px ;
    margin-bottom: 5%;
    text-align: left;
}
.Crops-col{
    width:100%;
    border-radius: 10px;
}
.Crops-col p{
    padding:0;
}
.Crops-col h3{
    margin-top:16px;
    margin-bottom: 15px;
    text-align: left;
}
.LOCATION{
width: 50%;
margin: auto;
padding-top: 100PX;
text-align: center;
}
.LOCATION-COL{
    flex-basis:44%;
    border-radius:10px;
    text-align:left;
    background: black;
    padding: 12px;
    cursor:pointer;
    display:flex;
}
    .LOCATION-COL img{
        height:40px;
        margin: left 5px; ;
        margin-right: 30px;
        border-radius:50%;
}
.LOCATION-COL p{
    padding: 0;
}
.LOCATION h3{
    margin-top:15px ;
    text-align: left;
}
.LOCATION-COL .fa{
    color:black;

}
@media  (max-width: 700px){
.LOCATION-COL img{
    margin-left: 0px;
    margin-right: 15px;
}
}
/*--------call to action-------*/
.cta{
    margin:50px auto;
    width:50%;
    background-image: linear-gradient(rgba(4,9,30,0.7),rgba(4,9,30,0.7)),url(PICTURES/background.png);
    background-position: center;
    background-size: cover;
    border-radius:5px;
    text-align:center;
    padding: 100px ;
}
.cta h1{
    color:black;
    margin: bottom 10px;
    padding:1px;
}
@media(max-width:700px){
    .cta h1{
        font-size:24px;
    }
}
/*----------footer---------*/
.footer{
    width:100%;
    text-align:center;
    padding:30px ;

}
.footer h4{
    margin-bottom:25px ;
    margin-top:20px;
    font-weight: 600;
    color:black;
}
.footer P{
    font-size:15px;
    color:purple;
    padding: 20PX;
    behavior: var(----------footer---------);
}
.icons.fa{
    color:black;
    margin:13px;
    cursor:pointer;
    padding:18px;
}
.fa-herat-o{
    color:black;
}
    /*--------------about us page----------*/
    .sub-header{
        height: 50vh;
        width:100%;
        background-image: linear-gradient(rgba(4,9,30,0.7),rgba(4,9,30,0.7)),url(PICTURES/background.png.png);
    background-position: center;
    background-size: cover;
    text-align: center;
    color: black;
    }
    .sub-header h1{
        margin-top: 50px;
    }
    .about-us{
        width:80%;
        margin:auto;
        padding: 50px;
        padding-bottom: 50px;
    }
    .about-col{
        flex-basis: 48%;
        padding:30px 2px;
    }
    .about-col img{
        width: 70%;
    }
    .about-col h1{
        padding: 0;
    
    }
    .about-col p{
        padding:15px 0 25px;

    }
    .red-btn{
        border: 1px solid aqua;
        background: transparent;
        color:aqua;
    }
    .red-btn:hover{
        color:aqua;
    }
/*--------blog content---------*/
.blog-content{
width:80%;
margin:auto;
padding:60px 0;
}
.blog-left{
    flex-basis:65%
}
.blog-left img{
    width:100%;
}
.blog-left h2{
    color:red;
    font-weight:300;
    margin: 30px 0;
}
.blog-left p{
    color:red;
    padding:0;
}
.blog-right h3{
    background: aqua;
    color:blue;
    padding:7px 0;
    font-size: 16px;
    margin-bottom: 20px;
}
.blog-right div{
    display: flex;
    align-items: center;
    justify-content: space-between;
    color: aqua;
    box-sizing: border-box;
}
.comment-box{
    border:1px solid #ccc;
    margin:50px 0;
    padding:10px 20px;
}
.comment-box h2{
text-align: left;
}
.comment-form input,.comment-form textarea{
    width:100%;
    padding:10px;
    margin:15px 0;
    box-sizing: border-box;
    border:none;
    outline:none;
    background: #f0f0f0;
}
comment-button{
    margin:10px 0;
}
@media(max-width:700px){
    .sub-header h1{
        font-size:24px;
    }
}
/*-----------------cntact us page-------------*/
.LOCATION{
    width:80%;
    margin:auto;
    padding:80px 0;
}
.LOCATION iframe{
    width:100%;
}
.contact-us{
    width:80%;
    margin:auto;
}
.contact-col{
    flex-basis:48%;
    margin-bottom:30px;
}
.contact-col div{
    display: flex;
    align-items:center;
    margin-bottom: 40px;
}
.contact-col .fa{
font-size:28;
color:aqua;
margin:10px;
margin-right: 30px;
}
.contact-col div p{
    padding:0;
}
.contact-col div h3{
    font-size: 20px;
    margin-bottom: 5px;
    color:aqua;
    font-weight: 400;
}
.contact-col input,.contact-col textarea{
    width: 100%;
    padding: 15px;
    margin-bottom: 17px;
    outline: none;
    border:1px solid aqua;
    box-sizing: border-box;
}















