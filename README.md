<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MY PORTFOLIO</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@500;600&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/57ba17d00b.js" crossorigin="anonymous"></script>
    <style>
        *{
    margin: 0;
    padding:0;
    font-family: 'Poppins', sans-serif;
    box-sizing: border-box;
}
html{
    scroll-behavior: smooth;
}

body{
    background-color:rgb(28, 25, 25);
    color:white;
}

#header{
    margin: 0;
    padding: 0;
    font-family: 'Arial', sans-serif;
    background-image: url(bcgr1.avif); 
    background-size: cover;
    color: #fff;
}
.container{
    padding: 20px 10%;
}
.image{
    margin-top:20px;
    text-align: right;
}

nav{
    display : flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;

}
nav{
    display: inline-block;
    list-style: none;
    margin-left: 595px;
}
nav a{
    color:#fff;
    text-decoration: none;
    font-size: 16px;
    position: relative;
    margin-left: 20px;
    margin-top:20px;
}

nav a:hover::after{
    width: 100%;

}
nav a::after{
    content:'';
    width: 0;
    height:3px;
    background: purple;
    position: absolute;
    left:0;
    bottom: -6px;
}

.header-text{
    margin-top: 20%;
    font-size: 30px;
    text-align:right;
}
.header-text h1{
    font-size: 50px;
    margin-top: 20px;
}
.header-text p{
    font-size: 20px;
    margin-top: 10px;
    font-weight: 400;
    letter-spacing: 10px;
    
}
.header-text h1 span{
    color:purple;
}
#about{
    padding : 80px 0;
    color:#fff;
    text-align: center;

}
.about-col-1 p{
    margin-top: 30px;
    font-weight: 400;
    line-height: 30px;
    
}
.about-col-2 h1{
    margin-top: 70px;
    letter-spacing: 10px;
    color:purple;
}
#skills{
    padding: 30px 0;
}
.skills-list{
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    grid-gap: 40px;
    margin-top:80px;
}
.skills-list2{
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    grid-gap: 60px;
    margin-top:80px;

}
.skills-list2 p{
    font-size: small;
    margin-top: 20px;
}
.skills-list p{
    font-size :small;
   margin-top:20px ;
}
.skills-list h2{
    color:#ffffff;
}
.skills-list2 h2{
    color:#ffffff;
}
.sub-title{
    text-align: center;
}
.skills-list2 a{
    color:#ffffff;
    margin-top: 40px;
    font-size:small ;
    text-decoration: underline;
}
.skills-list a{
    color:#ffffff;
    font-size: small;
    text-decoration: underline;

}
.skills-list div{
    background: purple;
    padding: 40px;
    border-radius: 30px;
    transition: background 0.5s, transform 0.5s;
}
.skills-list2 div{
    background:purple;
    padding: 40px;
    border-radius: 30px;
    transition: background 0.5s, transform 0.5s;
}
.skills-list div i{
    font-size: 30px;
    margin-bottom: 30px;
}
.skills-list2 div i{
    font-size: 30px;
    margin-bottom: 30px;
}
.skills-list div:hover{
    background:#ff004f;
    transform: translateY(-10px);
}
.skills-list2 div:hover{
    background: #ff004f;
    transform: translateY(-10px);
}
#interests{
    padding: 50px 0;
}
.work1 img {
    width: 350px;
    margin-top: 40px;
    margin-left: 27px;
    align-items: center;
}
.work1 h1{
    margin-top: 40px;
    color:#ffffff;
    font-size: 30px;
}
.work1 p{
    margin-top: 40px;
}
.work2 img{
    margin-top: 50px;
}
.work2 p{
    margin-top: 40px;
}
.work2 h1{
    margin-top: 90px;
}
.work3 h1{
    margin-top: 90px ;
}
.work4 img{
    width: 150px;
    align-items: center;
    margin-top: 40px;
}
.work4 h1{
    margin-top: 90px;
}
.work5 img{
    width: 150px;
    margin-top: 40px;
}
.work5 h1{
    margin-top: 90px;
}
.work6 h1{
    margin-top: 90px;
}
.work6 img{
    width :250px;
    margin-top: 40px;
}
.work7 img{
    width: 250px;
    margin-top: 40px;
}
.work7 h1{
    margin-top: 90px;
}
.work8 img{
    width : 350px;
    margin-top: 40px;

    
}
.work8 h1{
    margin-top: 90px;
}
.work9 h1{
    margin-top: 90px;
    margin-left: 140px;
}
.work9 img{
    width:350px;
    margin-left: 140px;
    margin-top: 40px;
}
.work9 p{
    margin-left: 140px;
    margin-right: 140px;
}
#skills{
    padding: 30px 0;
}
.skills-list{
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    grid-gap: 40px;
    margin-top:80px;
}
.skills-list{
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    grid-gap: 40px;
    margin-top:80px;
}
.skills-list{
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    grid-gap: 40px;
    margin-top:80px;
}
.contact-left{
    flex-basis:35%; 
}
.contact-right{
    flex-basis:60%;
}
.contact-left p{
    margin-top: 30px;
}
.contact-left p i{
    color:purple;
    margin-right: 15px;
    font-size: 25px;
}
.social-icons{
    margin-top: 30px;
}
.social-icons a{
    text-decoration: none;
    font-size: 30px;
    margin-right: 15px;
    color: #ababab;
    display:inline-block;
    transition: transform 0.5s;
}
.social-icons a:hover{
    color:purple;
    transform: translateY(-8px);
}
.btn{
    background:purple;
    color: #fff;
    border-radius: 30px;
    text-decoration: none;
    margin: 50px;
    display:inline-block;
    width: fit-content;
    padding: 14px 50px;
    margin-left: 5px;
}
.contact-right form{
    width:100%;
}
form input, form textarea{
    width: 100%;
    border:0;
    outline:none;
    background: #262626;
    padding: 15px;
    margin: 15px 0;
    color:#fff;
    font-size:18px;
    border-radius:6px;
}
.contact-left p{
    margin-top: 60px;
}
form btn{
    padding: 14px 60px;
    font-size: 18px;
    margin-top: 20px;
    cursor:pointer;
}
.copyright {
    width: 100%;
    text-align: center;
    padding: 25px 0;
    background: #262626;
    margin-top: 20px;
}
.copyright p{
    font-weight: 100px;
    font-size: 15px;
}
#header li{
    cursor: pointer;

}
    </style>
    
