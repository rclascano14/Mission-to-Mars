# Mission-to-Mars
`Module 10: Building an app to scrape websites for data pertaining to the Mission to Mars, and then creating a HTML page to display my findings.` 

## Resources

- Python
- Jupyter Notebook
- MongoDB
- Visual Studio Code
- Flask
- Data: app.py, scraping.py, Mission_to_Mars.ipynb, index.html

## Overview of Project

In this module, I am being asked to automate a web browser to be able to visit a plethora of websites and extract data about a Mission to Mars. After doing this, the extracted data will then be stored in a NoSQL database and then rendered in a web application created through the use of Flask. With these steps completed, I shall display this work in my own portfolio. For this challenge, the web app that I have created is working, but I am asked to further polish it. This polish is to be found through the incorporation of scraping from Mars hemispheres online. Specifically, I am being asked to use BeautifulSoup and Splinter to scrape full resolution images of these Mars's hemispheres. Upon doing this, I will store the scraped data on a Mongo Database, use a selected web app to display this data and lastly, alter the web design to present the images in a clean and creative format. 

## Results

This Weeks Module consists of the following three deliverables:

### Deliverable 1: Scrape Full-Resolution Mars Hemisphere Images and Titles

<img width="1146" alt="Deliverable 1 (10)" src="https://user-images.githubusercontent.com/95828604/156097636-72f2d5f9-91bb-4c92-b64c-b5f7e61e0cbf.png">

<img width="1126" alt="Deliverable 1-1 (10)" src="https://user-images.githubusercontent.com/95828604/156097577-71129db3-7892-44d3-8174-f3f29702543e.png">

### Deliverable 2: Update the Web App with Mars Hemisphere Images and Titles

The second Deliverable askes me to further modify the web app with images of the 4 Mars Hemispheres as well as to title each one. My index.html file was revised to loop through my web app for both the Mars Hemisphere images and titles as seen below. 

<img width="709" alt="Deliverable 2 (10)" src="https://user-images.githubusercontent.com/95828604/156307288-a6799ee6-4b1d-4936-9600-df0e4538271a.png">

### Deliverable 3: Add Boostrap 3 Components

In order to complete, Deliverable 3, I was asked to make three modifications to my index.html code in order to style the created webpage with Bootstrap component alterations.

(1) I modified the body tag (<Body>) by specifying that I wanted the background of the webpage to be #cf491c, which is a blood orange color.
  
 - `<body style="background-color:#cf491c;color:black">`
  
(2) This modification also designates that I want the lettering of the body to be black in color.
  
(3) In addition to altering the body, I changed the header as well through the use of a gradient color shading. I specified it as the same blood orange color as previously used for the body of the webpage.
  
- `<div style="background:linear-gradient(to bottom, #d4baba 15%, #cf491c 85%)!important" class="jumbotron text-center">`

<img width="910" alt="Deliverable 3 (10)" src="https://user-images.githubusercontent.com/95828604/156303671-9dfa6c8b-7d8a-4c3a-a116-b804ef9d33da.png">

## Summary

 In summation, I have foremost, used a Python script to scrape both images and text from the following websites. 
  
  - https://data-class-mars.s3.amazonaws.com/Mars/index.html
  - https://spaceimages-mars.com
  - https://galaxyfacts-mars.com
  - https://marshemispheres.com/
  
 After this, I used Flask to display the scraped data within a Mongo database. The web app that I created throughout this module was altered to include the images and titles of the Mars Hemispheres and lastly, I added some minor Boostrap Component modifications to present the web app in a clear and visually appealing format.
