# Ex.04 Book Front Cover Page Design
## Date:18.042025

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
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Cover</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      height: 100vh;
      background: #eee;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Courier New', monospace;
    }

    .book {
      width: 420px;
      height: 720px;
      background: url('back.jpg') no-repeat center center;
      background-size: cover;
      padding: 30px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      border: 1px solid #ccc;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
    }

    .top-label {
      font-weight: bold;
      font-size: 14px;
      border-bottom: 2px solid black;
      width: fit-content;
      margin-bottom: 30px;
    }

    .title {
      font-size: 26px;
      font-weight: bold;
      line-height: 1.4;
      margin-bottom: 12px;
    }

    .subtitle {
      font-size: 16px;
      margin-bottom: 40px;
    }

    .extended {
      font-weight: bold;
      font-size: 16px;
      color: black;
     
      padding: 5px 10px;
      display: inline-block;
      margin-bottom: 20px;
    }

    .photo {
      width: 120px;
      height: auto;
      border: 3px solid white;
      align-self: flex-end;
      background-color: white;
      padding: 3px;
    }

    .bottom-bar {
      display: flex;
      justify-content: space-between;
      font-weight: bold;
      font-size: 14px;
      color: #fff;
      border-top: 2px solid white;
      padding-top: 8px;
    }

    .author {
      color: #fff;
    }
  </style>
</head>
<body>
  <div class="book">
    <div>
      <div class="top-label">SEC STUDENT INSIGHT</div>
      <div class="title">THE LIFE:<br>Completely Ruined One</div>
      <div class="subtitle">with Happiness and Realization</div>
      <div class="extended">First Limited Edition</div>
    </div>

    <img src="photo.jpg" alt="Author Photo" class="photo" />

    <div class="bottom-bar">
      <div class="author">Mr.Rishab.P.Doshi</div>
      <div>SEC</div>
    </div>
  </div>
</body>
</html>
```

## OUTPUT:
![alt text](image-1.png)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
