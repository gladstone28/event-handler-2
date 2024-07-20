link to source:

/c/Users/glads/Downloads/props-put-an-event-handler-in-a-function-component/event-handler


link to codecademy lesson:

https://www.codecademy.com/courses/react-101/lessons/this-props/exercises/event-handler-component-class


link to AI:

https://chatgpt.com/c/14426d70-9262-425d-95e0-ff40af8c4e99


### PROPS

**Put an Event Handler in a Function Component**

You can, and often will, pass functions as props. It is especially common to pass event handler functions.

In the next exercise, we will pass an event handler function as a prop. However, we have to define an event handler before we can pass one anywhere. In this exercise, we will define an event handler function.

How do we define an event handler in React?

We define an event handler as a method on the function component!

Take a look at the Example.js file in the code editor. On lines 4 through 8, an event handler method is defined. On line 10, that event handler method is attached to an event (a click event, in this case).

### Instructions

Checkpoint 1 Passed

1. Select Talker.js.

Here we have a function named talk() that alerts ten thousand “blah”s to your screen. You will eventually use talk() as an event handler.

There’s a problem: talk is defined outside of the Talker component.

Rewrite talk(), so that it is a method defined inside the Talker component. Look at Example.js if you get stuck!

Once you’re done, delete the original talk() function before clicking Run.

**Hint**

The talk() function should be inside the Talker component definition, but before the return statement.

