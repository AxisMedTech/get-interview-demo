# GWT Interview Demo
The goal of this demo is to give you a place to show off your knowledge of the GWT platform and web technologies.

## Specification
You will be building a simple app with a navigation bar at the top of the page and a content area below it.  This navigation bar will have links that when clicked will swap out the content below it.  You only need to support the latest build of Chrome and can assume that the minimum browser size will be 768px wide by 768px tall, but could also be expanded to fit a large monitor. [Click Here](https://github.com/AxisMedTech/interview-development-test/blob/master/GWT/GWT%20Developer%20Test.pdf?raw=true) to get the mockup.

## Goals
- URL based navigation
- Use GWTP slots to switch out child presenters in the content area
- Effective use of CSS to style the app
- The mockup provided is just a wireframe, choose a color pallete, fonts, etc and make the site look good
- **Most importantly be creative and show off your development and design skills!**

## Getting Started
Use this maven archetype to create a basic GWT project that uses GWTP:
https://github.com/ArcBees/Arcbees-Archetypes/tree/master/archetypes/gwtp-basic

For more info / documentation on GWTP visit their github repo wiki: http://dev.arcbees.com/gwtp/

*Please note that additional external frameworks / libraries should not be used for this demo.  It is expected that you will be using standard GWT, GWTP, and CSS.*

## Submitting your work
Send an email to devtest@axismedtech.com with your name as the subject and the message body containing a link to a public Github repository with your work in it.

Here are the steps I will take to check it out:

1.  Clone your repo
2.  ```mvn clean compile```
3.  Open the project using IntellijIDEA
4.  Run using Super Dev mode and Chrome
