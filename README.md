# Face Detection by using Javascript and Node.js

This project is a fork from Kyle's Face-Detection-Javascript program. 
Those days when he writes that code, browsers allow web pages to upload training data directly from files.
But new browsers do not allow web pages to directly upload data from local computers. 
For that to work I write a small  server based on node.js to handle the file upload in a way that it works as expected. 

# How to use this program

You are supposed to have node.js installed before running this program.
Also you need to have a webcam attached to the computer.

1. Download the project. 
2. In main folder, run npm install. It installs express library.
3. run **node server.js** to start the program.
4. Open a web browser ( I tested just by chrome) and input http://localhost:3000
5. It will open the webcam and after a while it starts detecting faces and emotions.

