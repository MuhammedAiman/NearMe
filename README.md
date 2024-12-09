# Ex04 Places Around Me
## Date: 

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
    <title>My city</title>
   </head>
   <body>
    <h1 align="center">
        <font color="red"><b>KODAIKANAL</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Muhammed Aiman S (24901053)</b></font>
    </h3>
    <center>
    <img src="c:\Users\admin\Pictures\Screenshots\Screenshot (24).png" usemap="#MyCity" height="610" width="1450">
    <map name="MyCity">
        <area shape="circle" coords="820,360,170," href="home.html" title="My Home">
        <area shape="circle" coords="620,150,45" href="cave.html" title="GUNA CAVE">
        <area shape="circle" coords="850,300,80" href="park.html" title="Bryant park">
        <area shape="circle" coords="850,350,150" href="observatory.html" title="Observatory of astronomical research">
        <area shape="circle" coords= href="lake.html" title="Man made Lake">
    </map>
</center>
   </body>
</html>

```

cave.html
```
<html>
    <head>
        <title>KODAIKANAL</title>
        </head>
        <body bgcolor="grey">
        <h1 align="center">
        <font color="brown"><b>GUNA CAVE</b></font>
        </h1>
        <h3 align="center">
        <font><b>My Home Town</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">
            Guna Caves, once known as Devil's Kitchen, are a series of deep, narrow crevices shrouded in mystery. 
            Located amidst the lush greenery and towering Pillar Rocks, these caves gained fame after being featured in the iconic Tamil film "Guna." 
            While the caves are not accessible for entry due to safety concerns, visitors can marvel at their imposing structure from a safe distance. 
            The surrounding area, with its dense shola forests and cool mountain breeze, offers a serene and captivating atmosphere.
            Recently the movie "MANJUMMEL BOYS" was filmed there and "Kanmani anbodu kathalan" song was once again famous.
            It then attracted a lot of tourists.
        </font>
        </p>
    </body>
</html>

```
home.html

```
<html>
    <head>
        <title>My Home Town</title>
        </head>
        <body bgcolor="lightgreen">
        <h1 align="center">
        <font color="maroon"><b>KODAIKANAL</b></font>
        </h1>
        <h3 align="center">
        <font color="red"><b>My Home Town</b></font>
        </h3>
        <hr size="3" color="purple">
        <p align="justify">
        <font face="Georgia" size="5">
            Kodaikanal, often called the "Princess of Hill Stations," is a breathtaking hill station nestled amidst the Palani Hills of Tamil Nadu, India.
            Its cool, misty climate, lush green valleys, and cascading waterfalls make it a perfect escape from the scorching plains.
            The star-shaped Kodaikanal Lake, surrounded by rolling hills, offers serene boating experiences.
            Trekkers can explore the misty trails leading to Dolphin's Nose, a unique rock formation offering panoramic views.
            Bryant Park, with its vibrant flowerbeds and diverse flora, is a haven for nature lovers.
            The town's colonial-era architecture, including the historic Bryant's Park and the serene Lutheran Church, adds to its charm.
        </font>
        </p>
    </body>
</html>

```
lake.html
```
<html>
    <head>
        <title>KODAIKANAL</title>
        </head>
        <body bgcolor="pink">
        <h1 align="center">
        <font color="blue"><b>LAKE</b></font>
        </h1>
        <h3 align="center">
        <font><b>My Home Town</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">
            The star-shaped Kodaikanal Lake, nestled amidst the verdant hills, is the heart of Kodaikanal. 
            This man-made marvel, created in 1863, offers a serene boating experience on its tranquil waters. 
            Surrounded by lush greenery, it's a popular spot for picnics, leisurely walks, and capturing stunning photographs. 
            The lake's picturesque beauty, coupled with the cool, misty climate, makes it an idyllic retreat for nature lovers and those seeking tranquility.
        </font>
        </p>
    </body>
</html>

```
observatory.html
```
<html>
    <head>
        <title>KODAIKANAL</title>
        </head>
        <body bgcolor="beige">
        <h1 align="center">
        <font color=""><b>OBSERVATORY</b></font>
        </h1>
        <h3 align="center">
        <font color="lime"><b>India's astronomical institution</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">
            The Kodaikanal Solar Observatory, perched atop the Palani Hills, is a renowned astronomical institution in India.
            Established in 1899, it boasts a rich history of solar research.
            This observatory has made significant contributions to our understanding of the sun,
            including the discovery of the Evershed effect.
            With its pristine skies and advanced telescopes, it continues to be a vital hub for solar studies,
            providing valuable insights into the sun's behavior and its impact on Earth's climate and space weather.
        </font>
        </p>
    </body>
</html>

```
park.html
```
<html>
    <head>
        <title>KODAIKANAL</title>
        </head>
        <body bgcolor="violet">
        <h1 align="center">
        <font color="OLIVE"><b>BRYANT PARK</b></font>
        </h1>
        <h3 align="center">
        <font color="GREEN"><b>My Home Town</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">
            Bryant Park, a sprawling 20-acre botanical garden, is a jewel in Kodaikanal's crown.
            Established in 1908 by H.D. Bryant, this park boasts a diverse collection of over 325 species of trees, shrubs, and cacti. 
            Its vibrant flowerbeds, especially during the annual summer flower show, are a sight to behold. 
            The park's serene atmosphere, dotted with benches and walking paths, offers a tranquil escape. 
            Beyond its aesthetic appeal,Bryant Park also serves as an educational center, showcasing various horticultural techniques
            and promoting environmental awareness.
        </font>
        </p>
    </body>
</html>

```


## OUTPUT

![alt text](<Screenshot (23).png>)

![alt text](<Screenshot (25).png>)

![alt text](<Screenshot (26).png>)

![alt text](<Screenshot (27).png>)

![alt text](<Screenshot (28).png>)

![alt text](<Screenshot (29).png>)

![alt text](<Screenshot (30).png>)




## RESULT
The program for implementing image maps using HTML is executed successfully.