</head>
<body>
    <div id="header">
        <div class="container">
            <nav>               
                    <a href="#header">Home</a>
                    <a href="#about">About</a>
                    <a href="#skills">Skills</a>
                    <a href="#interest">Interests</a>
                    <a href="#contact">Contact</a>
                    <a href="#video">demo</a>
            </nav>
            <div class="header-text">
                <h1>Welcome to my page!</h1>
                <h1>This is <span>KIREETI BUSSA</span></h1>
                <p>web Developer</p>
                
                <div class="image">
                    <img  src="PHOTO.jpg" width="200px" height="275px">
                </div>
            </div>
            
        </div>
    </div>

    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <h1>ABOUT ME</h1>
                    <p>
                        passionate about the website development, and beyond which can lead me to the notable accomplishments.I thrive on tackling challenges and bringing creative solutions to the table.outside of it, I loving watching solo games and medal tournaments. And, I have a curiosity of knowing about thing. </p>    
                </div>
                
            </div>
        </div>
    </div>

<div id="skills">
    <div class="container">
        <h1 class="sub-title">MY SKILLS</h1>
        <div class="skills-list2">
            <div>
                <i class="fa-solid fa-code"></i>
                <h2>Web Design</h2>
                <p>I have a creative flair for website Designing, skillfully blending aesthetics and functionality to create captivating online experiences.</p>
            </div>
            <div>
                <i class="fa-solid fa-crop-simple"></i>
                <h2>UI / UX Designs</h2>
                <p>I excel in UI/UX designing, crafting seamless and visually appealing interfaces that prioritize user satisfaction and engagement.</p>
            </div>
        </div>
        <div class="skills-list">
            <div>
                <i class="fa-brands fa-stumbleupon"></i>
                <h2>3D Modeling</h2>
                <p>I am considerate in 3D modeling, building models of virtual to look realistic with creativity and realistic</p>
            </div>
            <div>
                <i class="fa-solid fa-vector-square"></i>
                <h2>Programming</h2>
                <p>I am good at c, c++  and  I also know bits of PYTHON and JAVA and also SQL</p>
            </div>
        </div>
    </div>
</div>
<!----------------portfolio----------------->
<div id="interests">
    <div id="web">
        <div class="container">
            <h1 class="sub-title">MY INTERESTS</h1>
            <div class="work1">
                <h1></h1>
              <img src="download.jpg" class="work1">
              <img src="images.jpg"class="work1">
                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                    I am pursuing a course in 3D modeling and there we use blender software to work on things, and has many opportunities to build a future out of it. Recently, I build up interest on Website designing and it helps me to understand the core notations of a website.
                </p>   
            </div>
        </div>
    </div>
</div>
<!--------------------My accounts--------------------->
<div id="Accounts">
    <div class="container">
        <h1 class="sub-title">MY Accounts</h1>
        <div class="skills-list2">
            <div>
                <a herf=""><i class="fa-brands fa-x-mail"></i></a>
                <h2>E-MAIL</h2>
                <p>my email acc, <a href="mailto:https://mail.google.com/mail/u/0/?tab=rm&ogbl#inbox">email</a>.</p>
            </div>
            <div>
                <a herf=""><i class="fa-brands fa-github"></i></a>
                <h2>GITHUB</h2>
                <p>my github acc, <a href="https://github.com/Kireeti2808/Kireeti2808">github</a>.</p>
            </div>
            <div>
                <a herf=""><i class="fa-brands fa-linkedin"></i></a>
                <h2>Linkedln</h2>
                <p>my Linkedln page, <a href="https://www.linkedin.com/in/kireeti-bussa-2339b6267/">Linkedln</a>.</p>
            </div>
        </div>
    </div>
</div>
        </div>
    </div>
</div>
<!--------------------contact--------------------->
<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact Me</h1>
                <p>If you want, You can contact me through</p>
                <p><i class="fa-solid fa-paper-plane"></i><a href="mailto:kireeti2808@gmail.com">email</a></p>
                <p><i class="fa-solid fa-phone"></i>+91 9121366331</p>
                <div class="social-icons">
                    <a herf=""><i class="fa-brands fa-linkedin"></i></a>
                    <a herf=""><i class="fa-brands fa-x-twitter"></i></a>
                    <a herf=""><i class="fa-brands fa-x-github"></i></a>
                </div>
            </div>
                
            <div class="contact-right">
                <form>
                    <input type="text" name="Name" placeholder="Your Name" required>
                    <input type="email" name="email" placeholder="Your Email" required>
                    <textarea name="message" rows="6" placeholder="Your message"></textarea>
                    <button type="Submit" class="btn">Submit</button>
                </form>
                <div id="video">
                    <video controls autoplay src="portfolio video.mp4" width="960" height="540"></video>
                </div>
            </div>
        </div>
    </div>
    <div class="copyright">
        <p>&copy; 2024 kireeti bussa. All rights reserved.</p>
    </div>
</div> 
</body>
</html>
