# Getir Node.js Bootcamp Graduation Project

Thanks to express-async-errors package, when the app come across any async error, it is automatically passed to error handler without need of next() method. It makes the code very clean. There is no need to catch the async-errors.

Error handling is done by custom error class which extended default Error class. When error is needed to send, its type and status code is ready , only must write error message.

## Crucial Points

- Delivering a Working RESTful API.
- Clean and Production Ready Code
- Error Handling
- Comments and Documentation
- Unit and/or Integration Tests (Jest is preferable but Mocha also works)
- Avoid Over Engineering
