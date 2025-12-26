# Ex03 Places Around Me
## Date: 18/12/2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Map</title>
    <style>
        img{
            display: block;
            margin: auto;
            margin-top: 9%;
            border: 2px solid black;
        }
    </style>
</head>
<body>
    <img src="workplace.jpeg" alt="Workplace" usemap="#workmap" width="400" height="379">

    <map name="workmap">
    <area shape="rect" coords="34,44,270,350" alt="Computer" href="https://www.google.com/search?q=computer">
    <area shape="rect" coords="290,172,333,250" alt="Phone" href="https://www.google.com/search?q=phone">
    <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="https://www.google.com/search?q=cup+of+coffee">
    </map>
</body>
</html>
```
## OUTPUT

<img width="1354" height="727" alt="image" src="https://github.com/user-attachments/assets/c43aad7a-c40c-4f19-a007-1febf5799313" />
<img width="1339" height="709" alt="image" src="https://github.com/user-attachments/assets/7b928179-e457-4892-bd9e-3c1cfbaf7207" />
<img width="1378" height="722" alt="image" src="https://github.com/user-attachments/assets/759a9a3d-0b87-4f82-a309-f37647f8fa11" />








## RESULT
The program for implementing image maps using HTML is executed successfully.
