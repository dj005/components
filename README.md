## Component Development Work

### Problem Statement
Write the HTML, CSS and necessary Javascript for the "MarqueeL" and the "Product Combinator".
### Approach
I have created two different HTML as per MarqueeL & Product Combinator design specs.

 1.	Component - *MarqueeL*
 
 I have divided the design in four major sections:
 - Banner logo
 - Banner heading text
 - Banner button
 - Banner right image
These values will be taken from dialog input & static data in current HTML will be replaced with derived content from AEM.
This can be used as a customizable product banner for different products. 
2.	Component - *Product Combinator*

This component is divided into two sections. 
-	Left section is marketing text
-	Right section is product tabs. For tab section, list of image & description will be taken from dialog & iterated to get desired HTML spec.

### Set up instructions
Download the project from below location:
 ```
https://github.com/dj005/components
  ```
Get your development environment set up. Install http-server globally using below command.
 ```
npm install http-server -g
  ```
 Open up a terminal, `cd` into the directory where index.html is located. Run below command to start server:
  ```
http-server
  ```
Go to below link to see the project in action.
  ```
http://127.0.0.1:8080/
  ```
