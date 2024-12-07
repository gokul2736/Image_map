# Ex04 Places Around Me
# Date:07-12-2024
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Mapping</title>
</head>
<body>
<section class="header">
    <img src="C:\Users\admin\Desktop\SEM 1\WEB DEV\Img mapping Gokx\Image.png" usemap="#image-map" alt="Map Image">

    <map name="image-map">
    <area target="" alt="Tirupati" title="Tirupati" href="C:\Users\admin\Desktop\SEM 1\WEB DEV\Img mapping Gokx\tirupati.html" coords="526,179,393,217,399,272,570,214" shape="poly">
    <area target="" alt="Chennai" title="Chennai" href="C:\Users\admin\Desktop\SEM 1\WEB DEV\Img mapping Gokx\chennai.html" coords="799,373,715,421,723,457,742,496,726,537,797,584,821,461,835,390" shape="poly">
    <area target="" alt="Vellore" title="Vellore" href="C:\Users\admin\Desktop\SEM 1\WEB DEV\Img mapping Gokx\vellore.html" coords="329,503,284,500,289,549,343,593,437,535,380,479,333,463" shape="poly">
</map>
</section>
</body>
</html>
```

# OUTPUT
![Screenshot (21)](https://github.com/user-attachments/assets/e810b6e7-ce8a-4229-ba57-277373640b3e)

# RESULT
The program for implementing image maps using HTML is executed successfully.
