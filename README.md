# Ex03 Places Around Me
## Date: 17/12/25

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
        <title>Dhivya Dharshini</title>
    </head>
    <body>
        <h1 align="center">PONDICHERRY MAP-25004153</h1>

<img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Beach" title="Beach" href="beach.html" coords="1213,251,1507,421" shape="rect">
    <area target="" alt="JIPMER" title="JIPMER" href=" hospital.html" coords="667,202,120" shape="circle">
    <area target="" alt="WHITE TOWN" title="WHITE TOWN" href="town.html" coords="1180,511,1486,471,1509,638,1200,697" shape="poly">
    <area target="" alt="POTHYS PONDICHERRY" title="POTHYS PONDICHERRY" href="store.html" coords="968,466,1165,528" shape="rect">
    <area target="" alt="JIPMER COLLEGE" title="JIPMER COLLEGE" href="college.html" coords="811,169,747,365,1063,283,957,219,880,157,854,167" shape="poly">
</map>

beach.html

<html>
    <head>
        <title>BEACH</title>
   </head>
   <body bgcolor="blue">
    <b><h1 align="center">PONDICHERRY BEACH</h1></b>
    <hr>
   <b><p>Pondicherry offers several distinct beaches, with the Promenade Beach (Rock Beach) being a popular city-center spot known for its rocky shore, the historic promenade, and nearby colonial landmarks, while Paradise Beach is a tranquil white-sand beach requiring a short ferry ride through mangrove forests and is ideal for relaxation
   </b>  
    </p>
   </body>
</html>

hospital.html

<html>
    <head>
    <title>hospital</title>
    </head>
    <body bgcolor="aqua">
        <b><h1 align="center">JIPMER</h1></b>
        <hr>
        <b><p>
             JIPMER Hospital in Puducherry is a multi-specialty, tertiary care referral hospital and an Institute of National Importance (INI) that provides quality education, medical research, and higher-order patient care under the Ministry of Health and Family Welfare, Government of India.
              The hospital offers a wide range of services, including free specialty healthcare and a variety of undergraduate, postgraduate, and super-specialty courses.  
             </p>
    </body>
</html>

college.html

<html>
    <head>
        <title>college</title>
    </head>
    <body bgcolor="cyan">
        <b><h1 align="center">JIPMER COLLEGE</h1></b>
        <hr>
       <b><p>JIPMER (Jawaharlal Institute of Postgraduate Medical Education and Research) is famous for its undergraduate and postgraduate medical courses, its excellent healthcare facilities particularly for low-income patients, its role as an Institute of National Importance, its quality education, and its emphasis on both medical training and research
        Prestigious Medical Education: JIPMER offers renowned undergraduate (MBBS) and postgraduate (MD/MS, DM/MCh, PhD) medical programs, attracting students from all over the world. 
Institution of National Importance: Declared an "Institute of National Importance" by the Indian Parliament in 2008, it is a highly respected and autonomous institution. 
Excellent Healthcare Services: It is known for providing high-quality patient care and possesses excellent health facilities, serving a large patient population, many of whom are from low socioeconomic backgrounds. 
       </b>  
</p>

    </body>
</html>

store.html

<html>
    <head>
        <title>STORE</title>
    </head>
    <body bgcolor="hotpink">
        <b><h1 align="center">POTHYS PONDICHERRY</h1></b>
        <hr>
       <b><p>Pothys is famous for its vast and authentic collection of silk sarees, featuring its exclusive, trademarked in-house brands like Samudrika, Parampara, and Vasundhara, which are known for quality, design, and variety. 
        As a prominent South Indian textile retail brand with a long legacy, it's a household name in Tamil Nadu and a top choice for wedding wear and festive fashion, offering both traditional and contemporary ethnic wear beyond just silk.  
       </b> 
        </p>  

    </body>
</html>

town.html

<html>
    <head>
        <title>white town</title>
    </head>
    <body bgcolor="red">
       <b><h1 align="center">WHITE TOWN</h1></b>
       <hr>
        <b><p> Pondicherry's White Town is the city's historic French Quarter, known for its well-preserved colonial architecture, charming cobbled streets, and vibrant blend of French and Indian cultures.
             Once the exclusive residential area for the French, it now features iconic landmarks like the Promenade Beach, the French War Memorial, and the Aurobindo Ashram.
             Visitors can explore diverse shops, art galleries, and cafes, enjoy French-style buildings with open courtyards, and experience a unique atmosphere that feels like a slice of France in India.
        </b>  
</p>
    </body>
</html>
```


## OUTPUT
<img width="1040" height="437" alt="Screenshot 2025-12-22 221947" src="https://github.com/user-attachments/assets/97dfd0fb-ed60-49aa-81fc-a7dbf1a678d7" />
<img width="1035" height="314" alt="Screenshot 2025-12-22 222002" src="https://github.com/user-attachments/assets/97b3b8b1-1088-4c1b-a720-7b297b7cfaaf" />
<img width="1039" height="307" alt="Screenshot 2025-12-22 222013" src="https://github.com/user-attachments/assets/496bf276-c9f2-4024-9b55-8a13c3c6119e" />
<img width="1039" height="299" alt="Screenshot 2025-12-22 222025" src="https://github.com/user-attachments/assets/8f159c10-fcdb-4881-af0c-db703eabad8d" />
<img width="1035" height="336" alt="Screenshot 2025-12-22 222036" src="https://github.com/user-attachments/assets/43f7614f-7711-41af-8226-432be1ec3105" />
<img width="1037" height="257" alt="Screenshot 2025-12-22 222052" src="https://github.com/user-attachments/assets/00751cc0-7510-43ab-aa55-cb69fa6cf1f8" />


## RESULT
The program for implementing image maps using HTML is executed successfully.
