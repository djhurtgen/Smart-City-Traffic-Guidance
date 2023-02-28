# Smart-City-Traffic-Guidance

To run the program in Microsoft Visual Studio, clone the remote repository to a folder of your choice on your local machine. Be sure to cd into the repo folder and use the command 'git checkout branch hurtgen_v2'. Then, create a VS project in the same parent folder as the cloned repository (i.e., outside the cloned repository) and name it 'traffic-management'. Simply drag the following files into the project within the VS solution:

Header files, path is traffic-management/_src/_include:
Map.h, 
Road.h, 
Intersection.h, 
Split.h, 
DataGenerator.h, 
ReactiveRouting.h

Source file, located directly within the traffic-management folder:
Source.cpp

This will ensure that all paths to external files (such as the .csv files) are correct. From here, you can run the program to view output.
