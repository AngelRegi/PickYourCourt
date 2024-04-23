# Pick Your Court #

![Alt text](public/images/1.jpg)

### Overview ###

Pick Your Court is a user-friendly Court Reservation Web Application designed to cater to students, instructors, and staff at UREC (University Recreation Center). It streamlines the process of reserving courts, allowing members to effortlessly schedule bookings, manage reservations, and access real-time availability information.

### Installation ###
To run the application locally, follow these steps:

1) Install dependencies using **npm install**
2) Start the server by running **node app.js**
Alternatively, you can directly visit **https://pickyourcourt.onrender.com/** without any installation requirements.

### Features ###
1) User Registration and Authentication
2) View List of Courts
3) Reservation : Add/Edit/View/Cancel court bookings
4) Notification System : Send notifications to the user for all the CRUD operations in the reservation module
5)  Feedback System

### Tech Stack ###
We employed the MEN stack - MongoDB, Express, and Node.js - for PickYourCourt's development. Here's a refined overview of our deployment process using Render.com:

## NOTE:                                                                                                             (ONLY FOR DEPLOYMENT- specifically Render.com) ##
Repository Setup: Our codebase is hosted on GitHub, facilitating seamless version control and collaborative efforts.
Build Process: We meticulously installed dependencies and compiled crucial resources using the command: yarn install && npm rebuild bcrypt --build-from-source.
Server Start: We initiated the web server using the command: node app.
Environment Variables: We configured our application and safeguarded sensitive information, such as our MongoDB connection string (MongoURL), using environment variables. Leveraging the mongodb+srv URI scheme ensured secure connections to MongoDB Atlas.

