## Forms and Inputs
- HTML form elements work a little bit differently from other DOM elements in React, because form elements naturally keep some internal state. 
- Think of React inputs as stateful child components.

## Props
“Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another. Furthermore, props data is read-only, which means that data coming from the parent should not be changed by child components.

## One Way Data flow
State can only be passed from parent component to a child component through the use of props. This enforces the idea of one way data flow. One way data flow is a way of describing that state can only be passed down the component tree (not up). If a child wants to pass some data to a parent, the parent can pass a function to the child through props and the child may invoke that function and pass it data for the parent to manage.

![img](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.techdiagonal.com%2Freactjs_courses%2Fbeginner%2Freactjs-component-state%2F&psig=AOvVaw2y1un76fMvmeL90QE4TLBq&ust=1593509087749000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCKDC2YvapuoCFQAAAAAdAAAAABAD)
