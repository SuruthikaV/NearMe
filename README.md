# Ex03 Places Around Me
## Date:26-11-2025 

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
        <title>map</title>
    </head>
    <body>
        <h2 align="center">
            <font color="red"><b>Vellore-Ambur</b></font>
        </h2>
        
        <h3 align="center">
            <font color="blue"><b>Suruthika(25000884)</b></font>
        </h3>
        <img src="map.png" usemap="#image-map">

        <map name="image-map">
            <area target="" alt="Titan World" title="Titan World" href="titan.html" coords="639,536,763,568" shape="rect">
            <area target="" alt="Government Hospital Ambur" title="Government Hospital Ambur" href="govt.html" coords="881,314,76" shape="circle">
            <area target="" alt="Ziya Shoes" title="Ziya Shoes" href="shoe.html" coords="1307,228,1221,270,1316,314,1395,270" shape="poly">
            <area target="" alt="Ambur Railway Station" title="Ambur Railway Station" href="station.html" coords="1345,528,52" shape="circle">
            <area target="" alt="Raj Kamal Theatre" title="Raj Kamal Theatre" href="theatre.html" coords="1173,446,1043,524,1268,525" shape="poly">
        </map> 
    </body>
</html>

theatre.html

<html>
    <head>
        <title>theatre</title>
        <body bgcolor="red">
            <h2 align="center">Ambur</h2>
            
            <h3 align="center">Raj Kamal Theatre</h3>
            <hr>
            <p>Raj Kamal Cinemas is a well-known movie theatre on MC Road (near the Ambur bus-stand / Flower Bazar area, pin-code 635802), offering a modern cinema experience with air-conditioned halls, digital projection (4K / 2K) and Dolby-Atmos / DTS-enabled sound. The theatre features comfortable seating, good screen & sound quality, and ample parking and making it a popular choice for locals and visitors looking for a nice outing. Raj Kamal also provides online ticket booking and shows a variety of films, making movie-going easy and convenient in Ambur.


            </p>
        </body>
    </head>
</html>

station.html

<html>
    <head>
        <title>Station</title>
    </head>
    <body bgcolor="orange">
        <h2 align="center">Ambur</h2>
        <h3 align="center">Ambur Railway Station</h3>
        <hr>
        <p>
            Ambur Railway Station (station code: AB) is a key stop on the Chennai to Bengaluru rail route and serves as the main transportation hub for the town of Ambur. The station has three platforms, electrified tracks, and essential passenger facilities such as waiting areas and ticket counters. It handles regular express and passenger trains, making travel convenient for residents and visitors heading to major cities.
        </p>
    </body>
</html>

shoe.html

<html>
    <head>
        <title>shoes</title>
    
    </head>
    <body bgcolor="cyan">
        <h2 align="center">Ambur</h2>
        <h3 align="center">Ziya Shoes</h3>
        <hr>
        <p>
            Ziya Shoes is a popular footwear store located in the Flower Bazar area of Ambur.
            Known for its wide range of shoes for men and women, the shop offers stylish and affordable options suitable for everyday wear. 
            Its convenient central location and customer-friendly service make it a well-known choice among shoppers looking for quality footwear in Ambur.
        </p>
    </body>
</html>

govt.html

<html>
    <head>
        <title>hospital</title>
    </head>
    <body bgcolor="blue">
        <h2 align="center">Ambur</h2>
        <h3 align="center">Government Hospital Ambur</h3>
        <hr>
        <p>Government Hospital in Ambur is a major public healthcare center located on Nethaji Road, providing essential medical services to the local community.
         With around 375 beds and facilities such as a blood bank, emergency care, and general medical services, it serves as an important lifeline for residents in and around Ambur.
         The hospital is known for offering treatment at affordable costs and operates under the Tamil Nadu Health Department to ensure accessible healthcare for all.

        </p>
    </body>
</html>

titan.html

<html>
    <head>
        <title>titan</title>
        <body bgcolor="pink">
            <h2 align="center">Ambur</h2>
            
            <h3 align="center">TITAN WORLD</h3>
            <hr>
            <p>This is the World of Titan/ Titan World outlet located in Ambur
        
                They sell a variety of watches (men, women, kids, etc.), possibly including quartz, analog, and fashion-style watches under the Titan umbrella and related sub-brands.


            </p>
        </body>
    </head>
</html>

```

## OUTPUT
![alt text](<Screenshot (21).png>)

![alt text](<Screenshot 2025-11-26 220748.png>)

![alt text](<Screenshot 2025-11-26 220701.png>)

![alt text](<Screenshot 2025-11-26 220729.png>)

![alt text](<Screenshot 2025-11-26 220644.png>)

![alt text](<Screenshot 2025-11-26 220630.png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
