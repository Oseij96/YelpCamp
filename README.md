# YelpCamp

> A Node.js web application project from the Udemy course - [The Web Developer Bootcamp by Colt Steele](https://www.udemy.com/the-web-developer-bootcamp/)

## Live Demo
https://campconnect.onrender.com/

## Description

YelpCamp is a web application that allows users to discover and share campgrounds from around the world. Users can sign up, log in, and create their own campgrounds, complete with descriptions and images. The app provides basic functionalities for managing campgrounds, comments, and user accounts, ensuring a seamless and enjoyable user experience.

## Features:
### Authentication:
Users can sign up and log in using their username and password.
Admins have the option to sign up using a unique admin code.

### Authorization:
Certain actions are restricted to authenticated users only. Unauthenticated users cannot manage posts or view user profiles.
Users can only edit or delete their own posts and comments, not those created by other users.
Admins have the authority to manage all posts and comments on the platform.

### Campground Management:
Users can create, edit, and delete their campground posts, sharing information about their favorite camping spots.
Campground details can include a title, description, images, and location, which are displayed on the campground's page.
Campground photos can be uploaded to enhance the visual appeal of the campground's page.
The app integrates Google Maps to showcase the precise location of the campgrounds.

### User Account Management:
Users can set up their profile pages during the sign-up process.
Password reset functionality via email confirmation is available to help users regain access to their accounts.

### Flash Messages:
YelpCamp provides responsive and informative flash messages that guide users and provide feedback based on their interactions with the app.

### Responsive Web Design:
The web application is designed to adapt seamlessly to different screen sizes and devices, providing an optimal user experience on both desktop and mobile devices.

## Built with

### Front-end

* [ejs](http://ejs.co/)
* [Bootstrap](https://getbootstrap.com/docs/3.3/)

### Back-end

* [express](https://expressjs.com/)
* [mongoDB](https://www.mongodb.com/)
* [mongoose](http://mongoosejs.com/)
* [async](http://caolan.github.io/async/)
* [crypto](https://nodejs.org/api/crypto.html#crypto_crypto)
* [helmet](https://helmetjs.github.io/)
* [passport](http://www.passportjs.org/)
* [passport-local](https://github.com/jaredhanson/passport-local#passport-local)
* [express-session](https://github.com/expressjs/session#express-session)
* [method-override](https://github.com/expressjs/method-override#method-override)
* [cloudinary](https://cloudinary.com/)
* [geocoder](https://github.com/wyattdanger/geocoder#geocoder)
* [connect-flash](https://github.com/jaredhanson/connect-flash#connect-flash)
