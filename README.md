# Ex.06 Book Front Cover Page Design
# Date:05-10-2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
book.html:

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <link rel="stylesheet" href="link.css">
        <title>COVER</title>
        
    </head>
    <body align="center">
        <div class="name"><h1 align="certer">MINHAJ (25006694)</h1></div>
        <div class="min">
            <div class="page1">
                <h1>SEC INSIGHT</h1>
                <hr>
            </div>
            <div class="page2">
                <p>FUNDAMENTAL OF WEB DEVELOPEMENT</p>
            </div>
            <br>
            <div class="page3">
                <h2>  HTML AND CSS</h2> 
                <h3>INTRODUCTION TO WEB DEVELOPEMENT</h3>
            </div>
            <div class="picture">
                <img src="IMG_20250629_162405_128.jpg">
            </div>
            <div class="page4">
                <h2>NEW EDITION</h2>
                <hr>
                <h2 align="center">J.MINHAJ AHAMED</h2>
            </div>
            
        </div>
    </body>
</html>

link.css:

.name{
    text-align:center;
    position: relative;
    right:50px;
}




body{
    background-color:rgb(233, 10, 10) ;
    font-family:blueCarbria,Chchin,Georgia,Time,'Time New Roman',serif;
    font-style:oblique;
    color:rgb(8, 243, 110);
    

}
.min{
    background-image:url(cover.png);
    background-clip:border-box;
    background-position-x:right ;
    background-size:cover;
    height: 800px;
    width:600px;
    position:relative;
    left: 400px;
    border:solid 10px rgb(151, 100, 255);
}
.page1{
    margin:auto;
   

}
.page2{
    font-size:50px;
    text-align:center;
    position:relative;
    top:50px;

}
.page3{
    position:relative;
    left:15px;
    font-size: 20px;

}

.picture{
    width: 150px; 
    height:150px;      
    position: relative;
    top: 70px;
    left:300px;
    border: 2px solid orangered;
    background: white;
    overflow: hidden;
}

.picture img{
    width:100%;
    height:100%;
    object-fit:cover;
}
.page4{
    position:relative;
    top:50px;
    left:5px;
    font-weight: bold;
}
```
# OUTPUT:
![alt text](output.png)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
