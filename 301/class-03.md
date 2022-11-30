# Class 3 Notes

This topic is important because it provides us with tools to be able to interact with react a little better.

### React Docs - lists and keys

1. What does .map() return?
It returns an array after it has been passed through a function.
2. If I want to loop through an array and display each value in 
JSX, how do I do that in React?
You would need to wrap it it curly braces.
3. Each list item needs a unique ____.
key
4. What is the purpose of a key?
Keys help react to keep track of items that have been changed, added or removed. They help react stay efficient.

### The Spread Operator

1. What is the spread operator?
It is a special type of syntax that shows up as three dots. It allows us to expand an iterable object into the list of arguments.
2. List 4 things that the spread operator can do.
It can copy an array, concatentate or combine arrays, it can be used to add an item to a list, and even combine objects.
3. Give an example of using the spread operator to combine two arrays.
const numArray = [1, 2, 3]
const numTwoArray = [4, 5, 6]
const combinedArray = [...numArray, ...numTwoArray]
combinedArray = [1, 2, 3, 4, 5, 6]

4. Give an example of using the spread operator to add a new item to an array.
const twoNum = [2, 3]
const threeNumPlus = [4, 5, 6, ...twoNum]

5. Give an example of using the spread operator to combine two objects into one.
const nameOne = {hello: Adrian}
const nameTwo = {hello: Aiden}
const nameThree = {...objectOne, ...objectTwo, hello: Jessica}

### Videos

How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?
Create an increment function
2. In your own words, what does the increment function do?
It creates the change of an element from another component.
3. How can you pass a method from a parent component into a child component?
By using props
4. How does the child component invoke a method that was passed to it from a parent component?
By using increment
