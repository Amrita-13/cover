# Ex.06 Book Front Cover Page Design
## Date:7.10.2025

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
cover.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Book Front Cover Page  </title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="bookcover">
            <div class="insight">
                EXPERT SECURITY
            </div>
            <div class="hr1">
                <hr>
            </div>
            <div class="h1">
                <h1>Introduction to Cyber Security</h1>
            </div>
            <div class="para">
                <p>Gateway to secured browsing </p>
            </div>
            <div class="pic">
                <img src= "mypic.jpg" width="150" height="150" >
            </div>
            <div class="hr2">
                <hr>
            </div>
            <div class="name">
                <p><b>Amrita B.S(25018474)</b></p>
            </div>
            <div class="pub">
                <b> SEC </b>
            </div>
            <div class="edition">
                <b> FIRST Edition </b>
            </div>
        </div>
    </body>
</html>

style.css
.bookcover {
    width: 400px;
    height: 640px;
    color: rgb(25, 199, 60) (221, 39, 39);
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    background-image: url(back2.JPG);
    background-size: cover;
    }
.insight {
    color: rgb(227, 12, 12);
    }
.hr1 {
    width: 130px;
    color: rgb(177, 42, 42) ;
    }
.h1 {
    font-size: larger;
    font-family: Arial, Helvetica, sans-serif;
    text-align: center;
    position: relative;
    top: 30px;
    color:rgb(6, 6, 121);
    }
.para {
    font-size: medium;
    font-family: Arial, Helvetica, sans-serif;
    position: relative;
    top: 40px; 
    color: rgb(122, 79, 240) (221, 39, 39); 
    }
.edition {
    font-size: large;
    font-family: Arial, Helvetica, sans-serif;
    color:rgb(112, 7, 7) ;
    top: 90px;
    position: relative;
    }
.pic {
    position: relative;
    top: 150px;
    left: 250px;
    width: 100px;
    height: 100px;
    background-size: cover;
    color:rgba(78, 2, 2, 0.853) ;
    }
.hr2 {
    position: relative;
    width: 400px;
    top: 200px;
    color:rgb(203, 13, 13);
    }
.name {
    font-size: medium;
    font-family: Arial, Helvetica, sans-serif;
    display: inline;
    position: relative;
    color:black;
    top: 210px;
    }
.pub {
    font-size: large;
    position: relative;
    top: 180px;
    left: 330px;
    color:rgb(149, 19, 19);
    }
```

## OUTPUT:
![alt text](<Screenshot 2025-10-07 143916.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
