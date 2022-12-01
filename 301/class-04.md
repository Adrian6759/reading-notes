# Class 4 Notes

## React Docs - Forms

1. What is a ‘Controlled Component’?
It is an input form element whose value is controlled by React
ref: https://reactjs.org/docs/forms.html

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
You would want to update it as soon as they are entered because that gives you the ability to pass that information to other UI elements.

3. How do we target what the user is entering if we have an event handler on an input field?
You can add a name attribute to it so that you can target a specific element.

## The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?
Because it can help the code look cleaner and it would be shorter than using a conditional statement.

2. Rewrite the following statement using a ternary statement:

var = ((x===y) ? 'true' : 'false';)

if(x===y){
  console.log(true);
} else {  
    console.log(false);
}