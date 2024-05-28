*{
    margin: 0;
    padding: 0;
    font-family: 'Source Sans Pro', sans-serif;
}
.youtube-header{
    font-family: 'Big Shoulders Display', cursive;
    font-weight: 700;
}
.container{
    background: #202020;
    padding: 15px 0px;
    overflow: hidden;
}
.tube-bar-header{
    width: 20%;
    display: flex;
    align-items: center;
}
.tube-bar, .tube-logo{
    display: inline-block;
}
.tube-bar i{
    font-size: 18px;
    color: white;
    margin-left: 30px;

}
.tube-logo{
    color: white;
    font-size: 19px;
    margin-left: 20px;
    display: flex;
    gap: 4px;
}
.tube-logo img{
    color: red;
    width: 30px;
}
.tube-logo sup{
    font-size: 11px;
    color: rgb(119, 118, 118);
    font-family: arial;
}

/* ============   search box =========== */

.tube-search-account{
    overflow: hidden;
}
.tube-bar-header, .tube-search-account{
    float: left;
}
.tube-search-account{
    width: 77%;
}
.search-box {
    width: 680px;
    float: left;
    margin-left: 150px;
}
.search-box input{
    width: 550px;    
    padding: 4px 10px;
    background: #050505bd;
    color: #fff;
    font-size: 16px;
    outline: none;
    border: 1px solid #4d4d4d;
}
.search-box i{
    color: white;
    padding: 0 5px;
}
.search-box i:nth-child(2){
    background: #333;
    padding: 6px 20px;
    color: rgb(167, 160, 160);
    font-size: 14px;
    border: 1px solid #4d4d4d;

}
.search-box i:nth-child(3){
    margin-left: 20px;
    font-size: 20px;
}
.account-box{
    width: 230px;
    float: right;
}
.account-box i{
    color: #fff;
    margin-right: 30px;
    font-size: 20px;
}
.account-box img{
    width: 25px;
    border-radius: 50px;
    border: 1px solid rgb(109, 108, 108);
}
.account-box i, .account-box img{
    display: inline-block;
    overflow: hidden;
}


/* ========Menu Box and Side bar */

.left-side-bar{
    width: 16%;
    height: 87vh;
    overflow: auto;
    background: #212121;
    float: left;
}
/* =======  OVerflow Design */
::-webkit-scrollbar {
    width: 10px;
  }
  
  ::-webkit-scrollbar-track {
    background: #f1f1f100;
  }
  
  ::-webkit-scrollbar-thumb {
    background: rgb(71, 71, 71);
  }
  
  ::-webkit-scrollbar-thumb:hover {
    background: #555;
  }

.menu-section-all ul{
    list-style: none;
    width: 100%;
    margin: auto;
    
}
.menu-section-all li{
    color: rgb(236, 236, 236);
    font-size: 17px;
    font-weight: 600;
    padding: 10px 0px;
    padding-left: 30px;

}
.menu-section-all ul li i{
    padding: 5px 0px;
    color: gray;
    width: 40px;
    height: 15px;
}

.yt-sub-heading{
    margin-top: 10px;
    color: white;
    margin-bottom: 10px;
    margin-left: 30px;
    font-size: 18px;
    color: gray;
}

.menu-section-all ul li:hover{
    background: #3b3b3b;
    color: #fff;
}
b{
    color: white;
    font-size: 13px;
    font-weight: noraml;
    margin-left: 30px;
    font-family: arial;
    margin-top: 10px;
    display: block;
}

.first-section ul{
    border-bottom: 1px solid gray;
}
.second-section ul{
    border-bottom: 1px solid gray;
}
.third-section ul{
    border-bottom: 1px solid gray;
}
.fourth-section ul{
    border-bottom: 1px solid gray;
}
.fifth-section ul{
    border-bottom: 1px solid gray;
}




/* Right SIde top Bar */



.right-side-top-bar{
    width: 83%;
    float: right;
    overflow: hidden;
}
.right-side-top-bar ul{
    padding: 10px;
    overflow: hidden;
    border-top: 1px solid #474747;
    border-bottom: 1px solid #474747;

}
.right-side-top-bar ul li{
    float: left;
    padding: 7px 15px;
    background: #383838;
    color: white;
    margin-left: 5px;
    border-radius: 20px;
    list-style: none;
    border: 1px solid rgb(78, 78, 78);
    font-size: 15px;
    font-family: arial;
}
.right-side-top-bar ul li:hover{
    background: rgb(112, 112, 112);
}
.yt-videos-wrapper{
    padding: 20px;
    overflow: hidden;
}

.yt-videos-wrapper{
    background: #181818;
    overflow: hidden;
}
.yt-videos{
    width: 394PX;
    padding: 10px;
    float: left;
}
.yt-videos video{
    border-radius: 3px;
}
.yt-video-deatails i{
    width: 30px;
    height: 70px;
    list-style: none;
    color: white;
    font-size: 26px;
    float: left;
    padding: 10px 5px;
}
.yt-video-deatails {
    width: 370px;

}
.yt-video-deatails h3{
    color: white;
}
.yt-video-deatails span{
    color: gray;
    font-size: 16px;
    display: block;
}

footer{
    background-color: #333;
}
footer p{
    color: #fff;
    font-size: 14px;
    text-align: center;
    padding: 8px 0;
}
