## What is the single responsibility principle and how does it apply to components?
this principle means that every component should have one function to do, if the component has more than one function then make subcomponents as children to it, every child will do one function.

## What does it mean to build a ‘static’ version of your application?
that is means you will not be able to change your data. in another meaning; you will not use state into your components.

## What are the three questions you can ask to determine if something is state?
if is it able to move from its component(parent to child)? if not, maybe it is not state. if its value still fixed over time? if yes, it is not state. if it depends on other states and props? if yes, it is not state.

## Once you have a static application, what do you need to add?
you have to make it dynamic, by using states into each component that needs to change its data.

## How can you identify where state needs to live?
based on where it will be used and rendered? sometimes you have to pass this state from its component to another to render it there. Things I want to know more about classes in ES6.
