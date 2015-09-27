# docqr.github.io
View Building Construction Docs Online via QR Codes

#Problem Statement:
##Demystiphy 2D!

BIM software such as Revit and Archicad have been designed to generate a 3D building model, to then produce 2D [paper] drawings.

Once printed, the sections displayed in 2 dimensions might not entail all of the detail necessary to understand the building. 
DOC-QR is a tool that aims to visuals those sections, shown in 2D architectural drawings, as trimmed sections of the 3D Revit model, in a web browser.

The project was proposed by Jonatan Schumacher [here](http://aec-technology-hackathon-2015.devpost.com/forum_topics/5187-3d-model-viewer-to-accompany-2d-drawings) - check out the sketch below for the rough idea.
![alt tag](https://raw.githubusercontent.com/DOCQR/web-viewer/master/files/documentation/JS_HackathonProposal.jpg)

This tool currently consists of two parts: 
1. node.js application
2. Revit Plugin

The web application allows users to create an account, and to create 'Projects'. 
The Revit plugin, which communicates with the web app, prompts the user to log in. Once logged in, one can select one of the user's projects, and publish 3D sections of all drawings in the Revit model. 
In the same process, the Revit app also places QR codes next to all views on the sheets, and uploads the 3D models to the webapp, where they can be retreived at the URLs stored in the QR code.

[Video of Revit Demo] (https://youtu.be/cHrULgEkMXw)
