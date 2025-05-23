# Ex.06 Book Front Cover Page Design
## Date: 13-05-2025

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

Name : Rohit G P

Reg no : 212224220082

```
<!DOCTYPE html>
<html>
<head>
    <title>Quantum Physics Book Cover</title>
    <style>
        body {
            background-color: white;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 400px;
            height: 600px;
            margin: 50px auto;
            border: 2px solid black;
            position: relative;
            overflow: hidden;
            font-family: Arial, sans-serif;
        }
        .container img.bg {
            width: 100%;
            height: 100%;
            object-fit: cover;
            display: block;
        }
        .title {
            color: white;
            position: absolute;
            top: 20%;
            left: 50%;
            transform: translateX(-50%);
            font-size: 26px;
            font-weight: bold;
            text-shadow: 2px 2px 5px black;
            text-align: center;
            font-size: 2.5rem;
            font-weight: 900;
            text-transform: uppercase;
      
        }
        .footer {
            position: absolute;
            bottom: 0;
            width: 100%;
            text-align: right;
            color: white;
            background: rgb(28, 28, 87);
            text-shadow: 1px 1px 3px black;
            /* padding: 10px -10px; */
        }
        .author {
          font-size: 1.3rem;
          font-weight: 700;
          margin: 0;
          letter-spacing: 0.05em;
          text-shadow: 0 2px 5px rgba(0,0,0,0.8);
          padding-top: 10px;
          padding-right: 10px;
        }
        .college {
          font-size: 0.9rem;
          opacity: 0.;
          margin: 2px 0 0 0;
          padding: 10px;
          text-shadow: 0 2px 4px rgba(0,0,0,0.5);
        }
    </style>
</head>
<body>
    <div class="container">
        <img class="bgb" src="https://w0.peakpx.com/wallpaper/311/873/HD-wallpaper-blue-ripple-amoled-dark-dots-higgsas-iphone-physics-quantum-samsung-simple.jpg" alt="Quantum Background">

        <h1 class="title">Introduction to Quantum Physics</h1>
        <div class="footer">
            <h3 class="author">Rohit G P</h3>
            <h4 class="college">Saveetha Engineering College</h4>
        </div>
    </div>
</body>
</html>

```

## OUTPUT:

![Output](<Screenshot 2025-05-13 114321.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
