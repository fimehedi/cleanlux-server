# Cleanlux API

Cleanlux API is a Node Application. It's hosted on Heroku.

## APIs

[https://cleanlux.herokuapp.com/[api]](https://cleanlux.herokuapp.com/)

* GET - /services - For all services
* GET - /service/:id - For a single service
* GET - /bookings?email=email - Specific user bookings (if user is admin it will return all bookings)
* GET - /check-admin?email=email - Check loggedIn user admin or not
* GET - /all-admins - For all admins list
* GET - /reviews - For all reviews.
* POST - /add-service - For add a Service
* POST - /add-review - For new booking
* POST - /add-booking - For new review
* POST - /make-admin - For add a admin
* DELETE - /delete-service/:id - Delete a single service
* PATCH - /change-booking-status/:id - For Changing booking status

## Technology Usage

* Node JS
* Express JS
* MongoDB
