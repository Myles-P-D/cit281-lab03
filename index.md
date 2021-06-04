# CIT 281 lab 03

## Outcome:

This lab primarily focused on modern javascript syntax using arrays and objects. 
We gained experience creating and deconstructing objects and to make properties. 
We focused on creating the object of a car with metadata about the type of car.
This lab had us create a module with code to gain experince exporting and retrieving data from a code module.
This was also an introduction to arrow function notation which was widely used throughout the remainder of the course.

## Code:
**[Here](https://github.com/Myles-P-D/cit281-lab03/blob/main/lab-03.js)** is a link to the full code and below is a screenshot of exporting a module. 

```javascript
const { reverseString, concatenateString } = require('./lab-03-module.js')

// Declare a specific car object
let car = {
    make: "Ford",
    model: "Mustang",
    vin: "4S3BMHB68B3286050",
    color: "Red",
    year: 2019,
    mileage: 1234,
    used: true,
    owners: [
        { last: "Last1", first: "First1" },
        { last: "Last2", first: "First2" }
    ]
}
```
## Images: 
This is an image from the code module to set it up to export. 
![Module export](https://github.com/Myles-P-D/cit281-lab03/blob/main/moduleExport.png?raw=true "Module Export example")

