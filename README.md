# JavaScript Objects and Methods Practice

## Description

This project contains a collection of JavaScript exercises focused on object manipulation, object methods, property management, object iteration, and data modeling.

The project demonstrates how to create objects, define methods, evaluate student performance, manage vehicle information, work with enumerable and non-enumerable properties, and clone objects using the Spread Operator.

## Features

### Student Performance System

* Creates a person object containing:

  * Name
  * Grades
* Calculates the student's average grade.
* Classifies academic performance into categories:

  * Excellent Performance
  * Good Performance
  * Regular Performance
  * Insufficient Performance

### Vehicle Information Management

* Creates a vehicle object containing:

  * Brand
  * Model
  * Year
  * Color

* Displays all vehicle properties using `for...in`.

### Dynamic Property Management

* Adds new properties to an existing object.
* Updates and displays modified object information.

### Enumerable and Non-Enumerable Properties

* Creates hidden properties using `Object.defineProperty()`.
* Explores enumerable and non-enumerable behavior.
* Retrieves visible keys using `Object.keys()`.

### Object Cloning with Spread Operator

* Creates a new vehicle object.
* Combines object properties using the Spread Operator (`...`).
* Generates an updated object with additional details.
* Modifies cloned object properties independently.

## Skills Demonstrated

* JavaScript fundamentals
* Object creation and manipulation
* Object methods
* Property access
* Dynamic property creation
* Template literals
* Conditional statements
* Arrays inside objects
* `for...in` loops
* `Object.keys()`
* `Object.defineProperty()`
* Enumerable vs non-enumerable properties
* Spread Operator (`...`)
* Object cloning
* Data modeling
* Problem-solving and logical thinking

## Technologies Used

* JavaScript
* HTML5
* CSS3

## Learning Objectives

This project was created to practice:

* Creating reusable objects
* Defining object methods
* Working with object properties
* Iterating through object data
* Managing hidden properties
* Cloning and extending objects
* Applying object-oriented programming concepts

## Project Structure

```text
├── index.html
├── style.css
├── script.js
└── README.md
```

### File Description

* **index.html** — Main webpage structure.
* **style.css** — Styling and visual customization.
* **script.js** — Contains all object-related exercises and implementations.
* **README.md** — Project documentation.

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/javascript-object-methods-practice.git
```

2. Open the project folder.

3. Open the `index.html` file in your browser.

4. Open the browser's Developer Console to view the outputs.

## Concepts Covered

### Object Methods

```javascript
person.calculateAverageGrades();
person.classifyPerformance();
```

### Property Iteration

```javascript
for (let property in car) {
  console.log(property);
}
```

### Hidden Properties

```javascript
Object.defineProperty(car, 'licensePlate', {
  value: 'ABC-1234',
  enumerable: false
});
```

### Object Cloning

```javascript
const updatedCar = {
  ...car,
  ...newCar
};
```

## Academic Purpose

This project was developed as part of JavaScript programming practice focused on objects, methods, property management, iteration techniques, and object-oriented programming fundamentals.


Computer Engineering Student

