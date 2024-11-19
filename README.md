# Ex04 Places Around Me
## Date: 19.12.2024

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
map.html

<html>
    <head align="center"></head>
    <body>
        <h1 align="center"><font color="red"><b>Vellore</b></font></h1>
        <h3 align="center"><font color="cyon">Ameen Basha A (24900027)</font></h3>
        <center>
            <img src="map.png" usemap="#MyCity" height="610" width="1450">

            <map name="MyCity">
                <area target="_blank" alt="vellore" title="vellore" href="vellore.html" coords="801,298,715,262" shape="rect">
                <area target="_blank" alt="palamathi hills" title="palamathi hills" href="palamathi_hills.html" coords="1002,640,799,469" shape="rect">
                <area target="_blank" alt="palamathi temple" title="palamathi temple" href="palamathi_temple.html" coords="649,544,699,369" shape="rect">
                <area target="_blank" alt="Vellore airport" title="Vellore airport" href="airport.html" coords="67,266,165,307" shape="rect">
                <area target="_blank" alt="fort" title="fort" href="fort.html" coords="708,226,893,249" shape="rect">
            </map>
        </map>
        </center>
    </body>
</html>

vellore.html
<html>
    <body bgcolor="red">
        <font size="50">
            <h1 align="center" size="100%"><b>vellore </b></h1>
            <ul>
                <li>Vellore (English: VAY-loor), also natively spelt as Velur,[note 1] is a sprawling city and
                     the administrative headquarters of Vellore district in the Indian state of Tamil Nadu</li>
                     <li>
                        It is located on the banks of the Palar River in the northeastern part of Tamil Nadu and 
                        is separated into four zones that are further subdivided into 60 wards, <br>covering an area of 76.09  km2 
                        and housing a population of 315128 as reported by the 2011 census.[4] It is located about 137.20 kilometres
                     </li>
                     <li>

                      . Vellore is located on the Mumbai–Chennai arm of the Golden Quadrilateral
                      . Vellore is governed under a mayor and the Vellore Municipal Corporation.
                     </li>
                     It is a part of both the Lok Sabha and state assembly constituencies of Vellore. 
            </ul>
        </font>
    </body>
</html>


palamathi_temple.html

<html>
    <body bgcolor="yellow">
        <h1 align="center" ><font size="100">The Palamathi Temple</font> </h1>
        <font size="100">
            <ul>
                <li>The Palamathi Temple (also Balamathi, Balamathi Hills) are an extension of the Eastern Ghats spread across southeastern parts of Vellore City in Tamil Nadu. </li>
                    <li>It is the one of the most popular temple located in the palamathin hills </li>
                     <li>The area is a thriving hotspot for various birds and various flora. The hill top has a famous Hindu temple (Bala Murugan Kovil).
                     The place is also a developing tourist destination. </li>
            </ul>
        </font><
    </body>
</html>

palamathi_hills.html

<html>
    <body bgcolor="green">
            <font  size="50" align="center"><h1 align="center">The Palamathi Hills </h1></font>
        <font size="100"  >
            <ul>
                <li>The Palamathi Hills (also Balamathi, Balamathi Hills) are an extension of ,<br>the Eastern Ghats spread across southeastern parts of Vellore City in Tamil Nadu.
                     The Palamathi Hill range, the nearby Palamathi Reserve Forest, and the Otteri lake are collectively referred to as Palamathi Hills. </li>
                     <li>  The area is a thriving hotspot for various birds and various flora.</li>
                     <li> The hill top has a famous Hindu temple (Bala Murugan Kovil). </li>
                     The place is also a developing tourist destination. </li>
            </ul>
        </font>
    </body>
</html>

airport.html

<html>
    <body bgcolor="cyan">
        <h1 align="center"  ><font size="100">Vellore Airport</font></h1>
        <font size="100">
            <ul>
                <li>n July 2006, it was re-activated in as a part of Airports Authority of India idle airports activation programme to facilitate regular flying by trainee pilots of the Madras Flying Club whose operations were restricted <br>
                     with the increase in scheduled aircraft movement at Chennai Airport.</li>
                     <li> The Madurai airport flies internationally to 3 main destinations <br>
                        .Which included the Dubai airport,Singapore Changi AirPort and the Colombo bandaranaike airport.[1][2] The club stopped its training activities in March 2011.[3]</li>
            </ul>
        </font>
    </body>
</html>

fort.html

<html>
    <body bgcolor="pink">
        <h1 align="center"  ><font size="100">Vellore Fort</font></h1>
        <font size="100">
            <ul>
                <li>
                    Vellore Fort is a large 16th-century fort situated in heart of teh Vellore city, <br> in the state of Tamil Nadu, India built by the Emperors of Vijayanagara.
                </li>
                <li> Teh fort was at one time teh imperial capital of teh Aravidu Dynasty of teh Vijayanagara Empire. <br> The fort is non for its grand ramparts, wide moat and robust masonry.</li>
            </ul>
        </font>
    </body>
</html>
```

## OUTPUT
![alt text](<map (2).png>)
![alt text](<Screenshot (35).png>)
![alt text](<Screenshot (36).png>)
![alt text](<Screenshot (37).png>)
![alt text](<Screenshot (38).png>)
![alt text](<Screenshot (39).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
