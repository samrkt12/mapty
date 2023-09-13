# Mapty - Map your Workouts

**Note**: This project was developed during my learning phase as part of my
journey to improve my web development skills.

## Description

Mapty is a web application that allows users to log and track their workouts on
an interactive map. It provides a convenient way to record various workout
activities, including running and cycling, while visualizing them on a map.

## Features

-   **Workout Logging**: Record your workouts, including details like distance,
    duration, cadence (for running), and elevation gain (for cycling).

-   **Interactive Map**: View your workouts on an interactive map, making it
    easy to visualize your fitness journey.

-   **Two Workout Types**: Mapty supports two main workout types: running and
    cycling. Each workout type has its own set of metrics and calculations.

-   **Data Validation**: Input data is validated to ensure that only valid and
    positive numbers are accepted, providing a reliable and user-friendly
    experience.

## Learning Experience

### Object-Oriented Programming (OOP)

One of the key highlights of the Mapty app is the use of Object-Oriented
Programming (OOP) principles. Classes have been employed to structure and
organize the code effectively. Here's how OOP has been utilized:

-   **Class Hierarchy**: We've created a class hierarchy with a base `Workout`
    class and two child classes, `Running` and `Cycling`, to represent different
    workout types. This promotes code reusability and consistency.

-   **Inheritance**: The child classes inherit common properties and methods
    from the parent `Workout` class, reducing code duplication.

-   **Encapsulation**: We've encapsulated data and methods within each class,
    ensuring that each class manages its own state and behavior independently.

### Learning and Growth

While developing Mapty, I've gained valuable experience in the following areas:

-   **JavaScript**: I've deepened my understanding of JavaScript, especially ES6
    features like classes and modules.

-   **Leaflet.js**: I've learned how to integrate Leaflet.js, a popular mapping
    library, into web applications.

-   **OOP Principles**: I've applied OOP principles to create a well-structured
    and maintainable codebase.

## Code Structure

The code for the Mapty app is structured as follows:

-   HTML
-   CSS
-   JavaScript
-   Leaflet.js (for map integration)
-   Object-Oriented Programming (OOP) principles and classes

## Getting Started

To run Mapty locally, follow these steps:

1. Clone this repository to your local machine.
2. Open the `index.html` file in your web browser.

## Acknowledgments

I'd like to express my gratitude to the open-source community and the developers
of Leaflet.js for providing excellent tools and resources for web mapping.

Happy tracking and stay fit!
