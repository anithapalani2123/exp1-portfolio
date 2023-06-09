# EXP 01 - PORTFOLIO

## AIM:

To create a portfolio using HTML and CSS

## ALGORITHM:

1. Set up the basic structure of your HTML document.

2. Create a CSS file named "styles.css" and link it to your HTML document. This file will contain the CSS rules for styling your portfolio.

3. Design the layout of your portfolio using HTML elements such as < header >, < nav >, < section >, < article >, and < footer >. Use appropriate classes or IDs to style these elements later with CSS.

4. Add a header section to display your name or the title of your portfolio.

5. Add images or media to enhance your portfolio. You can use the <img> tag to display images and embed videos or other media using appropriate HTML tags.

6. Apply responsive design techniques to ensure your portfolio looks good on different devices and screen sizes. Use CSS media queries to adjust the layout and styling as needed.

7. Apply CSS styling to your portfolio elements by targeting their respective classes or IDs in the "styles.css" file. Customize the colors, fonts, spacing, and other visual properties to match your desired design

## CODE:

### HTML CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PORTFOLIO</title>
    <link rel="stylesheet" href="g.css" />
    <link href='https://fonts.googleapis.com/css?family=Didact Gothic' rel='stylesheet'>
    <link href='https://fonts.googleapis.com/css?family=Alegreya' rel='stylesheet'>
    <link href='https://fonts.googleapis.com/css?family=Aclonica' rel='stylesheet'>
</head>
<body>
    <nav class="navbar">
        <ul>
            <li><a herf="#home">HOME</a></li>
            <li><a herf="#about">ABOUT ME</a></li>
            <li><a herf="#education">EDUCATION</a></li>
            
            <li><a herf="#portfolio">PORTFOLIO</a></li>
            <li><a herf="#contact">CONTACT ME</a></li>
        </ul>
    </nav>
    <section id="home">
        
           
        
        <h1 class="heading"> HI&emsp;&emsp;&emsp;</h1><br>
        <h1 class="heading">&emsp;&emsp;I AM ANITHA </h1>
        <br>
        <P class="para">&emsp;ML ENGINEER </P>
    
    </section>
<section class="sec">                                                                                                                                                                                                                                                                                                                                                                                                                                                                  
    <div class="gal">
        <img src="ani2.jpg" alt="">
    </div>
    <!-- <div class="box1"></div> -->
    <p class="box">
        I am anitha p studying in saveetha engineering college in the department aiml 2nd year. 
        I did my schooling in bharathi matriculation higher secondary school. I scored 90% in my 10th and 12th grade.
        I am anitha p studying in saveetha engineering college in the department aiml 2nd year. 
        I did my schooling in bharathi matriculation higher secondary school. I scored 90% in my 10th and 12th grade.
        <br><br>

        I am anitha p studying in saveetha engineering college in the department aiml 2nd year.
        I am anitha p studying in saveetha engineering college in the department aiml 2nd year. 
        I did my schooling in bharathi matriculation higher secondary school. I scored 90% in my 10th and 12th grade.
        I am anitha p studying in saveetha engineering college in the department aiml 2nd year. 
        I did my schooling in bharathi matriculation higher secondary school. I scored 90% in my 10th and 12th grade.
      
    </p>
    
</section>   
<section class="sec1">
    <div class="expect"><p class="font" ><u>EXPERTISE:</u></p>
        <br>
        <ul >
            <li >Product Development (FUSION360)</li><br>
            <li>AR filters (INSTAGRAM / SNAPCHAT)</li><br>
            <li>Web Designer</li><br>
            <li>Modelling</li><br>
            <li>Communication SkillS</li><br>
        </ul>
    
    </div>
    <div class="lang"><p class="font" ><u>PROGRAMMING LANUGUAGES:</u></p>
        <br>
        <ul >
            <li >PYTHON</li><br>
            <li>C</li><br>
            <li>JAVA</li><br>
            <li>JAVA SCRIPT</li><br>
            <li>HTML & CSS</li><br>
            
        </ul>
    
    </div>
    <div class="edu"><p class="font" ><u>EDUCATION:</u></p>
        <br>
        <ul >
            <li >2019 - 10TH GRADE in Bharathi Vidhya Mandhir</li><br>
            <li>2021 - 12TH GRADE in Bharathi Matriculation higher Secondary School</li><br>
            <li>2025 - B.Tech AIML in Saveetha Engineering College</li><br>
            
        </ul>
    
    </div>
    
</section> 
<section class="thirdbox">
    
        <p class="font" style="font-size: 30px; "><b>Contact me:</b></p><br>
        <div>
            <a href="https://github.com/anithapalani2123"><img src="git.png"  class="git"alt="Photo" width="100" height="100"></a>
        </div>

        <div class="what">
            <a  href="https://wa.me/7305444188"><img src="whatsapp.png" alt="Photo" width="120" height="120"></a>

        </div>
        <div class="link">
            <a href="https://www.linkedin.com/in/anitha-palani-b79a3a22a/"><img src="linkedin.png" alt="Photo" width="120" height="120"></a>

        </div>
        


</section>
<div class="footer">
    <p>copyright &#169;Developed by  ANITHA PALANI</p>
