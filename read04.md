# React and Forms

## What is a ‘Controlled Component’?

Controlled components render form elements and control them by storing the form data in the component's state.

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

When React is in charge of preserving and setting its state, both will function. It is possible to keep the state up-to-date by altering the input value, but this requires that the input be changed first.

## How do we target what the user is entering if we have an event handler on an input field?

after adding the setState on the ChangeInput function, we can target the event as event.target.value

----------------

# The Conditional (Ternary) Operator Explained

## Why would we use a ternary operator?


A ternary operator allows you to assign one value to the variable if the condition is true, and another value if the condition is false. ... A ternary operator makes the assignment of a value to a variable easier to see, because it's contained on a single line instead of an if else block.

```
if(x===y){
    console.log(true);
  }else {
    console.log(false);
  }
  ```
  
```
  console.log(x===y ? 'true' : 'false')
```