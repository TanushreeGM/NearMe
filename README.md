# Ex03 Places Around Me
## Date: 28/11/2025

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
    <head>
        <title>City Map</title>
    </head>
    <body align="center">
        <h1><font color="darkblue">Ulhasnagar-2</font></h2>
        <h3><font color=lightblue">Tanushree G (25012099)</font></h3>
        <br>
        <img src="map.png" usemap="#nagar">
        <map name="nagar">
            <area target="" alt="Gol-Maidan" title="Gol-Maidan" href="gol.html" coords="661,38,148" shape="circle">
            <area target="" alt="Sapna Garden" title="Sapna Garden" href="garden.html" coords="685,792,870,891" shape="rect">
            <area target="" alt="Gajanand Market" title="Gajanand Market" href="market.html" coords="951,312,1145,256,1224,370,1017,432,961,400" shape="poly">
            <area target="" alt="Hira Marriage Hall" title="Hira Marriage Hall" href="hall.html" coords="640,466,33" shape="circle">
            <area target="" alt="Kishore patties wala" title="Kishore patties wala" href="shop.html" coords="768,144,727,169,726,199,799,177" shape="poly">

        </map>
    </body>
</html>

gol.html

<html>
    <head>
        <title>Gol-Maidan</title>
    </head>
    <body bgcolor="#79b791" align="center">
        <h1>Ulhasnagar-2</h1>
        <h3>Gol-Maidan</h3>
        <hr>
        <font size="5">
        Gol-Maidan in Ulhasnagar serves as an essential community space for residents. This open area is often utilized for various activities, including sports, cultural events, and casual gatherings. It is surrounded by greenery, making it a pleasant spot for relaxation and socialization. 
        </font> 
    </body>
</html>

garden.html

<html>
    <head>
        <title>Sapna garden</title>
    </head>
    <body bgcolor="#FFFF90" align="center">
        <h1>Ulhasnagar-2</h1>
        <h3>Sapna Garden</h3>
        <hr>
        <font size="5">
        Sapna Garden fosters a connection between thousands of people and nature. The park provides a peaceful environment, whether one is with family and friends or enjoying solitude. Sapna Garden is perfect for spending time with friends, picnicking, and gathering in groups of all sizes, making it an ideal destination.
        </font> 
    </body>
</html>

hall.html

<html>
    <head>
        <title>Hira Marriage Hall</title>
    </head>
    <body bgcolor="#FF758F" align="center">
        <h1>Ulhasnagar-2</h1>
        <h3>Hira Marriage Hall</h3>
        <hr>
        <font size="5">
        Hira Marriage Hall, Ulhasnagar, Mumbai, is a great place to celebrate tying the knot with your friends and family. Located approximately 4 km from Kalyan Junction, (via Kalyan Ambernath Rd/Kalyan - Badlapur Rd) your guests can easily access this location without much fuss.
Hira Marriage Hall, Mumbai, has a team of in-house caterers that provide your guests with a delicious and freshly made variety of pure vegetarian and nonvegetarian food for your guests to enjoy.
        </font> 
    </body>
</html>

market.html

<html>
    <head>
        <title>Gajanand Market</title>
    </head>
    <body bgcolor="#4895EF" align="center">
        <h1>Ulhasnagar-2</h1>
        <h3>Gajanand Market</h3>
        <hr>
        <font size="5">
        Gajanand Market is more than just a shopping destination—it’s a vibrant hub where tradition, quality, and community come together. Located in the heart of the city, Gajanand Market has become a trusted name for shoppers seeking the perfect blend of value and variety. Whether you’re looking for fresh produce, household essentials, fashionable apparel, or specialty items, our diverse range of shops caters to every need under one roof.
        </font> 
    </body>
</html>

shop.html

<html>
    <head>
        <title>Kishore patties</title>
    </head>
    <body bgcolor="#6A7337" align="center">
        <h1>Ulhasnagar-2</h1>
        <h3>Kishore patties wala</h3>
        <hr>
        <font size="5">
            The history of Kishore Patties in Ulhasnagar dates back over 40 years, making it a staple in the local food scene. The stall has been a source of satisfaction for food enthusiasts with its delicious offerings, including Chole and potato patties, and Gulab Jamun. The stall's tradition and popularity have made it a must-visit for anyone looking to indulge in the best street food in Ulhasnagar.
        </font> 
    </body>
</html>

```

## OUTPUT

![alt text](<Screenshot (109).png>)
![alt text](<Screenshot (110).png>)
![alt text](<Screenshot (111).png>)
![alt text](<Screenshot (112).png>)
![alt text](<Screenshot (113).png>)
![alt text](<Screenshot (114).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
