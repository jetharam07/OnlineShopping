# OnlineShopping Mern Stack Project
Using React, Express, Node.js, bootstrap, MongoDB (Database).
View from this link:https://onlineshopping-aizl.onrender.com


# About this project:
This is a mern stack project. Mongoose DB database is used in it which is no SQL database. Express JS and Node JS have been used. React JS is used in the frontend. Express JS and node js is the libraries of Javascript. These have been used as backend. All the files of frontend are inside the client folder and while deploying it, I have build backend and front end in one file, then added it to github repository and deployed it on render.com website.
It has the option of register, login and forget password for the users. It has a user dashboard and admin dashboard. The admin can add, delete and update products according to him. He can view the order status of the users on his dashboard and can do processing, shift, deliver, cancel etc. Inside the user dashboard, the user can see his email, his orders and other things. There is a  filter option in which you can filter the products according to the price and category. Payment method integration is also available in this project. 

# Below are mentioned some important files and tools which have been used in this project.

** Client / public (Frontend): Inside the public folder, there is an index.html file and an images folder. The js script and css links are linked inside this HTML file and all the images to be used in the project are inside the images folder.

Src Folder: Inside the src folder, there are Components, Context, Pages, Styles folders which contain the layout of the website, header, footer and all the pages. There is a CSS folder which contains different CSS files according to the different aspects of the entire website. All components are built with React JS.

package.json: Inside this, dependencies have been installed as per the requirement of the website.

** (Backend) / controllers: Inside the controllers folder, all the APIs have been created as per the requirement of this app. Express JS has been used in this. API has been created for updating or deleting categories and for the complete functionality of admin dashboard and user dashboard, through which integration has been done as per the requirement at various places inside the client.

middlewares: When a user sends a request, middle ware works in between going to the server. There are many advantages of using middleware. It is used for authentication in login. it helps in error handling.

models: In this, a model has been created about the type of data to be stored and used for the order, product,categories and user.

routes: The path is created with the help of routes which is used when integrated in the frontend.

.env: All secret keys, mongo url and payment related keys are kept inside the environment variable file. and this file remains private.

package.json: Backend related dependencies is installed in this file.
