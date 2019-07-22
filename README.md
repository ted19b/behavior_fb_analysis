# behavior_fb_analysis
This application allows you to perform a personality test of a user of the Facebook platform.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 
See deployment for notes on how to deploy the project on a live system.

### Prerequisites

* Install python (Version >= 3.6)

* Install Pycharm, Visual Basic Code (or use Terminal)

### Installing

Clone the project and install all the necessary dependencies for the project.

> git clone https://github.com/ted19b/behavior_fb_analysis.git

> pip install -r requirements.txt

### Start the application

> python3 run.py

The application runs at port 5000. 

To check that the application is working correctly, just go to this address in the browser or in postman.

http://localhost:5000/

You should see the following message 

    Hello world from flask
   
### package and dependency management

Dependency management helps manage all the libraries required to make an application work. 
Itâ€™s incredibly beneficial when youâ€™re dealing with complex projects and in a multi-environment. 
Dependency management also helps to keep track, update libraries faster and easier, 
as well as solve the problem then one package will depend on another package.

After updating the project and installing new libraries in our virtual environment. 
These dependencies should also be added to the Requirements.txt file so that others 
can install the project's new libraries with relative ease and thus obtain a project that works 
well enough easily.

To generate a requirements.txt file you can run 

    pipreqs /your_project/path 
    
If Requirements.txt already exists, use --force to overwrite it 
