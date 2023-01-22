# Places Around Me
# Aim:
To develop a website to display details about the places around my house.

# Design Steps:
# Step 1:

Clone the git repository into Theia IDE.
# Step 2:

Create a new Django project.
# Step 3:

Write the needed HTML code.
# Step 4:

Run the Django server and execute the HTML files

# Code:
1. map.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <title> TIRUNELVELI </title>
</head>
<h1 align="left">
<font color="red"><b>TIRUNELVELI</b></font>
</h1>
<body style="background-color: pink;">
    <img src="/static/images/map.png" width="1920" height="907" alt="nativemap" usemap="#nativemap">
<MAP name="nativemap">
    <area shape="RECT" coords="161,226,317,366" alt="bank" title="bank" href="/bank/">
    <area shape="RECT" coords="1114,244,1232,304" alt="hotel" title="hotel" href="/hotel/">
    <area shape="RECT" coords="1104,789,1285,898" alt="kna" title="kna" href="/kna/">
    <area shape="RECT" coords="352,242,556,374" alt="park" title="park" href="/park/">
    <area shape="RECT" coords="1352,106,1692,346" alt="rto" title="rto" href="/rto/">
</map>
</body>
</html>
```
2. bank.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>BANK</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="black"><b>TIRUNELVELI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>STATE BANK OF INDIA</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
<b>
<ul>
<li>State Bank of India branch is located here.</li>
<li>It is one of the oldest chruch in cuddalore.</li>
<li>It has a ATM facility.</li>
<li>The people working in the bank are so kind.</li>
</ul>
</b>
</font>
</p>
</body>
</html>
```
3. hotel.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>VINTAGE KITCHEN</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>TIRUNELVELI</b></font>
</h1>
<h3 align="center">
<font color="black"><b>VINTAGE KITCHEN</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
<b>
<ul>
<li>The Vintage hotel is known for its ambiance.</li>
<li>It looks like a vintage.</li>
<li>The food items there also good.</li>
<li>It provides healthy and hygenic food.</li>
<li>The hotel is also cheap and money saving .</li>
</ul>
</b>
</font>
</p>
</body>
</html>
```
4. kna.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>kna</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>TIRUNELVELI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Kerala NEET Academy</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
<b>
<ul>
<li>Kerala NEET Academy is a famous coaching centre in Tirunelveli.</li>
<li>It is successfully running for almost 6 years </li>
<li>It also has hostel facility.</li>
<li>The faculties here are from kerela.</li>
</ul>
</b>
</font>
</p>
</body>
</html>
```
5.park.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Park</title>
</head>
<body bgcolor="light blue">
<h1 align="center">
<font color="red"><b>TIRUNELVELI</b></font>
</h1>
<h3 align="center">
<font color="darkblue"><b>Anna Nagar Park</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
<b>
<ul>
<li>Anna nagar park is a well known park in that area.</li>
<li>Many children and elders come to the park.</li>
<li>It also has Gym facility.</li>
<li>It has many trees and greeneries.</li>
<li>It has a good ambiance.</li>
</ul>
</b>
</font>
</p>
</body>
</html>
6.rto.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>RTO</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>TIRUNELVELI</b></font>
</h1>
<h3 align="center">
<font color="green"><b>RTO</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
<b>
<ul>
<li>The Regional Transport Office is the organisation of the government responsible for maintaining a database of drivers and a database of vehicles.</li>
<li>This RTO in Tirunelveli maintains all the vehicle data of the districts.</li>
<li>It enforce the provisions of the various acts of motor vehicles.</li>
<li>The RTO issues driving licences, organises collection of vehicle excise duty.</li>
</ul>
</b>
</font>
</p>
</body>
</html>
```
# Output:
MAP

![map (2)](https://user-images.githubusercontent.com/118707091/213926932-285b041f-e041-4134-819d-2f438bbdc009.png)

BANK
![bank](https://user-images.githubusercontent.com/118707091/213926610-c83eacf9-0781-40a4-86f4-2bf37564e216.png)
PARK
![park](https://user-images.githubusercontent.com/118707091/213926665-0fd439be-4008-4fcb-99ea-f181cb5e8ebf.png)
HOTEL
![hotel](https://user-images.githubusercontent.com/118707091/213926683-ece10ac6-266f-44a9-9c91-3e0175caa560.png)
RTO
![rto](https://user-images.githubusercontent.com/118707091/213926687-7ad0d479-1090-49aa-a8a0-eb1ec63d3534.png)
KNA
![kna](https://user-images.githubusercontent.com/118707091/213926748-5c26a625-9427-4759-881f-aecb7538606b.png)
![Screenshot (33)](https://user-images.githubusercontent.com/118707091/213927579-78f4a939-341b-48a9-9206-fd8565e7784f.png)


# Result:
Thus The Web Is Developed To Show The Details near me
