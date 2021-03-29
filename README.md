# reactnd-3-redux-managing-state

Lesson 1 - Managing State
You’ll learn techniques to make your state more predictable by moving your state to a central location and establishing strict rules for getting, listening, and updating that state.

Lesson 2 - UI + Redux
You’ll learn to move away from having state live in the DOM by creating a vanilla JavaScript application whose state is managed entirely by Redux.

Lesson 3 - Redux Middleware
You’ll learn to create custom middleware and add it to your Redux store. This middleware will allow you to enhance your store by hooking into and intercepting actions before they reach any reducers.

Lesson 4 - Redux with React
You’ll learn how to add React to a Redux application and have the state of that application be managed by Redux.

Lesson 5 - Asynchronous Redux
You’ll learn to better abstract asynchronous events by creating your own custom Thunk middleware and adding it to your store.

Lesson 6 - react-redux
You’ll learn to leverage the react-redux bindings in order to leverage the benefits of a UI library like React and a state management library like Redux.

Summary: 

React often leverages Redux for more predictable state management via the react-redux bindings. These bindings give us an API that simplifies the most common interactions between React and Redux.

Provider makes it possible for Redux to pass data from the store to any React components that need it. It uses React’s context feature to make this work.

connect() connects a React component to the Redux store. The mapStateToProps() function allows us to specify which state from the store you want passed to your React component, while the mapDispatchToProps() function allows us to bind dispatch to action creators before they ever hit the component.