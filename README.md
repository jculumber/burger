# Eat-Dat-Burger!

* Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.

* Whenever a user submits a burger's name, the app will display the burger on the left side of the page -- waiting to be devoured.

* Each burger in the waiting area also has a `Devour it!` button. When the user clicks it, the burger will move to the right side of the page.

* The app will store every burger in a database, whether devoured or not.

* [Check out this video of the app for a run-through of how it works](burger_demo.mp4).

## Technologies

*   MySQL
*   Node
*   Express
*   Handlebars

This app utilizes a custom ORM and follows the MVC design pattern. It uses Node and MySQL to query and route data in the app, and Handlebars to generate the HTML.

## Installing

After cloning the respository, you will need to install the following Node packages:

In the command line, type:

```
npm install mysql
```
```
npm install express
```
```
npm install express-handlebars
```
```
npm install body-parser
```
