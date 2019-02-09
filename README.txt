# MyStoreFront

This project was generated with [Angular CLI](https://github.com/angular/angular-cli)So Angular version 6.1.2.

# Installation
After you have downloaded the file from git and extracted the zip file, you will need to open a command line editor and change to the directory structure to where you extracted the project to.
I assume you have node and npm already installed.
Now run 'npm install' to create the required node modules for the project.

# Additional Libraries
I did not include material or flex-layout, nor bootstrap or jquery.
Since Angular is such a big library already I wanted to keep it as basic as I could.

# Documentation
I believe in pictures, so have added a basic UML class diagram within the document folder, within the main structure of the project. I did this at the start, so not 100% correctly updated, but it does give an idea of the components and how they interface with each other.

# CSS Grid
I did make use of CSS Grid. For training purposes for myself mostly. This is supposed  to be supported by most of the latest browsers. I have added code within the category component to check if the browser allows for the use of the grid. However within the cart component I did not get around to adding seperate code for if the grid is not supported. Only because of time constraits. 

## Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding
The main components
Category
Cart  - Include a service
Product - Include a service (To extract data from product.json file)
Models - Data structures
Common - Include 2 components (Item for the product items and counter)

## Things not done because of time constraints
Apart from the Jasmine testing files I also did not include the 2 popup screens. I really just did not have the time to build in al 5 screens. I therefore decided to start by building the 3 main screens (Caegory, cart and product) and only if time permits would I add in the 2 popup functions. Unfortunately I did not get time to finish the popups, but believe you can still get a good idea of my coding style.

## Running unit tests

Normally you would be able to run the unit test using Karma and Jasmine. 
In Absa we only unit tested our java code using jUnit and never used Jasmine or Karma to perform unit testing on the front end. I really wanted to build in at least a unit test for one component, but since I needed to first at least go through a basic training module on Jasmine (taking a day or 2 ) I was not able to do so in the given time frame. So I am sad to say that ng test will not work correctly. I do understand the value something like this can add.

