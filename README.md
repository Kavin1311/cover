# Ex.06 Book Front Cover Page Design
## Date: 26.04.2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<!DOCTYPE html>
<html>

<head>
    <title>BOOK COVER</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url(8go81z8i93s91.jpg);
            background-size: cover;
        }
            
        
        .insight{
            color:azure;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(255, 255, 255);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:azure;
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            color:azure;
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:azure;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color:azure;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
            text-align: center;
        }
        .myphoto {
            position: relative;
            margin-top: 20px; /* Adjust the margin-top to position the image below the subtitle */
            margin-left: auto;
            margin-right: auto;
            left: 140px;
            top: 185px;
            width: 90px;
            height: 90px;
            border-radius: 50%;
            overflow: hidden;
        }
        
        .myphoto img {
            width: 100%;
            height: 120%;
            object-fit: cover;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                TRAVELLER
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>"Wandering Souls: A Traveler's Odyssey"</h1></div>
            <div class="subtitle">
                 Explore the world through pages
            </div>
            <div class="subtitle">
                 
            </div>
            
            <br>
            <br>
            <br>
            <br>

            <div class="myphoto">
                <img src="fa96cfe1-490e-4d0c-8055-b3dbaa82657c.jpg" width="120" height="120" >
           
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>FIRST EDITION </b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>KAVINAJAI.T(212223100020)</b>
            </div>
        </div>
        </body>
        

</html>
```

## OUTPUT:
![alt text](kavin/app1/static/frontcover.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
