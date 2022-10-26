# Class 3 Notes

Ordered and unordered liat are important because it is very useful to be able to order lists. It can help make the content look cleaner.
The box model is important because it is very useful knowing how to format from our margins to our content.
Arrays, operators and expressions, coinditionals and loops are all important because they help improve the interactivity of our websites.

#### Learn HTML
1. When should you use an unordered list in your HTML document?
You should use an unordered list when you need to list items that don't need to be in any particular order. 

2. How do you change the bullet style of unordered list items?
You can use the list-style-type property in CSS to change them.

3. When should you use an ordered list vs an unorder list in your HTML document?
You should use an ordered list when the order of items matters such as ranking a list and also if you needed something to be in numerical order.

4. Describe two ways you can change the numbers on list items provided by an ordered list?
You can change it by putting "type=" and using i for roman numerals. Another way is to using "start=" and using the number you would like to start on.

#### Learn CSS
1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
Margin and Content used to be real tight. Some would say inseparable. Then one day they got into a huge fight. They let this one swell lady named Padding get between them. Both were still close to Padding and maintained a close relationship with her until Border came along and came in between Margin and Padding. Padding discovered that she loves Content and Content would always within Padding's heart. Border saw this love and decided to prtotect that love. Border loves both Padding and Content and does it's best to block out Margin. 

2. List and describe the four parts of an HTML elements box as referred to by the box model.
The box model includes the margin, border, padding, and content. The margin is in the outermotst layer of this box and contains the border, padding, and content within it. The border wraps padding and content within it. The padding wraps around the content. The content is in the middle of all of these.

#### Learn JS

1. What data types can you store inside of an Array?
Strings, Numbers, Objects, and Arrays can be stored inside an array.

2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
It is a valid array and you can access values stores by typing 
console.log(people[]); and adding an index into the brackets. The index will be the whatever number assigned to it was.

 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

3. List five shorthand operators for assignment in javascript and describe what they do.

* x=f() Assigns the value of f() to x
* x += f() Assigns the value of x + f() to x
* x -= f() Assigns the value of x - f() to x
* x *= f() Assigns the value of x * f() to x
* x /= f() Assigns the value of x / f() to x

4. Read the code below and evaluate the last expression and explain what the result would be and why.
The result would be 10 because 'dog' + false evaluates to null or 0.
10+0=10

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.
Conditional statements should be used when you have a cetain condition you want met. They can be used for a website that needs to verify age. So if you provide me with your age and it is above 21, but if you are not of age it will deny you access to the site.

6. Give an example of when a Loop is useful in JavaScript.
A loop is useful when you want a user to give you a valid answer. You can keep looping until they give you what you are asking for.

# Things I want to know more about
