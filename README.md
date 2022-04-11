# KARM
A web application for a rental company🚗🚲🛴🛵. 

## Overview
A simple project for University of Palermo.
We had to build a web application to allow the company's customers to order vehicles, such as: cars, motorcycles, bicycles and scooters, independently.
In addition, documentation has been created in the UML standard
### Main Feature
* Login and Logout, made with the use of passport
* Registration, the user enters his / her data, fundamental are age, driving license and credit card
* Password reset, if the user forgets the password, he can retrieve it via his email. A randomly generated code is sent to your email, which you will then have to enter on the site to enter a new password 
* Order a vehicle, the user must complete a form by entering destination, departure, date and time of arrival and departure. In the case of selecting a car, there is the possibility to request a driver. These data are subsequently used to complete the entire booking and therefore determine which cars are closest to the place of departure, which car parks are closest to the place of destination and which driver to contact if requested.
* Manage the ride, during the ride the customer can change the arrival time and destination parking, the program automatically calculates the surcharge that he will have to pay or make a refund. Before the ride and up to 10 minutes before, the vehicle can also be changed. An accident or delay may also be reported
* Notifications, a notification is sent to the driver in the event that it is requested, and through it, he can accept or refuse the ride. Subsequently, a notification is sent to the user who had requested the ride, with the details of their driver
* Admin management, an admin can add and delete vehicles and parking spaces, he can also delete employees and / or add new ones

## Technologies Used
* HTML5
* CSS3
* JavaScript (ES6)
* SCSS
* Git
* GitHub
* Redux
* React JS
* Webpack
* Node JS
* Express JS
* MongoDB
* Google Map's APIs
* Insomnia (for test the DB)  

## Approach Taken
In the development of the project, I first wrote the documentation, highlighting and researching the authors and the actions they had to perform, also defining all the functions that I would have to implement and the data bases. I established the design of the whole application through mockup with photoshop and then made each piece of code. Dividi et impera is the way!🏛️

## Wins and Blockers
### Wins
I really appreciated the realization of the project in all its parts, but above all in the management of the backend
#### Blockers
I was abandoned by my project team and had to do it all by myself in 3 weeks

## Visuals 

### Home
![image](https://user-images.githubusercontent.com/86735558/162752914-1c8dd4db-5386-44bb-b32d-d12908eb14cd.png)


### New prenotation
https://user-images.githubusercontent.com/86735558/162751635-94f003c5-842e-48c9-aed1-fdc60b53d65a.png

### Main Maps with parking site
https://user-images.githubusercontent.com/86735558/162751841-718ce91c-87b9-4714-b924-eb9ba0c7dc79.png

### About us (me) page
https://user-images.githubusercontent.com/86735558/162751719-05575ea6-435f-41ab-8e75-bb96de8bf166.png

### Not found and server error page (the logo rotate)
https://user-images.githubusercontent.com/86735558/162752698-0f9a8e13-15f5-481c-98f2-fb62cd412a25.png

## How to run
### `npm start`
to run the frontend
### `nodemon server`
to run the backend
