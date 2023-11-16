# Ex04 Places Around Me
# DATE: 15.10.2023
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
### index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NearMe</title>
</head>
<body>
   <img src="Map.png" usemap="#image-map">

    <map name="image-map">
        <area target="_blank" alt="SB Theatre" title="SB Theatre" href="theatre.html" coords="1435,565,1498,609" shape="rect">
        <area target="_blank" alt="ORR" title="ORR" href="orr.html" coords="125,396,296,463" shape="rect">
        <area target="_blank" alt="Temple" title="Temple" href="temple.html" coords="789,417,844,463" shape="rect">
        <area target="_blank" alt="Bus Stand" title="Bus Stand" href="busStand.html" coords="620,241,725,302" shape="rect">
        <area target="_blank" alt="D Mart" title="D Mart" href="dmart.html" coords="1579,523,1671,576" shape="rect">
    </map>
</body>
</html>
```
### dmart.html
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dmart</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>D MART CHENNAI</h1>
    <br>
    <hr color="Brown">
    <p>Avenue Supermarts Limited, d/b/a DMart, is an Indian retail corporation that operates a chain of hypermarkets in India. It was founded by Radhakishan Damani in 2002 when its first store was opened in Powai, Mumbai.As of June 2023, it has 330 stores across 14 states in India.

        The company has its headquarters in Mumbai. As of 31 March 2022, DMart had a total of 10,713 permanent employees and 58,597 employees hired on contractual basis</p>
</body>
</html>
```
### theatre.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SB cinemas</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>SB CINEMAS</h1>
    <br>
    <hr color="Brown">
    <p>SB Cinemas is the ultimate cinema destination equipped with 4k Projection, Dolby Atmos and extravaga. Sri Bhagavathi Theatre - Poonamallee is a popular theatre located at 2, Amman Koil Street, Kumananchavadi, Near Aksent English Academy, Poonamallee, West, Chennai. Sri Bhagavathi Theatre - Poonamallee has 1 screens. Movies now showing at Sri Bhagavathi Theatre - Poonamallee are NONE.</p>
</body>
</html>
```
### busstand.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ponamalee Bus Stand</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>POONAMALLEE BUS STAND</h1>
    <br>
    <hr color="Brown">
    <p>Located on Mount-Poonamallee Road, Poonamallee Bus Stand Chennai is a famous bus terminus. While serving hundreds of different routes every day, this bus stand is a major halting point for buses arriving from Tirupathi, Kanchipuram, Vellore, etc. Further, the bus stand shares close proximity with Alvadi Railway Station as it’s located only 10.4km away. On the other hand, the famous Chennai International Airport is only 21km far, and it takes around 45 to 50 minutes to reach there. The bus station’s road network is well-connected and maintained due to popular roads such as NH-48, Mount-Poonamallee Road, etc. Lastly, Poonamallee Bus Depot is well-surrounded by famous tourist attractions such as Sri Kamakshi Amman Temple, Varageaswari Temple, etc</p>
</body>
</html>
```
### temple.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vaitheeswaran Temple</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>VAITHEESWARAN TEMPLE</h1>
    <br>
    <hr color="Brown">
    <p>Vaitheeswaran Koil is a Hindu temple dedicated to the Shiva, located in the Indian state of Tamil Nadu. Shiva is worshipped as Vaidyanathar or Vaitheeswaran meaning the "God of healing" and it is believed that prayers to Vaitheeswaran can cure diseases. Vaitheeswaran is a Tamil derivative from vaidya (Doctor) and Ishvara (God/Master). The presiding deity is Sri vaidyanathan, facing towards West whereas East side is the common one. He is the God of Healing. When pronouncing in Tamil, it sounds like "vaideeswaran". It is one of the nine Navagraha (nine planets) temples and is associated with the planet Mars (Angaraka).</p>

</body>
</html>
```
### orr.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ORR</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>OUTER RING ROAD</h1>
    <br>
    <hr color="Brown">
    <p>The Outer Ring Road, officially State Highway 234 (SH 234),is a major transport corridor along the periphery of Chennai Metropolitan Area (CMA) by the Chennai Metropolitan Development Authority (CMDA). It is 62 km long connecting GST Road at Perungalathur, GST Road at Vandalur, NH 48 (GWT Road) at Nazarethpettai, NH 716 (CTH Road) at Pattabiram to NH 16 (GNT Road) at Vijayanaallur and to TPP road at Minjur. On 29 August 2010, the then Tamil Nadu Deputy Chief Minister M. K. Stalin laid the foundation for the first phase of the project from Vandalur to Nemilichery covering a distance of 30 kilometres (19 mi). The Chennai ORR generally covers Avadi North, West and South, Redhills, Minjur and Tambaram neighbourhoods. Chennai Outer ring road had a plan of Chennai metro rail CMRL which is going to build up at gap between two roads.</p>
</body>
</html>
```

## OUTPUT
![279336601-1cefcbe8-72ca-47f8-8884-e0d50500085e](https://github.com/kamalesh2509/NearMe/assets/120444689/2ab4aa98-9826-42f9-88af-985da833cca2)
![279336661-08e9a74d-95ae-475e-b97d-8f3dae700f03](https://github.com/kamalesh2509/NearMe/assets/120444689/dfb45555-d8a9-4f80-9c09-6249418f154b)
![279336712-2e6a4b2d-6351-413a-965a-eeb7125f3167](https://github.com/kamalesh2509/NearMe/assets/120444689/f58f7c14-9425-45d1-805e-cda20d9f5afe)
![279336752-22024211-c8ee-4f75-a8e1-e6a54c290726](https://github.com/kamalesh2509/NearMe/assets/120444689/e4dac111-4ae3-4fbe-8e3c-6e197d2b4762)
![279336821-f51e8c6c-e3e8-40c7-97aa-12ab61f5193f](https://github.com/kamalesh2509/NearMe/assets/120444689/efdc9de0-17c0-4a8a-a0f7-07e4f19960e7)
![279336882-0b3582eb-bd96-4436-9fea-128cd75bd32e](https://github.com/kamalesh2509/NearMe/assets/120444689/8746ffe3-ea27-4e4b-afcd-4c693ac7bbb8)
![279337120-33c77562-ac67-4cea-8c4f-26b9462b9907](https://github.com/kamalesh2509/NearMe/assets/120444689/6f708c8c-cf29-4eef-930c-f1860447ad8f)

## RESULT
The program for implementing image maps using HTML is executed successfully.
