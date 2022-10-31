# Class 6 Notes

### Javascript Objects

1. How would you describe an object to a non-technical friend you grew up with?
It's a way of grouping related items together. It's kind of like organizing items in your cabinets that contain like items. This makes it more efficent for you when you need to use them because you know where they are and what they are used for.

2. What are some advantages to creating object literals?
Object literals are more efficent that just objects. They also help keep your code cleaner. Makes it easier to scan and debug code.

3. How do objects differ from arrays?
Objects are able to store variables and fucntions whereas arrays store values.

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
You can use bracket notation when dot notation isn't an option to retrieve a value. The only tiem this would be true is iif the property name is located in a variable.

5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?
It refers to the code directly next to it. In this case it's name and age. The advantage to using this is that it allows you to use the same method definition for objects.
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

### Introduction To The DOM

1. What is the DOM?
The DOM is a programming interface that allows us to see the structure and content of a website to allow us to more easily update and make changes to it.

2. Briefly describe the relationship between the DOM and JavaScript.
Javascript uses the DOM in order to be able to interact with web pages and documents. 

### Things I want to know more about