</div>
    

    
</body>
</html>
```

### CSS CODE:
```
*
{
    margin: 0;
    padding: 0;
}
html{
    scroll-behavior: smooth;
}

#home{
    display: flex;
    flex-direction: column;
    height: 1000px;
    justify-content: center;
    align-items: center;
    background-color: rgba(23, 8, 8, 0.5);
    color: rgb(27, 14, 14);
    font-size: 25px;
}
#home::before{
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    background: url('ani.jpg') no-repeat center center/cover;
    height: 1000px;
    width: 100%;
    z-index: -1;
    /* opacity: .85; */
}
.heading{
    color: rgb(252, 249, 249);
    
    font-family: 'Didact Gothic';font-size: 22px;
    text-align: center;
    transform: scale(1,1.3);
    padding-top: 10px;
    letter-spacing: .2em;

}
.para
{
    color: rgb(204, 177, 177);
    font-style: italic;
    font-size: large;
}
.sec{
    height: 700px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: medium;
    color: #011311;
    background-color:  rgba(30, 52, 65, 0.952);
    padding: 50px;
    
}

.navbar{
    display : flex;
    justify-content: center;
    height: 50px;
    align-items: center;
    position: sticky;
    top: 0;
}
.navbar::before{
    content: "";
    position: absolute;
    background-color: #061425;
    height: 100%;
    width: 100%;
    z-index: -1;
}
.navbar ul{
    display : flex;
    list-style: none;
}
.navbar ul li{
    font-size: 1.1rem;
}
.navbar ul li a{
    padding: 5px 20px;
    text-decoration: none;
    color: rgb(255, 255, 255);
}
.navbar ul li a:hover{
    border-bottom: 2px solid yellow;

}
.s2
{
    display:flex;
    flex-direction: column;
    height: 1000px;
}
.box
{
    display: block;
    /* top: 0%; */
    height: 440px;
    width: 800px;
    color: blanchedalmond;
    background-color: #010811;
    margin-left: 500px;
    margin-top: -500px;
    border-radius: .50px;
    font-family: 'Alegreya';
    font-size: 22px;
    word-spacing: 9px;
    letter-spacing: 0.45px;
    padding: 15px;
    
    
}
/* .box1::before{
    content: "";
    position: absolute;
    top: 0;
    left: 0;
} */
.box1
{
    display: block;
    top: 50%;
    height: 500px;
    width: 300px;
    color: blanchedalmond;
    background-color: rgba(236, 19, 19, 0.977);
    margin-left: 100px;
    margin-top: 130px;
    border-radius: 20px;
    z-index: -1;
    opacity: .8;
}

.h1{
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    color: #ffffff;
}
.gal img{
    
    width: 335px;
    height: 500px;
    /* padding: 10px; */
    margin-left: 100px;
    margin-top: 90px;
    opacity: .6;
    border-radius: 20px;

}
.sec1
{
    height: 550px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: medium;
    color: rgba(229, 235, 238, 0.952) ;
    background-color:  #010811;
    padding: 50px;
}
.expect
{
    height:250px;
    width: 250px;
    background-color: rgba(30, 52, 65, 0.952);
    margin-left: 120px;
    margin-top: 100px;
    padding: 50px;
    word-spacing: 5px;
    letter-spacing: 2px;
    border-radius: 60px;
    opacity: .9;
}
.lang
{
    height:250px;
    width: 250px;
    background-color: rgba(30, 52, 65, 0.952);
    margin-left: 600px;
    margin-top: -350px;
    padding: 50px;
    word-spacing: 5px;
    letter-spacing: 2px;
    border-radius: 60px;
    opacity: .9;
}
.edu
{
    height:250px;
    width: 250px;
    background-color: rgba(30, 52, 65, 0.952);
    margin-left: 1100px;
    margin-top: -350px;
    padding: 50px;
    word-spacing: 5px;
    letter-spacing: 2px;
    border-radius: 60px;
    opacity: .9;

}
.font
{
    font-family: 'Aclonica';
    font-size: 22px;
    color: antiquewhite;
}
.thirdbox
{
    height: 200px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: medium;
    color: rgba(229, 235, 238, 0.952) ;
    background-color:  rgba(30, 52, 65, 0.952);
    padding: 50px;
}
.footer {
    text-align: center;
    padding: 3px;
    background-color: #010811;
    color: white;
  }
.git
{
    margin-left: 500px;
    margin-top: -10px;
    
    
}
.what
{
    margin-left: 300px;
    margin-top: -120px;
}
.link
{
    margin-left: 100px;
    margin-top: -120px;
}
```
## OUTPUT:
![p1](https://github.com/anithapalani2123/exp1-portfolio/assets/94184990/cafd1214-f189-48e0-a92d-a2cca4cbbb05)


![p5](https://github.com/anithapalani2123/exp1-portfolio/assets/94184990/8ae2acb0-5e0c-4d84-9242-dc723db782f6)
![p3](https://github.com/anithapalani2123/exp1-portfolio/assets/94184990/01fcb29f-c569-4c84-978e-d488ddb3cd67)


![p4](https://github.com/anithapalani2123/exp1-portfolio/assets/94184990/b884d74f-b823-417c-b7c2-b58553490db4)




## RESULT:

Thus, a Portfolio is created using HTML and CSS.


























