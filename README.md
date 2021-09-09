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
- [4. Operators](#4-operators)
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
7. [Object]()
- 
### Varaibles
Assigns a memory in store for the comp

There are three (3) ways of assiging variables in JS. ie. Using `var`, `let` and `const`
```jsx
var myName = "Okomo" // Used throughout the program i.e globally
let myName = "Okomo" // Only used within the scope you've declared them
const myName = "Okomo" // Should (cannot) be changed, or it will throw an error
```
- Declaring <br>
- Assigning variables <br>
- Initializing Varibales using Assignment operator<br>
## 4. Operators
1. Assignment =, ==, ===
2. Addition (+)
3. Subtraction (-)
4. Multiplying (*)
5. Divide (/)
6. Incrementing Numbers: (++) Meaning you add 1 to a numerical varaible.
7. Decrementing Numbers: (--) Meaning you sub 1 to a numerical varaible.
   
```jsx
var sumMultSub = 10 + 20*20-20;
console.log(sumMultSub); //ans
```

```jsx
// Incrementing
var myNum = 90;
myNum ++; //myNum = myNum + 1;

// Decrementing
myNum --;
```
ured Query Language (SQL)
   - About the API (GET, POST, PUT, DELETE) request
   - At least develop one Create, Read, Update, Delete (CRUD) project
   - About the Object Relational Mapping (ORM)
   - Working with PostGIS and it’s extensions such as PG Routing

- Using the backend, now you can connect the mapping server and create the interactive web-GIS portals

_GeoJSON serializer, GeoSpatial data visualization portal using PostGIS database_ etc are some of the beginner level backend projects on web-GIS. 

**Recommendation**: Learn about Django. You should spend at least 3 weeks learning the databases(PostGIS/PostgreSQL combo recommended) , spatial SQL and backend technology.

##### Acknowledgements

1. [Tek Kshetri]() is the research Associate at Geoinformatics Center, Asian Institute of Technology, Thailand. He is mainly working on web-GIS technology and spatial data analysis.
2. [Emmanuel Jolaiya](https://linktr.ee/JolaiyaEmmanuel) is a GIS developer with a really really really special interest in geospatial community development.
3. 
## Related Articles
1. [6 Open Source Powered Projects to Enrich Your GIS Programming Skills,GISLounge](https://www.gislounge.com/6-open-source-powered-projects-to-enrich-your-gis-programming-skills/)
2.