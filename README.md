# Ex04 Places Around Me
## Date: 23-03-2024

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
map.html
```
<html>
    <head>
        <title>Madurai</title>
    </head>
    <body bgcolor="cyan">
        <h1> MADURAI CITY</h1>
        <h3>Name: VISWA PRAKAASH NJ </h3>
        <h3>Reg no:212223040246</h3>

        
        <img src="map.png.png" usemap="#image-map">

        <map name="image-map">
            <area target="" alt="MR Residency" title="MR Residency" href="1.html" coords="173,424,95" shape="circle">
            <area target="" alt="Hotel royal court" title="Hotel royal court" href="2.html" coords="594,570,66" shape="circle">
            <area target="" alt="Meenakshi Temple" title="Meenakshi Temple" href="3.html" coords="850,615,88" shape="circle">
            <area target="" alt="Raj's Arts and Crafts" title="Raj's Arts and Crafts" href="4.html" coords="1005,495,74" shape="circle">
            <area target="" alt="Gandhi Mueseum" title="Gandhi Mueseum" href="5.html" coords="1502,265,96" shape="circle">
        </map>

    </body>
</html>
```
1.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="gold">
        <h1 align="center">
        <font color="green"><b>MADURAI CITY</b></font>
        </h1>
        <h3 align="center">
        <font color="yellow"><b>MR Residency</b></font>
        </h3>
        <hr size="3" color="pink">
        <p align="justify">
        <font face="Georgia" size="5">
            he small hotel offers 24 hour front desk, room service, and newspaper, to make your visit even more pleasant. The property also features an on-site restaurant.
        </font>
        </p>
    </body>
</html>
```
2.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
        <font color="gold"><b>MADURAI CITY</b></font>
        </h1>
        <h3 align="center">
        <font color="pink"><b>Hotel royal cour</b></font>
        </h3>
        <hr size="3" color="yellow">
        <p align="justify">
        <font face="Georgia" size="5">
            As one of the best hotels in Madurai, the Royal Court sets a new standard for luxury and comfort in the city. We offer unrivaled levels of comfort and ...
        </font>
        </p>
    </body>
</html>
```
3.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
        <font color="gold"><b>MADURAI CITY</b></font>
        </h1>
        <h3 align="center">
        <font color="green"><b>Meenakshi Temple</b></font>
        </h3>
        <hr size="3" color="blue">
        <p align="justify">
        <font face="Georgia" size="5">
            Arulmigu Meenakshi Sundareswarar Temple a.k.a Arulmigu Meenakshi Amman Thirukkovil is a historic Hindu temple located on the southern bank of the Vaigai River in the temple city of Madurai, Tamil Nadu, India. It is dedicated to the goddess Meenakshi, a form of Shakti, and her consort, Sundareshwarar, a form of Shiva.
        </font>
        </p>
    </body>
</html>
```
4.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="lightblue">
        <h1 align="center">
        <font color="cyan"><b>MADURAI CITY</b></font>
        </h1>
        <h3 align="center">
        <font color="pink"><b>Raj's Arts and Craft</b></font>
        </h3>
        <hr size="3" color="green">
        <p align="justify">
        <font face="Georgia" size="5">
            Tanjore Painting original gold foil with high-quality available book now. Tanjore painting gold foil Arabic gum chalk many more.
        </font>
        </p>
    </body>
</html>
```
5.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">
        <font color="maroon"><b>MADURAI CITY</b></font>
        </h1>
        <h3 align="center">
        <font color="babypink"><b>Gandhi Mueseum</b></font>
        </h3>
        <hr size="3" color="yellow">
        <p align="justify">
        <font face="Georgia" size="5">
            The building that houses the Gandhi Memorial Museum, Madurai is the historic Tamukkam Palace belonging to Rani Mangammal of Nayak Dynasty built about 1670 ...

           
        </font>
        </p>
    </body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2024-03-26 151605.png>) ![alt text](<Screenshot 2024-03-26 151634.png>) ![alt text](<Screenshot 2024-03-26 151615.png>) ![alt text](<Screenshot 2024-03-26 151555.png>) ![alt text](<Screenshot 2024-03-26 151541.png>) ![alt text](<Screenshot 2024-03-26 151457.png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
