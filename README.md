# Ex04 Places Around Me
## Date: 03-04-2024

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
## map.html

<html>
    <title>Mycity</title>
    <body bgcolor="white">
        <h1 align="center"><font color="black">RAJAPALAYAM</font></h1>
        <h3 align="center">
            <font color="red">KARTHIKEYAN M(212223110020)</font></h3>
        <center>
            <img src="map.png"  usemap="#MyCity" height="700" width="1450">
            <map name="MyCity">
                    <area shape="rect" coords="200,450,600,570" href="sasthafalls.html" title="Sastha kovil falls">     
                    <area shape="rect" coords="450,50,250,200" href="falls.html" title="ayyanar kovil falls">
                    <area shape="rect" coords="750,85,450,250" href="sanctuary.html" title="wildlife sanctuary">
                    <area shape="rect" coords="600,250,850,350" href="church.html" title="church">
                    <area shape="rect" coords="750,50,450,05" href="thopu.html" title="shenbaga thopu">
            </map>
        </center>

    </body>
</html>

## sasthafalls.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">RAJAPALAYAM</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">SASTHA KOVIL & FALLS</font>
    </h3>
    <body bgcolor="yellow" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Sastha Koil Falls, near Rajapalayam in Tamil Nadu, is a captivating waterfall named after the adjacent Sastha Koil temple. Nestled amidst lush forests and rolling hills, it offers a serene escape. Visitors can enjoy swimming and picnicking in its natural surroundings. Accessible via a short trek, the falls are especially alluring during the monsoon season when they are at their most majestic. It's a popular destination for locals and tourists seeking tranquility and a connection with nature in the beautiful landscapes of Tamil Nadu.
        </font>
        </p>
    </body>
</html>

## falls.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">RAJAPALAYAM</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">Ayyanaar Koil Falls</font>
    </h3>
    <body bgcolor="pink" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Ayyanaar Koil Falls, near Rajapalayam in Tamil Nadu, India, is a charming waterfall named after the nearby Ayyanaar Koil temple. Surrounded by lush greenery and fed by the waters of the Western Ghats, it provides a serene escape for visitors. Activities like swimming and picnicking are popular, especially during the monsoon season when the waterfall is at its most captivating. Accessible via a forest trek, it offers breathtaking views and a peaceful ambiance, making it a favored destination for nature lovers and tourists alike.
        </font>
        </p
    </body>
</html>

## thopu.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">RAJAPALAYAM</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="green" size="5.5">Shenbaga Thopu</font>
    </h3>
    <body bgcolor="orange" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Shenbaga Thopu is a scenic park located in Rajapalayam, Tamil Nadu, India. The name translates to "Grove of Shenbaga Trees," referring to the lush vegetation of the area, particularly the Shenbaga (Michelia champaca) trees that adorn the park. It is a popular recreational spot for locals and tourists alike, offering serene pathways for leisurely walks, shaded areas for picnics, and tranquil spots for relaxation amidst nature. The park's peaceful ambiance and verdant surroundings make it a favored destination for those seeking a break from the hustle and bustle of city life in Rajapalayam.
        </font>
        </p>
    </body>
</html>

## sanctuary.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">RAJAPALAYAM</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="orange" size="5.5">Grizzled Squirrel Wildlife Sanctuary</font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            This old temple is located amidst the Grizzled Squirrel Wildlife Sanctuary. Verdant green environments make up the surroundings of this location that are not only green but highly diverse as well with many different animals, birds, and plants. Keystone species of this wildlife sanctuary are the Grizzled Squirrels, other than the squirrels this location has a known population of leopards, elephants, tigers, flying squirrels, etc. A myriad of bird species reside in this park and this particular trail can be considered excellent for birding.
        </font>
        </p>
    </body>
</html>

## church.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">RAJAPALAYAM</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="orange" size="5.5">King of Kings Church</font>
    </h3>
    <body bgcolor="cyan" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            The "King of Kings" Church is a prominent Christian place of worship located in Rajapalayam, Tamil Nadu, India. The church holds significance for the local Christian community and stands as a symbol of faith and spirituality in the region. It serves as a gathering place for worship services, prayer meetings, and other religious events. With its distinctive architecture and spiritual atmosphere, the King of Kings Church attracts both local devotees and visitors seeking solace and inspiration.
        </font>
        </p>
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2024-04-03 212949.png>)
![alt text](<Screenshot 2024-04-03 213022.png>)
![alt text](<Screenshot 2024-04-03 213035.png>)
![alt text](<Screenshot 2024-04-03 213051.png>)
![alt text](<Screenshot 2024-04-03 213105.png>)
![alt text](<Screenshot 2024-04-03 213118.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
