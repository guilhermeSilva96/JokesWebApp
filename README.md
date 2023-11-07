# Random Joke Generator

![JokesWebApp](https://github.com/guilhermeSilva96/JokesWebApp/assets/139381851/3052e864-a0d0-4822-ad6a-893d41d2a967)


This is a simple web application that generates random jokes using the JokeAPI. In this README, we'll explore the JavaScript mechanics and fundamentals used in the code.

## JavaScript Mechanics and Fundamentals

1. **DOM Manipulation:** The code interacts with the Document Object Model (DOM) using `document.getElementById` to get references to HTML elements by their IDs (e.g., `jokeContainer` and `btn`). It then updates the content of the `jokeContainer` and handles button clicks using event listeners. This demonstrates DOM manipulation, a crucial part of web development.

2. **Asynchronous Fetch:** The `fetch` API is used to make an asynchronous HTTP request to the JokeAPI. This showcases how to work with external data sources and handle asynchronous operations in JavaScript.

3. **Promise Chain:** Promises are used to handle the response from the API. The code uses the `then` method to chain promises, demonstrating the use of promise-based asynchronous programming.

4. **Arrow Functions:** Arrow functions are employed in defining the `getJoke` function. This is a feature of ES6 that provides a concise syntax for writing functions.

5. **ClassList Manipulation:** The code uses `classList` to add and remove the "fade" class on the `jokeContainer` element, creating a fade-in effect. This demonstrates how to work with CSS classes in JavaScript.

## Getting Started

To run this application locally, you can simply open the HTML file in a web browser. No additional setup is required. The random joke will be displayed when you click the "Get Joke" button.
