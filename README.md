# YelpCamp

A Node.js web application project from the Udemy course - The Web Developer Bootcamp by Colt Steele

## Live Demo
To see the app in action, go to [YelpCamp](https://stormy-shelf-86103.herokuapp.com/)

## Features
* Authentication:

  * User login with username and password
  * Admin sign-up with admin code

* Authorization:

  * One cannot manage posts and view user profile without being authenticated

  * One cannot edit or delete posts and comments created by other users

  * Admin can manage all posts and comments

* Manage campground posts with basic functionalities:

  * Create, edit and delete posts and comments

  * Upload campground photos

  * Display campground location on Google Maps

  * Search existing campgrounds

* Manage user account with basic functionalities:

  * Profile page setup with sign-up

* Flash messages responding to users' interaction with the app

* Responsive web design

## Custom Enhancements
* Update campground photos when editing campgrounds

* Improve image load time on the landing page using Cloudinary

* Use Helmet to strengthen security

## Getting Started
This app contains API secrets and passwords that have been hidden deliberately, so the app cannot be run with its features on your local machine. However, feel free to clone this repository if necessary.

## Clone or download this repository
``` git clone https://github.com/sh1v98/yelpcamp.git ```
## Install dependencies
``` npm install ```
or

``` yarn install ```
## Comments in code
Some comments in the source code are course notes and therefore might not seem necessary from a developer's point of view.

## Built with
### Front-end
* [ejs](https://ejs.co/)
* [Google Maps APIs](https://developers.google.com/maps/)
* [Bootstrap](https://getbootstrap.com/docs/3.3/)
### Back-end
* [express](https://expressjs.com/)
* [mongoDB](https://www.mongodb.com/)
* [mongoose](https://mongoosejs.com/)
* [async](http://caolan.github.io/async/v3/)
* [crypto](https://nodejs.org/api/crypto.html#crypto_crypto)
* [helmet](https://helmetjs.github.io/)
* [passport](http://www.passportjs.org/)
* [passport-local](https://github.com/jaredhanson/passport-local#passport-local)
* [express-session](https://github.com/expressjs/session#express-session)
* [method-override](https://github.com/expressjs/method-override#method-override)
* [nodemailer](https://nodemailer.com/about/)
* [moment](https://momentjs.com/)
* [cloudinary](https://cloudinary.com/)
* [geocoder](https://github.com/wyattdanger/geocoder#geocoder)
* [connect-flash](https://github.com/jaredhanson/connect-flash#connect-flash)
## Platforms
* [Mongodb Atlas](https://www.mongodb.com/cloud/atlas/)
* [Cloudinary](https://cloudinary.com/)
* [Heroku](https://id.heroku.com/login)
* [Cloud9](https://aws.amazon.com/cloud9/?origin=c9io)

## License

[MIT](LICENSE)
