# Class 10 Notes

## Understanding the JavaScript Call Stack

1. What is a ‘call’?
When something is pushed into the stack to perform it's assigned task
2. How many ‘calls’ can happen at once?
One at a time from top to bottom.
3. What does LIFO mean?
Last In First Out means that whatever gets put in last will come out first.
4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

function functionOne(){
  console.log('Stack Em Up');
}

function functionTwo(){
  firstFunction();
}
functionTwo();
5. What causes a Stack Overflow?
A stack overflow is caused by recursive functions and happens when the maximum call size has been reached.

## JavaScript error messages

1. What is a ‘reference error’?
When a undeclared variable is trying to be used.
2. What is a ‘syntax error’?
When you try to use the wrong "punctutation" is code.
3. What is a ‘range error’?
When an object with some sort of length is improperly given an invalid value.
4. What is a ‘type error’?
When the type of data you are using does not work with what you qare trying to do.
5. What is a breakpoint?
The breakpoint is a stop in your code that is used to help debug.
6. What does the word ‘debugger’ do in your code?
It will make a breakpoint in your code wherever you use a debugger statement.
