# Ex.06 Book Front Cover Page Design
# Date:
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
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width,
initial-scale=1.0">
 <title>Jijo's book</title>
 <link rel="stylesheet" href="style.css">
</head>
<body>
 <div class="book-cover">
 <div class="book">
 <h3>Winner of pulicer prize</h3>
 <h1>MY</h1>
 <h1>BOOK</h1>
 <H1>COVER</H1>
 <h3>Secret in silicon valley startup</h3>
 <h3>by Jijo.H.Jebas</h3>

 </div>
 </div>
</body>
</html>
```
style.css
```
*{
 margin: 0;
 padding: 0;
 box-sizing: border-box;
}
.book-cover{
 display: flex;
 height: 100vh;
 align-items: center;
 justify-content: center;
 background-color: rgb(217, 207, 223);
}
.book{
 width: 600px;
 height: 700px;
 box-shadow: 0 4px 8px rgba(0,0,0,0.2);
 border-radius: 30px;
 background-color: #e4320a;
 background-image:
url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?ixlib=rb-4.0.3&ixid=https://i.pinimg.com/736x/e6/4d/b2/e64db2b58e99f6848403aa173b80aecb.jpg%3D%3D&auto=format&fit=crop&w=500&q=60');
 align-items: center;
 justify-content: center;
 text-align: center;
 background-size: cover;
}
h3{
 font-size: 32px;
 margin-top: 100px;
 color: white;
}
h1{
 font-size: 60px;
 margin-top: 20px;
 font-weight: bold;
}
```
# OUTPUT:
<img width="1919" height="986" alt="image" src="https://github.com/user-attachments/assets/875a5076-eb7f-4de8-8238-37e8cb97307e" />

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
