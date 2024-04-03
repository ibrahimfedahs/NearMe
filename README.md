# Ex04 Places Around Me
## Date: 23:03:2024

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
<head>
<title>MY CITY</title>
</head>
<body>
<h1 align="center">
<font color="black"><b>Nagercoil</b></font>
</h1>
<h3 align="center">
<font color="green"><b>IBRAHIM FEDAH.S(212223240056)</b></font>
</h3>
<center>
<img src="map.jpg" usemap="#image-map">

<map name="image-map">
    <area target="_self" alt="KFC" title="KFC" href="KFC.html" coords="657,687,483,572" shape="rect">
    <area target="_self" alt="sri gowri shankar" title="Government Hospital" href="hospital.html" coords="464,142,642,231" shape="rect">
    <area target="_self" alt="parish hall-CSI" title="parish hall-CSI" href="hall.html" coords="1154,644,69" shape="circle">
    <area target="_self" alt="RAJAS MALL" title="RAJAS MALL" href="MALL.html" coords="723,299,840,380" shape="rect">
    <area target="_self" alt="Poorvika Mobiles nagercoil" title="Poorvika Mobiles nagercoil" href="mobiles.html" coords="509,322,661,430" shape="rect">
</map>
</center>
</body>
</html>

kfc.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="silver"><b>nagercoil</b></font>
</h1>
<h3 align="center">
<font color="red"><b>KFC</b></font>
</h3>
<hr size="3" color="green">
<p align="justify">
<font face="Georgia" size="6">
  It is located in nagercoil,kanniyakumari district. At thiruvananthaouram Road Near collector Office.
   Opposite to indian oil.
   </font>
</p>
</body>
</html>

shankar.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="blue">
<h1 align="center">
<font color="white"><b>nagercoil</b></font>
</h1>
<h3 align="center">
<font color="pink"><b>sri gowri shankar</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="6">
It is located near muthu neuro & trauma canter,chunkandai. 
It is popular hotel
</font>
</p>
</body>
</html>

hall.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="brown"><b>kanniyakumari</b></font>
</h1>
<h3 align="center">
<font color="yellow"><b>Parish Hall-CSI</b></font>
</h3>
<hr size="4" color="black">
<p align="justify">
<font face="Georgia" size="6">
    Parish Hall is located in nesamony nager.
   It is located near to the Hotel Ramraj Regency
</font>
</p>
</body>
</html>

mall.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="white"><b>Nagercoil</b></font>
</h1>
<h3 align="center">
<font color="pink"><b>Rajas Mall</b></font>
</h3>
<hr size="4" color="white">
<p align="justify">
<font face="Georgia" size="6">
    the Rajas mall is located near to london mens wear
    It is located at chetikulam,kottar,Nagercoil,kanniyakumari District
</font>
</p>
</body>
</html>

mobiles.html

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="blue"><b>kanniyakumari</b></font>
</h1>
<h3 align="center">
<font color="grey"><b>Poorvika mobiles Nagercoil</b></font>
</h3>
<hr size="3" color="pink">
<p align="justify">
<font face="Georgia" size="6">
    poorvika mobiles Nagercoil is opposite to clock tower.
    located near to the indian oil petrol,Nagercoil,kanniyakumari district.
    
    </font>
</p>
</body>
</html>

```

## OUTPUT
![alt text](<Screenshot (3).png>)
![alt text](<Screenshot (5).png>)
![alt text](<Screenshot (4).png>)
![alt text](<Screenshot (6).png>)
![alt text](<Screenshot (7).png>)
![alt text](<Screenshot (8).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
