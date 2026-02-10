# Ex03 Places Around Me
## Date: 10.02.2026

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
map.html
<html>
    <head><title> Image map </title></head>
    <body>
        <h1> Cuddalore </h1>
        <h5> Moushmitha (25014643)</h5>
        <img src="Screenshot 2026-02-09 110030.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Manikoondu" title="Manikoondu" href="manikoondu.html" coords="1044,208,86" shape="circle">
    <area target="" alt="Collector Office" title="Collector Office" href="co.html" coords="719,222,852,310" shape="rect">
    <area target="" alt="Arcot Woodlands Hotel" title="Arcot Woodlands Hotel" href="arcot.html" coords="894,674,894,755,996,761,1069,716,983,669" shape="poly">
    <area target="" alt="Government Hospital" title="Government Hospital" href="gh.html" coords="806,569,52" shape="circle">
    <area target="" alt="Kumaran Mess" title="Kumaran Mess" href="mess.html" coords="969,406,1127,491" shape="rect">
</map>
    </body>
</html>

arcot.html
<html>
    <head><title>MAP</title></head>
    <body bgcolor="light blue">
        <h1>Cuddalore</h1>
        <h4>Arcot Woodlands Hotel</h4>
        <p>Arcot Woodlands Hotel in Cuddalore is a well-regarded, centrally located hotel featuring 40 renovated, clean, and spacious rooms. Known for its excellent, on-site vegetarian restaurant (Abirami), the hotel offers amenities including free Wi-Fi, 24-hour room service, ample, secure parking, an elevator, and banquet/conference facilities. It is considered a comfortable, reliable choice in the area. </p>
        
    </body>
</html>

co.html
<html>
    <head><title>MAP</title></head>
    <body bgcolor="green">
        <h1>Cuddalore</h1>
        <h4>Collector Office</h4>
        <p>The Cuddalore District Collectorate, located in Manjakuppam (607001), serves as the administrative headquarters for Cuddalore district, Tamil Nadu</p>
        
    </body>
</html>

gh.html
<html>
    <head><title>MAP</title></head>
    <body bgcolor="pink">
        <h1>Cuddalore</h1>
        <h4>Government Hospital</h4>
        <p>Cuddalore has several government medical institutions, primarily led by the Government Head Quarters Hospital and the Government Cuddalore Medical College & Hospital. 
</p>
        
    </body>
</html>

manikoondu.html
<html>
    <head><title>MAP</title></head>
    <body bgcolor="yellow">
        <h1>Cuddalore</h1>
        <h4>Manikoondu</h4>
        <p>Manikoondu is a landmark, historical landmark of Cuddalore</p>
        
    </body>
</html>

mess.html
<html>
    <head>
        <title>MAP</title>
    </head>head>
    <body bgcolor="red">
        <h1 align="center">Cuddalore</h1>
        <h4 align="center">Kumaran Mess</h4>
        <p>Kumaran Mess in Cuddalore is a 15-year-old popular local eatery, specifically renowned for its authentic non-vegetarian meals and seafood. 
</p>
        
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (21).png>) 
![alt text](<Screenshot (16).png>) 
![alt text](<Screenshot (17).png>) 
![alt text](<Screenshot (18).png>) 
![alt text](<Screenshot (19).png>) 
![alt text](<Screenshot (20).png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
