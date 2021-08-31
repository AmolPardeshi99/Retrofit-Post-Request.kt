# Retrofit-Post-Request.kt
POST Request Submitted
Problem
Design an Android app which makes a POST request with the below requirements

Given

Request Type : POST
BASE URL = https://jsonplaceholder.typicode.com/
END Point = /posts
Sample Request Body

{
    "email": "eve.holt@reqres.in",
    "password": "pisto1l",
    "title" : "Welcome to Post Api",
    "requestType" : "POST"
}
Response Body

Check the response body for the given sample request on postman and generate respective POJO classes.

Requirements

The screen must have 4 edittext which accepts email, password, title, requestType from the user and a button, on click of which the POST request is made.
Once the response comes from the server, open a new activity and pass the required parameters to second activity ( title, email, requestType, id) and populate the data in 4 text views.
Generate separate pojo classes for Response and Request Body.
Show progress bar if necessary.
