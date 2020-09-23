# README

## Introduction:

Create an application that has all the benefits of a non API only Rails application, without the limitations and vendor lock-in of a third party service like Firebase.

For this application we are going to build both the front-end and back-end within a single Rails application. However, we're only going to load React on a specific part of a specific view.

## Considerations

We will be deviating from a traditional Rails application by replacing a specific view with a React application. This means that we will no longer be able to use some of the features we take for granted in a Rails application, like form helpers or flash notices. Below are some often overlooked features that we will be responsible for.

* API authorization

* API versioning

* Setting HTTP status codes

* Form validation on the front-end

*  Handling errors

* Debouncing requests

* CSRF Countermeasures
