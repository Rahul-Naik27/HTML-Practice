# README.txt

Project Name:
Mumbai Skyline Image Map Feature

Description:
This project demonstrates how to use an HTML image map to create clickable regions inside an image.
Specific parts of the image can be clicked, and each clickable area opens a separate webpage that shows more images related to that object.
In this project, the image of the Mumbai skyline contains clickable areas such as the Taj Mahal Palace, Gateway of India, boats near the shore, and birds flying over the sea.

Purpose:
The purpose of this project is to practice the HTML image map feature and understand how users can interact with different parts of an image.

Features:
* Interactive image map
* Multiple clickable regions inside one image
* Navigation to separate HTML pages
* Organized folder structure for images and HTML files
* Use of different shapes like rectangle and polygon for clickable areas

How the Image Map Works:
The main page (index.html) displays an image of the Mumbai skyline.
The image uses the "usemap" attribute to connect with a map element.
Example:
<img src="../images/skyline.webp" usemap="#skyline">
Inside the map element, different clickable regions are defined using the "area" tag.

Each area contains:
* shape (rect or poly)
* coordinates
* a link to another HTML page
When a user clicks on one of these regions, a new page opens showing images related to that object.

Technologies Used:
* HTML5

Topics Practiced:
* HTML image maps
* Anchor navigation
* HTML page linking
* Project folder organization
* Use of alt attributes for accessibility

How to Run the Project:
1. Download or clone the project.
2. Open the folder named "map-feature-project".
3. Open the file "index.html" in a web browser.
4. Click on different parts of the skyline image to explore the feature.

learnings:
Created as a practice project to learn HTML interactive features.

Notes:
This project is intended for learning purposes and demonstrates how image maps can be used to build interactive webpages.
