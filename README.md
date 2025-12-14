# Ex.05 Book Cover Page Design
## Date:14/12/2025

## AIM:
To design a book back cover page using HTML and CSS.

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
        <title>Book Page</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
        <div class="container">  
         <div class="About">   
             <h1>Information About The Book</h1>
        <div class="hrstyle">
            <hr style="color: blueviolet;">
        </div>
          <p>Blockchain technology is revolutionizing business processes by providing a secure, 
            decentralized, and efficient way to record and share information. 
            It offers several benefits, including enhanced security, improved efficiency,
             and reduced costs. Here are some key aspects of blockchain technology in business:</p>
         </div>
             <div class="quote">
            <h2><strong>"Blockchain is a tool for unlocking new levels of efficiency and trust in business process.
                it is the driving force behind a new era of digital transformation.”</strong></h2>
        </div>
        <div class="author">
            <img src="cov2.jpg" alt="Author Image">
            <div><strong>T.NITHYASRI</strong></div>
            <div>
                T.NITHYASRI is a writer who loves turning emotions and thoughts into words.
                Her writing reflects life’s small moments, deep feelings, and quiet reflections.
                With simple yet meaningful language, she aims to touch hearts and connect with readers on an emotional level.
            </div> 
        </div>
        <div class="PUBLISHER">
            SEC PUBLISHERS-
                PRINTED IN INDIA
            <div>
            PRICE:RS.700
            </div>
        </div>
    </body>
</html>

style.css

body
{
    background:url('nithu.png')no-repeat center/contain;
    font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
    padding: 10px;
    border-color: blue;
    border-top: red;
    border-bottom: maroon;
    
}
.container
{
    
    width:30%;
    margin:auto;
    padding: 20px 40px;
    border-radius: 20px;
    border: 3px lavender;
    flex: content;
}
.About
{
    font-style: oblique;
    font-size: medium;
    font-weight: bolder;
    color: rgb(100, 83, 253);
    margin-top: 15px;
    margin-bottom: 15px;
    border-top: rebeccapurple;
}
.quote
{
    background-color: rgb(245, 147, 208);
    padding:10px;
    margin: 15px;
    border-right: 7px yellowgreen;
    border-left: solid greenyellow;
    font-style: oblique;
    font-weight: 200;
    font-family: 'Times New Roman', Times, serif;
}
.Author
{
    display:flex;
    background-color: blanchedalmond;
    padding: 30px;
    border-radius: 20px;
    border: outset rebeccapurple;
    margin-top: 25px;
    margin-bottom: 25px;
    font-weight:bolder;
    font-style: calc();
    color: rgb(73, 43, 226);
    flex-direction: row;
}
.Author img
{
    width:100px;
    height:150px;
    border-radius: 6px;
    margin-right: 15px;
    margin-left: 15px;
    border:4px rgb(2, 31, 14);
    color: rgb(6, 224, 152);
    flex-wrap: wrap;
}
.PUBLISHER
{
    margin-top: 20px;
    margin-bottom: 20px;
    padding: 12px 20px;
    background-color: rgb(248, 9, 152);
    color:aquamarine;
    border-radius: 0 0 12px 12px;
    text-align: end;
    font-weight: 200;
    font-style: oblique;
}

```

## OUTPUT:
![alt text](<cov out.png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
