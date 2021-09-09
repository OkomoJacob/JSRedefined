### Contents:
- [Introduction](#introduction)
  - [What is Javascript and its Applications?](#what-is-javascript-and-its-applications)
- [1. Tools and Running JS](#1-tools-and-running-js)
  - [1. Start with GIS and a GIS Software](#1-start-with-gis-and-a-gis-software)
    - [Resources](#resources)
- [2. Comments](#2-comments)
- [3. Data Types and Variables](#3-data-types-and-variables)
  - [Data Types](#data-types)
  - [Varaibles](#varaibles)
- [4. Learn about mapping libraries and other required utilities](#4-learn-about-mapping-libraries-and-other-required-utilities)
    - [Resources:](#resources-1)
  - [5.Now Move to working with Map servers](#5now-move-to-working-with-map-servers)
      - [Examples](#examples)
  - [6. Learn about databases and backend](#6-learn-about-databases-and-backend)
    - [Resources:](#resources-2)
  - [7. Learn a frontend frameworks (Additional)](#7-learn-a-frontend-frameworks-additional)
    - [Resources:](#resources-3)
- [Final Notes](#final-notes)
- [Errata](#errata)
      - [Acknowledgements](#acknowledgements)
- [Related Articles](#related-articles)

## Introduction
This is the comprehensive path, buddy
### What is Javascript and its Applications?

## 1. Tools and Running JS

<img src= "https://github.com/OkomoJacob/myLibrary/blob/main/GISDev%20RoadMap/roadmap.png">

### 1. Start with GIS and a GIS Software
The basic GIS Operationis Key

#### Resources
1. [Building a Python Plugin (QGIS3)](https://www.qgistutorials.com/en/docs/3/building_a_python_plugin.html)
2. [Chapter 1 Introduction to GIS](https://mgimond.github.io/Spatial/introGIS.html)

## 2. Comments
// inline comments
/*Multiline Comments*/ 
   
## 3. Data Types and Variables
 ### Data Types
- Anything meaningful to the computer
- JS has 7 (Seven) Data types <br>
1. [Undefined]() Hasn't been defined yet
2. [Null]()
3. [Boolean]() True or Flase
4. [String]()
5. [Symbol]() An immutable primiive value that is unique
6. [Number]()
7. Object
- 
### Varaibles
Assigns a memory in store for the comp

There are three (3) ways of assiging variables in JS. ie. Using `var`, `let` and `const`
```jsx
var myName = "Okomo" // Used throughout the program i.e globally
let myName = "Okomo" // Only used within the scope you've declared them
const myName = "Okomo" // Should (cannot) be changed, or it will throw an error
```

## 4. Learn about mapping libraries and other required utilities

Use Mapping libaraies to bulid the web-GIS portal data visualization interface. Here are the lists of some most commonly used mapping libraries;

- [LeafletJs](https://leafletjs.com/): It is the open-source, lightweight javascript library
- [OpenLayers](https://openlayers.org/): It is also an open-source javascript library.Read this blog [OpenLayers: Geospatial JavaScript Library](https://www.gislounge.com/openlayers-geospatial-javascript-library/))
Turf JS: Advanced geospatial analysis for browser and Node.js. etc

- **Recommendation:** Learn about mapping libraries for another 3 weeks. Instead of learning the basics of all libraries, master one.

Here are the some project ideas that can help you to improve your knowledge

  - Visualization of administrative boundary dataset (district, region etc) into map
  - Build web-GIS basic tools (eg. get coordinate, get current position, full screen view, custom zoom in/zoom out button etc)
  - Create the simple portal for geospatial data visualization

#### Resources:

1. [Leaflet from basic to advance (youtube playlist)](https://www.youtube.com/playlist?list=PLyWyQBSWLw1NH1wsA0wkSMTlQ45P0AqCj)
2. [Leaflet tutorials](https://leafletjs.com/examples.html)
3. [Open layer tutorials](https://openlayers.org/en/latest/doc/tutorials/)
4. [Qgis2Web tutorial](https://www.qgistutorials.com/en/docs/web_mapping_with_qgis2web.html)
- Read from the official website of the required library

### 5.Now Move to working with Map servers

For publishing a complex amount of structural dataset which cannot be held by the above [mapping libraries](#4-learn-about-mapping-libraries-and-other-required-utilities).
They can provide the Open Geospatial Consortium (OGC) standard services like Web Map Service (WMS), Web Feature Service (WFS), Web Coverage Service (WCS).

##### Examples
[GeoServer]() :An open-source server for sharing geospatial data.
[MapServer]() :Mapserver is an open-source platform for publishing spatial data and publishing interactive mapping applications to the web. 
GeoTool : The open-source java GIS toolkit.
GeoNetwork : A catalog application to manage spatially referenced resources. 
GLG map server : Generic Logic Inc. is a premier provider of real-time graphics, 

- **Recommendation:** You should spend at least 3 weeks on learning web map servers. Spend more time on OGC standards and its use. Learn geoserver and its application in detail.

### 6. Learn about databases and backend
Applicable for a large application.A database is used to store the geospatial data and the backend is used to query and get the required information in any web-applications. The backend can control and send the logic to the web-application.

There are lots of programming languages and frameworks purely dedicated to backend. The most popular languages are: <br>
    - Python <br>
    - Php <br>
    - Javascript <br>
    - Java <br>
    - Ruby <br>
    - Rust etc. <br>
    - 
- The most popular frameworks are django, laravel, ruby on rails, flask,  expressjs,  spring etc.

You can choose one language first and learn the framework later. Let’s suppose you want to learn about django (Python framework), you need to spend some time on learning python before. 

In this stage, you should learn at least about the following things,

   - About the Structured Query Language (SQL)
   - About the API (GET, POST, PUT, DELETE) request
   - At least develop one Create, Read, Update, Delete (CRUD) project
   - About the Object Relational Mapping (ORM)
   - Working with PostGIS and it’s extensions such as PG Routing

- Using the backend, now you can connect the mapping server and create the interactive web-GIS portals

_GeoJSON serializer, GeoSpatial data visualization portal using PostGIS database_ etc are some of the beginner level backend projects on web-GIS. 

**Recommendation**: Learn about Django. You should spend at least 3 weeks learning the databases(PostGIS/PostgreSQL combo recommended) , spatial SQL and backend technology.

#### Resources:

1. [Spatial bookmarking note (Youtube playlist)](https://www.youtube.com/playlist?list=PLyWyQBSWLw1OUfqcPzO6AceuGpC5gr-_n)
2. [Introduction to Web Mapping and Web GIS ( Udemy course)](https://www.udemy.com/course/3.introduction-to-web-mapping-and-web-gis-2020-geodjango/?referralCode=72E09BDD6D9C8ECE2169)
3. [Web mapping and Web-GIS from Dev to Deploy 2021: GeoDjango (Udemy course)](https://www.udemy.com/course/web-mapping-and-web-gis-from-dev-to-deploy-2021-geodjango/?referralCode=14893C9BD7E7D959F865)
3. [Make a Location-Based Web App With Django and GeoDjango (Blog)](https://realpython.com/location-based-app-with-geodjango-tutorial/)
4. [QGIS and the Spatial Database, Emmanuel J](https://jeafreezy.hashnode.dev/section-4-qgis-and-the-spatial-databasepostgis-ckoln6gzi0a5r2gs1axaocrm3)
5. [A playlist to dive into Spatial SQL and PostGIS by the great Quisheng Wu!](https://www.youtube.com/watch?v=fgS1eVPPBiE)
6. [Official Introduction to PostGIS](https://postgis.net/workshops/postgis-intro/introduction.html)
7. [Interactive learning platform by Crunchy Data](https://learn.crunchydata.com/training/postgis)
8. [Geodjango playlist](https://www.youtube.com/watch?v=QiLO3MQxvds&list=PL7amXK4vKqATa_KrfQ3_tEF_ywAgAqWeJ)

### 7. Learn a frontend frameworks (Additional)
- Frontend frameworks help to determine the logic, structure, design, behaviour and animation of every element you see on screen when you interact with web applications. 
- The frontend framework makes it easy to build the web pages faster. We can say this as an additional thing since we can build the web-GIS applications without learning any frontend frameworks as well. 
- The most popular frontend libraries on javascript are as below,

1. [React](https://reactjs.org/): React builds the UI in component based structure. It is supported and maintained by Facebook and Open Source Community.
2. [Vue](https://vuejs.org/): Vue builds the UI in model-view-view model structure. It is not supported by any big company but lots of developers around the world maintain it.
3. [Angular](https://angularjs.org/): Angular builds the UI in MVC pattern. It is supported and maintained by google.

**Recommendation**: You should spend at least two month on learning a frontend frameworks of choice. 

#### Resources:

1. [Top 10 webGIS UI 2021, GeoDev](https://www.youtube.com/watch?v=KULAc4P1Sh4)
2. [React documentation](https://reactjs.org/docs/getting-started.html)
3. [React courses](https://reactjs.org/community/courses.html)

## Final Notes
The list we have put together is absolutely non exhaustive. We all know the geospatial industry is highly dynamic, there are emerging technologies we didn’t capture such as; 
- Augmented Reality (AR)
- Virtual Reality (VR)
- Spatiotemporal Asset Catalogs (STAC)
- Cloud Optimized Geotiffs (COGs)
- Google Earth Engine
- Microsoft Planetary Computer, and many more earth observation tools and technologies.

The goal of the article was not to overwhelm you with trending technologies and we believe you’ll learn about them as you make progress. Just get started first! 

-Happy learning!
## Errata
This is just a thought, and all literature presented here is human generated.Therefore aby error
##### Acknowledgements

1. [Tek Kshetri]() is the research Associate at Geoinformatics Center, Asian Institute of Technology, Thailand. He is mainly working on web-GIS technology and spatial data analysis.
2. [Emmanuel Jolaiya](https://linktr.ee/JolaiyaEmmanuel) is a GIS developer with a really really really special interest in geospatial community development.
3. 
## Related Articles
1. [6 Open Source Powered Projects to Enrich Your GIS Programming Skills,GISLounge](https://www.gislounge.com/6-open-source-powered-projects-to-enrich-your-gis-programming-skills/)
2. [WebGIS Section 1 – A Quick Introduction to GIS and WebGIS](https://www.gislounge.com/section-1-a-quick-introduction-to-gis-and-webgis/)
3. [An Introduction to ArcGIS ModelBuilder](https://www.gislounge.com/an-introduction-to-arcgis-modelbuilder/)
