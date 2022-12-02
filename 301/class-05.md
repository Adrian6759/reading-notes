# Class 5 Notes

## React Docs - Thinking in React

1. What is the single responsibility principle and how does it apply to components?
It is the idea that a component should only do one thing and it it ends up having grown too much, it should be broken up into small subcomponents.

2. What does it mean to build a ‘static’ version of your application?
A static version would be an application that didn't have interactivity.

3. Once you have a static application, what do you need to add?
Reusable components

4. What are the three questions you can ask to determine if something is state?
Is it passed in from a parent via props?
Does it remain unchanged over time?
Can you compute it based on any other state or props in your component?
<!-- pulled from https://reactjs.org/docs/thinking-in-react.html -->
5. How can you identify where state needs to live?
Whatever component that's in the top of the hierarchy should own state.

## Higher-Order Functions

1. What is a “higher-order function”?
It is a function that operates on other functions by taking in arguments or returning arguments.

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
It is returning true if the value of m is greater than n.

3. Explain how either map or reduce operates, with regards to higher-order functions.
The map function is able to transform an array by using a function to get the desired result.
