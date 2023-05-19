# Archon-vis (my bachelor's degree final project)

## Abstract:

Due to its large applicability, web services have been gaining more popularity. This means that more hierarchical data are generated with hierarchical, mainly in JSON or XML formatted files. However, many users still use tabular files, such as Excel spreadsheets and CSV files. Without a specific tool, visualizing and understanding fully the hierarchy surrounding the data becomes a hard task, sometimes requiring programming skills. In order to support the users leading with hierarchical data in tabular format, in this work, we present a web-based tool that allows users to load, manipulate and understand hierarchical data from tabular data. The tool was developed using web technologies and data visualization principles to represent hierarchical data through a radial tree. The tool and its functionalities are demonstrated through a case study of skin cancer images, where users can investigate different hierarchies, manipulate and export data in JSON format or keep them as tabular data.

## Objective:

This work was inspired by [Chang's](https://www.youtube.com/watch?v=G0efD_p_E3s) project that proposes an approach to deal with hierarchies directly in spreadsheet format. However, Chang's work does not create any kind of visualization and the visual representation of data can be essential to generate insights about the dataset

This project aims to meet the following requirements related to the problem to be solved:
* Requirement 1: The data explored by the application is of low volume and is in an input file in tabular format (ex.: .csv) provided by the user;
* Requirement 2: The application must allow users to modify hierarchically structured data values as well as reorganize the hierarchy of these data;
* Requirement 3: The user does not need to have programming skills;
* Requirement 4: The application must allow exporting the modified data in .csv or .json formats;
* Requisito 5: Data must be represented in a visual way, making it easier to understand the data hierarchy.

### Built With

This section should list any major frameworks/libraries used to bootstrap this project. 
* [JavaScript](https://www.javascript.com/)
* [CSS](https://css-tricks.com/)
* [HTML](https://html.com/)
* [D3.js](https://d3js.org/)
* [JQuery](https://jquery.com/)

### the Data sample

The data we used as sample are obtained from the International Skin Imaging Collaboration (ISIC, 2021). The set used is a subset of dermoscopic images of skin lesions constituted for 232 items, a small amount but enough to simulate an image library built by a doctor from his patients. [Check it out](https://github.com/gabrieldasneves/Archon-viz/blob/main/data/lesions.csv)

### Interface

![](https://github.com/gabrieldasneves/Archon-viz/blob/main/media/derm1.PNG?raw=true)

## Auxiliary buttons

The zoom buttons amplify and reduce the size of the tree within the view window, if the image is larger than this area, the tree can be dragged across the screen with the mouse.
The rotation functionality, however, rotates the tree around the root clockwise or
counter-clockwise.
The select buttons select the next right or left sibling node. There is
also two view buttons where the first one returns the tree to the initial position and the second one,
places the selected node in the center of the viewport:


![](https://github.com/gabrieldasneves/Archon-viz/blob/main/media/c3.PNG?raw=true)


<p align="right">(<a href="#top">back to top</a>)</p>


![](https://media2.giphy.com/media/jakQnxhPwrbOdEZDul/giphy.gif?cid=ecf05e479yyngvlbwnzb76cecmijtztow2lbtfut6o9458qz&rid=giphy.gif&ct=g)