# Ex.06 Book Front Cover Page Design
## Date: 28-04-2024

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
book.html
~~~
<html>
<head>
    <title>Book Cover</title>
    <style>
        
        body{
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: white; 
        }
        

        .bookpage{
            width: 400px;
            height: 600px;
            color: black;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url('b.avif');
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
        }

        .linestart{
            width: 160px;
        }

        .bname{
            font-family: 'Times New Roman', Times, serif;
            font-size: larger;
            text-align: center;
        }

        .bsub{
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-size: medium;
            position: relative;
            top: 35px;
        }

        .edition{
            color: darkgreen;
            font-size: medium;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            position: relative;
            top: 85px;
        }

        .foto{
            position: relative;
            top: 140px;
            left: 256px;
            width: 100px;
            height: 100px;
        }
       
        .lineend{
            width: 400px;
            position: relative;
            top: 180px;
        }

        .myname{
            display: inline;
            position: relative;
            color: darkblue;
            top: 190px;
            font-family: Arial, Helvetica, sans-serif;
            font-size: medium;
        }

        .clg{
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;
            color: antiquewhite;
        }
    </style>
</head>

<body>
    <div class="bookpage">
        <h4 style="color: paleturquoise;"> Computer Communications and Networks</h4>

        <div class="linestart">
            <hr>
        </div>

        <div class="bname">
            <h1 style="color: royalblue;">Software Engineering in the Era of Cloud Computing</h1>
        </div>

        <div class="bsub">
            <p style="color:purple;">A practical approch for learning and implementation</p>   
        </div>

        <div class="foto">
            <img src="varsha.jpg" width="120" height="150">
        </div>

        <div class="lineend">
            <hr>
        </div>

        <div class="myname">
            <p>VARSHA  A </p>
        </div>

        <div class="clg">
            SEC
        </div>

        <div class="edition">
             Second Edition
        </div>

    </div>
</body>
</html>
~~~

## OUTPUT:

![Screenshot 2024-04-28 004546](https://github.com/04Varsha/cover/assets/149035374/1fd7a735-9bd8-45e4-b381-499a5d7324c9)

![Screenshot 2024-04-28 014846](https://github.com/04Varsha/cover/assets/149035374/74f2875c-eeb1-44c8-8249-54a4da89b6d7)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
