# Counter Vanilla

## About this Project
This is simple Redux sample.  
This project don't use react.

## implementation
I am referring to the following project.  
https://github.com/reactjs/redux/tree/master/examples/counter-vanilla

I implemete Redux objects.
- Reducer
- Store


1. If click increment or decrement button, send Action to the Store by calling dispath().
2. Reducer return the State according to the Action.
3. If change the State, render() is executed.
4. Using subscribe(), if the State is changed, render() is called.
5. Get the State and directly rewrites the value by manipulating DOM on the render().

## Precondition
None.  
Just using browder.

## How to start application
Just open index.html by browser
