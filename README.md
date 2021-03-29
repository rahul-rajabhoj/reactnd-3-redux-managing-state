# reactnd-3-redux-managing-state

Summary
React often leverages Redux for more predictable state management via the react-redux bindings. These bindings give us an API that simplifies the most common interactions between React and Redux.

Provider makes it possible for Redux to pass data from the store to any React components that need it. It uses React’s context feature to make this work.

connect() connects a React component to the Redux store. The mapStateToProps() function allows us to specify which state from the store you want passed to your React component, while the mapDispatchToProps() function allows us to bind dispatch to action creators before they ever hit the component.