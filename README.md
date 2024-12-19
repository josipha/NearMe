# Ex04 Places Around Me
## Date: 19/12/2024

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
        <title>My City</title>
    </head>
<body>
    <h1 align="center">
        <font color="red"><b>Pondicherry</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>JOSIPHA (24900212)</b></font>
    </h3> 
    <center>
        <img src="map.png" usemap="#image-map">

        <map name="image-map">
            <area target="" alt="POGO LAND" title="POGO LAND" href="park.html" coords="137,90,434,196" shape="rect">
            <area target="" alt="PONDY MARINA" title="PONDY MARINA" href="beach.html" coords="1534,438,110" shape="circle">
            <area target="" alt="NILAN ZINGLE RESORT" title="NILAN ZINGLE RESORT" href="resort.html" coords="600,792,893,893" shape="rect">
            <area target="" alt="EDEN BEACH" title="EDEN BEACH" href="flagbeach.html" coords="1498,751,96" shape="circle">
            <area target="" alt="WHITE TOWN" title="WHITE TOWN" href="town.html" coords="1347,229,1605,312" shape="rect">
        </map>
    </center>
</body>
beach.html
</html>
<html>
    <body bgcolor="lightgreen">
        <font><h1 align="center">Marina beach </h1> </font>
        <font align="center" size="5"><p><br>
            Pondy Marina Beach in Pondicherry is the new tourist attraction near the new lighthouse. It was developed under the theme-based beaches programs by the Pondicherry government, and “Pondy Marina” beach is based on a food-based theme.

Pondy Marina Beach is located at Dubrayanpet, 1.5km from the White town, Pondicherry. Unlike the rock beach, where the tourists can hardly venture into the seashores, here, as the name suggests, there is a reasonable length of sandy beach. Pondy Marina offers various food options, such as mangrove forest boating, sandy beaches, river mouth sighting, mangrove forest boating, etc. Pondy Marina is one of the best places to see sunrise in Pondicherry.
    </body>
</html>
flagbeach.html
<html>
    <body bgcolor="lightpink">
        <font><h1 align="center">EDEN BEACH</h1> </font>
        <font align="center" size="5"><p><br>
            Eden Beach Pondicherry (Puducherry) is a newly developed beach by the government of Pondicherry compared to other beaches in Pondicherry. The Denmark-based non-profit Foundation has awarded Eden Beach a blue flag tag beach for Environmental Education or FEE.

            Blue Flag beaches are the cleanest beaches globally, eco-friendly, and have all the amenities tourists need. In India, only ten beaches are given the Blue flag Tag; Eden Beach in Pondicherry is one of them. So, getting the blue tag for Eden Beach is a proud moment for the Pondicherry people. 
        </p></font>
    </body>
</html>
park.html
<html>
    <body bgcolor="lightblue">
        <font><h1 align="center">POGO LAND </h1> </font>
        <font align="center" size="5"><p><br>
            Pogo Land in Pondicherry offers a mix of experiences for visitors, with some praising the water rides like wave pools and waterfalls as highlights. However, there are concerns about maintenance issues, limited ride availability, and cleanliness problems in certain areas. Some reviewers found the amusement park worth the entry fee for families but noted drawbacks such as closed attractions, lack of safety precautions on certain rides, and unsatisfactory canteen facilities. Despite mixed reviews, Pogo Land is described as a decent place to visit near Pondicherry for those looking for water-based entertainment and land games.
        </p></font>
    </body>
</html>
resort.html
<html>
    <body bgcolor="cyan">
        <font><h1 align="center">NILAN ZINGLE RESORT </h1></font>
        <font align="center" size="5"><p><br>
            Nilan Zingle Resort in Pondicherry is a luxurious and serene escape that seamlessly blends contemporary comfort with the charm of South India's coastal landscape. Nestled amidst lush greenery and just a short drive from Pondicherry’s golden beaches and vibrant city center, this resort offers a tranquil retreat for families, couples, and solo travelers alike, all within easy reach of the area’s rich culture and attractions
        </p></font>
    </body>
</html>
town.html
<html>
    <body bgcolor="lightgray">
        <font>
            <h1 align="center">WHITE TOWN</h1>
        </font>
        <font align="center" size="5"><p><br>
            As the name suggest it was a secluded section in Pondicherry which was exclusively reserved for the white French people who had settled here and called it home after 1674 when they acquired it and used it as a trading post along with other locations such as Mahe, Karaikal, Yanam and Chandannagar.
        </p></font>
    </body>
</html>
```


## OUTPUT
![alt text](<imageapp/map/static/Screenshot 2024-12-19 224646.png>)
![alt text](<imageapp/map/static/Screenshot 2024-12-19 224717.png>)
![alt text](<imageapp/map/static/Screenshot 2024-12-19 224741.png>)
![alt text](<imageapp/map/static/Screenshot 2024-12-19 224849.png>)
![alt text](<imageapp/map/static/Screenshot 2024-12-19 224911.png>)
![alt text](<imageapp/map/static/Screenshot 2024-12-19 224941.png>)








## RESULT
The program for implementing image maps using HTML is executed successfully.
