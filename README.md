# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

##Step 1:
Clone the github repository into THEIA IDA.

##Step 2:
Create a new django project.

##Step 3:
Write the needed HTML code.

##Step 4:
Run the django server and execute the HTML files.

## Code:
```
map.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>My City - KALLAKURICHI</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>MY CITY - KALLAKURICHI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>JAYABHARATHI S(212222100013)</b></font>
</h3>
<center>
<img src="/static/images/my city1.png"usemap="#MyCity - KALLAKURICHI" height="420" width="1100">
<map name="My City">
<area shape="circle" coords="190,50,20" href="/static/html/cse.html" title="AKT Academy Matic Higher Secondary School">
<area shape="rectangle" coords="230,30,260,60" href="/static/html/admin.html" title="ANB Marraige Mahal">
<area shape="circle" coords="400,350,50" href="/static/html/ece.html" title="Maha Bharathi International CBSE School">
<area shape="circle" coords="400,200,75" href="/static/html/simats.html" title="Karikalan Hotel A/C">
<area shape="rectangle" coords="490,150,870,320" href="/static/html/eee.html" title="Oxaliss International CBSE School">
</map>
</center>
</body>
</html>

akt.html

<!DOCTYPE html>
<head>
<h1 align="center">
<font color="red"><b>KALLAKURICHI</b></font>
</h1>

<title>AKT Academy Matic Higher Secondary School</title>
</head>
<body bgcolor="cyan">
<h3 align="center">
<font color="blue"><b>AKT Academy Matic Higher Secondary School</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Segoe Script" size="5">
<b>
A.K.T. ACADEMY is situated on a sprawling campus of over 40 acres (160,000 m2), 2 km away from Kallakurichi town on Salem to Chennai Highways Road (around 72 km from Villupuram. An auditorium accommodation of 500 seats with D.T.S. digital sound effect,
A Vinayagar temple is around the campus,
Boys and Girls separate hostel facilities,
Well-equipped rest hall with cushion bed and A/C for Pre.K.G, L.K.G and U.K.G.
A canteen with hygienic foods, snacks and fruit drinks.
Separate Chemistry, Physics ,Biology , Computer Science and EMR labs are available with all necessary amenities.
Medical facilities are available in the campus to help in times of emergencies.
</b>
</font>
</p>
</body>
<hr size="3" color="red">
</html>

anb.html

<!DOCTYPE html>
<head>
<title>ANB Marraige Mahal</title>
</head>
<h1 align="center">
<font color="red"><b>KALLAKURICHI</b></font>
</h1>
<body bgcolor="lavender">
<h3 align="center">
<font color="blue"><b>ANB Marraige Mahal</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Segoe Script" size="5">
<b>
ANB Marriage Hall in Ammaiyagaram is an air-conditioned hall with a seating capacity of 800 and a floating capacity of 1200. The Dining capacity of ANB Marriage Hall is 320. The Function Hall is on the Ground floor. A parking facility is available for 50 cars and 100 bikes. There is generator backup for the event to function smoothly during a power cut. The Kalyana Mandapams provides air-conditioned rooms with a locker facility for the guests. Both the Dining hall and Function hall are on the same floor which is an added advantage. 
</font>
</p>
</body>
<hr size="3" color="red">
</html>

karikalan.html

<!DOCTYPE html>
KARIKALAN HOTEL
<head>
<title>Karikalan Hotel A/C</title>
</head>
<h1 align="center">
<font color="red"><b>KALLAKURICHI</b></font>
</h1>
<body bgcolor="lime">
<h3 align="center">
<font color="blue"><b>Karikalan Hotel A/C</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Segoe Script" size="5">
<b>
At this restaurant, the recipe of nicely cooked biryani is a story that ends up with a really good meal. The pleasant staff works hard, stays positive and makes this place wonderful. Nice service is a strong point that plays a great role for the success of Karikalan A/C Family Restaurant (Veg & Non Veg). 
</b>
</font>
</p>
</body>
<hr size="3" color="red">
</html>

mahabharathi.html

<!DOCTYPE html>
<head>
<title>Maha Bharathi International CBSE School</title>
</head>
<h1 align="center">
<font color="red"><b>KALLAKURICHI</b></font>
</h1>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b></b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Maha Bharathi International CBSE School</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Segoe Script" size="5">
<b>
Mahabharathi International School also known as Mahabharathi International School. The school was established in 2012. Mahabharathi International School is a Co-Ed school affiliated to Central Board of Secondary Education (CBSE) . It is managed by Mahasakthi Educational Trust.
</font>
</p>
</body>
<hr size="3" color="red">
</html>

oxaliss.html

<!DOCTYPE html>
<head>
<title>Oxaliss International CBSE School</title>
</head>
<h1 align="center">
<font color="red"><b>KALLAKURICHI</b></font>
</h1>
<body bgcolor="orange">
<h3 align="center">
<font color="blue">Oxaliss International CBSE School</font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Segoe Script" size="5">
<b>
Oxaliss International School is run by the reputable management of “Kalap Virucha Trust of Education” started at 2011. It is a co-educational school,offering a choice between Residential and Day scholastic programmes. Oxaliss Education strives towards holistic programme that help maximize the both individual and social welfare. The School aims to provide a broader and bolder education of body, mind, spirit. Such an eaducation produces: Self-Directed Learner,Quality Producers,Effective Communicators,Collaborative Workers,Good Thinker and Community Contributor. Such an integrated approach ensures every Child’s development with confidence.
</b>
<hr size="3" color="red">
</font>
</p>
</body>
</html>

```

## Output:

![out1](https://user-images.githubusercontent.com/120367796/233186842-3de2826b-10b8-451d-88f0-113da559dc06.png)

![out2](https://user-images.githubusercontent.com/120367796/233187057-b543df8f-1b20-4038-b8a8-bd20b6d777f2.png)

![out3](https://user-images.githubusercontent.com/120367796/233187081-3f6206f5-1e2e-45b7-a305-93fd38868f98.png)

![out4](https://user-images.githubusercontent.com/120367796/233187099-993a81ce-4998-41c1-bf47-5961f53b1074.png)

![out5](https://user-images.githubusercontent.com/120367796/233187143-c8691bfb-3878-4ec2-9fe1-d1c49a8c8517.png)

![out6](https://user-images.githubusercontent.com/120367796/233187190-126fd03b-ec24-4941-a6cc-00db9f169471.png)


## HTML VALIDATOR

![out7](https://user-images.githubusercontent.com/120367796/233187308-35c1f36a-8270-4a0b-82d9-f0bf14b18a33.png)


## Result:
The program for implemented image map is executed succussfully.
