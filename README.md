# Ex.06 Book Front Cover Page Design
## Date:

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
<html>
    <style>
        .box{
            height: 700px;
            width: 500px;
            margin:auto;
            position: relative;
            
        }
        .title{
            font-size: xx-large;
            font-weight: 400;
            font-style: italic;
            top:0%;
            left:10%;
            color: maroon;
            position: absolute;
            
        }
        .caption{
            font-size: x-large;
            font-weight: 1000;
            font-style: oblique;
            color:rgb(44, 161, 190);

            top:50%;
            right:22px;
            position:absolute;
        }
        .author{
            
            
           
            right: 0%;
            bottom: 0px;
            position: absolute;
            
           
        }
        .name{
            font-size: large;
            font-weight: 900;
            font-style: initial;
            position: absolute;
            right: 4%;
            bottom :10%;
            color: white;

        }
        .bottom-bar {
            position: absolute;
            bottom: 10px;
            left: 20px;
            font-size: medium;
        }
        .publisher, .date {
            display: inline-block;
            margin-right: 10px;
            font-weight: 600;
            color: white;

        }
    </style>
    <body>
        <div class="box">
            
            <center>
                <img src="knoowfilms-u_I2jt7EiEo-unsplash.jpg" width="100%" height="100%">
            </center>
           
            <div class="title" >
                <h1>HOW TO BECOME A DATA ANALYST?</h1>
            </div>
            
            <div class="caption">
                <p>
                    "A complete roadmap to handle datasets" 

                </p>
            </div>
            <hr>
            <div class="name">
                <p>YUVARAJ V</p>
            
            </div>
            
            <div class="author">
                
                <img src="yuvi.uv.jpg" width="85" height="85">
            </div>
    
            <div class="bottom-bar">
                <div class="publisher">Publisher: YuviBooks</div>
                <div class="publisher">Extended Edition-->></div>
                <div class="date">2024</div>
              
            </div>
            <div class="strip"></div>
        </div>
    </body>
</html>
## OUTPUT:
```
![Screenshot 2024-10-31 204013](https://github.com/user-attachments/assets/9693613b-b944-43a8-b7d5-41fdd90bc946)
![Screenshot 2024-11-01 233758](https://github.com/user-attachments/assets/2818fadb-da56-45c0-ad64-0399dbdbf247)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
