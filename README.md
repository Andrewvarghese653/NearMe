# Ex04 Places Around Me
## Date: 
27/09/2023

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
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>My Home Town</title>
  </head>
  <body>
    <h1 align="center">
      <font color="black"><b>ANDREW VARGHESE VS</b></font>
    </h1>
    <h3 align="center">
      <font color="green"><b>ANDREW VARGHESE VS (212222103001)</b></font>
    </h3>
    <center>
      <img src="mapp.png" usemap="#My Home" height="100%" width="100%" />
      <map name="My Home">
    <area target="_blank" alt="Hamedhiya Super market" title="Hamedhiya Super market" href="HamedhiyaSupermarket.html" coords="1221,1162,1268,1195" shape="rect">
    <area target="_blank" alt="Fresh seedless tamerind" title="Fresh seedless tamerind" href="Freshseedlesstamerind.html" coords="1070,1279,1101,1319" shape="rect">
    <area target="_blank" alt="Veetu Sapadu" title="Veetu Sapadu" href="Veetusapadu.html" coords="1000,1214,956,1189" shape="rect">
    <area target="_blank" alt="MAG Engineering " title="MAG Engineering " href="MAGEngingeering" coords="2645,776,2682,810" shape="rect">
    <area target="_blank" alt="Snowman logistics" title="Snowman logistics" href="SnowmanLogistics.html" coords="1714,256,1751,293" shape="rect">
</map>
    </center>
  </body>
</html>

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>HOME</title>
  </head>
  <body bgcolor="blue">
    <h1 align="center">
      <font color="red"><b>HOME</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>RUS PIZZA</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
        When it comes to buying a home, it’s a challenging task to find a place that is both smartly sized in a secure location and has major amenities in close proximity. What’s even more challenging, is to find such a place that snugly fits your budget. Keeping in mind our budget conscious customers, who demand value for money, we present to you Le Chalet - Smart Choice Homes. It offers a wide variety of delicious South Indian dishes, ranging from traditional to modern. The restaurant has a cozy and inviting atmosphere, with comfortable seating and a friendly staff. The menu features a variety of vegetarian and non-vegetarian dishes, as well as a selection of desserts. The restaurant also offers a variety of beverages, including tea, coffee, and soft drinks. The restaurant is open for lunch and dinner, and also offers catering services for special occasions. </font>
    </p>
  </body>
</html>

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Hameedhya Super Market</title>
  </head>
  <body bgcolor="blue">
    <h1 align="center">
      <font color="red"><b>Hameedhya Super Market</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>RUS PIZZA</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
        The supermarket typically has places for fresh meat, fresh produce, dairy, deli items, baked goods, and similar foodstuffs. Shelf space is also reserved for canned and packaged goods and for various non-food items such as kitchenware, household cleaners, pharmacy products and pet supplies. Some supermarkets also sell other household products that are consumed regularly, such as alcohol (where permitted), medicine, and clothing, and some sell a much wider range of non-food products: DVDs, sporting equipment, board games, and seasonal items (e.g., Christmas wrapping paper, Easter eggs, school uniforms, Valentine's themed gifts, Mother's Day gifts, Father's Day gifts and Halloween).etc.</font>
    </p>
  </body>
</html>

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Fresh seedless tamerind</title>
  </head>
  <body bgcolor="blue">
    <h1 align="center">
      <font color="red"><b>Fresh seedless tamerind</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>RUS PIZZA</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
        The tamarind tree produces brown, pod-like fruits that contain a sweet, tangy pulp, which is used in cuisines around the world. The pulp is also used in traditional medicine and as a metal polish. The tree's wood can be used for woodworking and tamarind seed oil can be extracted from the seeds. Tamarind's tender young leaves are used in South Indian and Filipino cuisine.[7][8] Because tamarind has multiple uses, it is cultivated around the world in tropical and subtropical zones.</font>
    </p>
  </body>
</html>


<!DOCTYPE html>
<html lang="en">
  <head>
    <title>VEEDU SAPADU</title>
  </head>
  <body bgcolor="blue">
    <h1 align="center">
      <font color="red"><b>VEEDU SAPADU</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>RUS PIZZA</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
        Hotel Veetu Saapadu is a F&B-Casual Dining outlet located in the heart of the city. It offers a wide variety of delicious South Indian dishes, ranging from traditional to modern. The restaurant has a cozy and inviting atmosphere, with comfortable seating and a friendly staff. The menu features a variety of vegetarian and non-vegetarian dishes, as well as a selection of desserts. The restaurant also offers a variety of beverages, including tea, coffee, and soft drinks. The restaurant is open for lunch and dinner, and also offers catering services for special occasions. </font>
    </p>
  </body>
</html>

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>MAG Engineering </title>
  </head>
  <body bgcolor="blue">
    <h1 align="center">
      <font color="red"><b>MAG Engineering </b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>RUS PIZZA</b></font>
    </h3>
    <hr size="3" color="red" />
    <p align="justify">
      <font face="Georgia" size="5">
        Provider of sheet metal fabrication services. The company manufactures operator cabins, canopies, housings, panels, switchboards, control cabinets and a variety of hi-precision sheet metal components for industrial requirements in light and medium categories enabling enterprises toProvider of sheet metal fabrication services. The company manufactures operator cabins, canopies, housings, panels, switchboards, control cabinets and a variety of hi-precision sheet metal components for industrial requirements in light and medium categories enabling enterprises to.</font>
    </p>
  </body>
</html>
```


## OUTPUT
<img width="832" alt="Screenshot 2023-11-19 at 10 54 27 PM" src="https://github.com/Andrewvarghese653/NearMe/assets/145822115/5846a486-4f86-49e4-a9e7-c1763eb6fc09">
<img width="832" alt="Screenshot 2023-11-19 at 11 10 16 PM" src="https://github.com/Andrewvarghese653/NearMe/assets/145822115/b13470cd-42ba-40ff-a2b1-3e17774ecc55">
<img width="830" alt="Screenshot 2023-11-19 at 11 11 55 PM" src="https://github.com/Andrewvarghese653/NearMe/assets/145822115/12908c7f-4327-4026-b549-8dbe7dbc7365">
<img width="832" alt="Screenshot 2023-11-19 at 11 13 15 PM" src="https://github.com/Andrewvarghese653/NearMe/assets/145822115/307d9c86-29a6-49d8-9b7c-2136979ff6b7">
<img width="826" alt="Screenshot 2023-11-19 at 11 14 24 PM" src="https://github.com/Andrewvarghese653/NearMe/assets/145822115/510891b7-d598-4c37-bdef-6b1dd17cc530">
<img width="830" alt="Screenshot 2023-11-19 at 11 15 16 PM" src="https://github.com/Andrewvarghese653/NearMe/assets/145822115/1db904bd-844e-40d1-98f7-7a8587fe6b10">













## RESULT
The program for implementing image maps using HTML is executed successfully.
