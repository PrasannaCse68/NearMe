# Ex04 Places Around Me
## Date:31/03/2024 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using <map> tag name the map.

### STEP 4
Create clickable regions in the image using <area> tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
### kos.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MAP</title>
</head>
<center>
<body bgcolor="grey">
    <h1>SEVOOR-TOWNMAP</h1>
    <h2>PRASANNA G.R(212221040129)</h2>
    <img src="Screenshot 2024-03-21 141659.png" usemap="#image-map">

    <map name="image-map">
        <area target="" alt="Old Bus Stand" title="Old Bus Stand" href="bus.html" coords="740,274,591,226" shape="rect">
        <area target="" alt="Suriya Lake" title="Suriya Lake" href="lake.html" coords="637,379,686,413" shape="rect">
        <area target="" alt="Lakshmi Theatre" title="Lakshmi Theatre" href="theatre.html" coords="696,338,16" shape="circle">
        <area target="" alt="Home" title="Home" href="home.html" coords="462,377,4" shape="circle">
        <area target="" alt="GK Hospital" title="GK Hospital" href="clinic.html" coords="687,183,37" shape="circle">
    </map>
</body>
</center>
</html>

### theatre.html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>theatre</title>
</head>
<body bgcolor="cyan">
<center>
<h1>ARANI</h1>
<h2>LAKSHMI THEATRE</h2>
<hr>
</center>
<h3>1.Nestled in the heart of Arani, amidst the vibrant pulse of the tow
<h3>2.Lakshmi theatre is situated on a bustling street corner, its marqu
<h3>3.As you approach, the grand façade of the theater captivates with i
</body>
</html>


### clinic.html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>G K hospital</title>
</head>
<body bgcolor="chartreuse">
<center>
<h1>ARANI</h1>
<h2>G K HOSPITAL</h2>
<hr>
</center>
<h3>1.The G K Hospital is situated at the heart of the town, Town Genera
<h3>2.The hospital boasts a modern yet welcoming architectural design, w
<h3>3.Town General Hospital stands as a pillar of healthcare excellence
</body>
</html>

### lake.html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>lake</title>
</head>
<body bgcolor="coral">
<center>
<h1>ARANI</h1>
<h2>SURIYA LAKE</h2>
<hr>
</center>
<h3>1.Nestled within the heart of the town lies the serene and picturesq
<h3>2.Boating enthusiasts can indulge in leisurely rides across the lake
<h3>3.Adjacent to the Suriya Lake stands the iconic MC Theatre, a belove
</body>
</html>

### bus.html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Old Bus Stand</title>
</head>
<body bgcolor="violet">
<center>
<h1>ARANI</h1>
<h2>OLD BUS STAND</h2>
<hr>
</center>
<h3>1.The old bus stand located in arani is heart of the town arani and
<h3>2.Thera are two bus stands in Arani. So it is easier to the people o
<h3>3.It's a place where locals gather, vendors sell their goods, and t
</body>
</html>

### home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>home</title>
</head>
<body bgcolor="yellow">
<center>
<h1>ARANI</h1>
<h2> MY HOME</h2>
<hr>
</center>
<h3>1.My home is located at the area called saidapet ,pichandi nagar, wh
<h3>2.Nestled within the vibrant community of Arani, my home stands as a
</body>
</html>


## OUTPUT:

### kos.html
![Screenshot 2024-04-04 140136](https://github.com/PrasannaCse68/NearMe/assets/127935950/5dd37cc1-fa30-4e90-b761-eafcbd41b7ab)

### theatre.html

![Screenshot 2024-03-25 175903](https://github.com/PrasannaCse68/NearMe/assets/127935950/804a8c22-0f18-427e-ac3f-336734621f69)
### clinic.html
![Screenshot 2024-03-25 175915](https://github.com/PrasannaCse68/NearMe/assets/127935950/e7fd28a4-68d3-41f3-94b9-94ca1463a818)

### lake.html
![Screenshot 2024-03-25 175925](https://github.com/PrasannaCse68/NearMe/assets/127935950/0d6ffa32-6731-4892-a27f-e897cf0db40b)

### bus.html
![Screenshot 2024-03-25 175812](https://github.com/PrasannaCse68/NearMe/assets/127935950/61c869c9-2496-4316-b52f-f3846b936081)

### home.html
![Screenshot 2024-03-25 175940](https://github.com/PrasannaCse68/NearMe/assets/127935950/879a43cf-3a44-4083-843b-d7db6e2955ad)


## RESULT
The program for implementing image maps using HTML is executed successfully.
