# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Asynchronous code delays a certain action until information from a server can be called and retrieved.
Synchronous code simply operates in real time, no servers needed
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
A function designated with '.on' that listens for a change in state of a given element, then triggering a function when that change takes place
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The Open-Closed principle:  Software should be open for extension, but closed for modification.
This means that software should have its core data encapsulated away from manipulation, but capable of being continually updated to fit new circumstances
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
Functions that rely on information passed to them from other functions down the line.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is a variation of a callback that boils any process down to a simple "true" or "false" value.  You can use a 'try / catch' method to catch errors before they pass through the app.js, allowing you to correct them without crashing your entire application.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
GET: retrieves information from a server
POST: adds information to a server
DELETE: removes information from a server
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application Programming interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The Service, as instructed by the AxiosService
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
To sequester important utilities and assets from user input, preventing unexpected and intolerable modifications to an application
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
200
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
A general error indicating some sort of problem on the server side of your request
```