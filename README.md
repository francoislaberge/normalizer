Overview
=============

This is the start of a project to make it easy for anyone to generate and render normal maps all using Javascript. Additionally I owe (still after 2+ years since I made the demos) a write up on how to us a camera to take photos that you can extract the normals of every day objects.


Instructions
=============

To run the demos, you must host the files in this project. Otherwise you'll get a security error because the demos require reading the pixels of loaded images which isn't allowed for HTML loaded on the file:/// protocol.

-------------
We provide a simple Python based server for you to host files. Run the following from the command line while inside the root folder
    
    ./server
    
Now open [http://localhost:8080/](http://localhost:8080/) in your browser and select a demo.
