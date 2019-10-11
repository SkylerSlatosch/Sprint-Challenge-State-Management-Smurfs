1. What problem does the context API help solve?
Context API helps solve prop-drilling.
1. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
Actions are payloads of information that send data from your application to your store. They are the only source of information for the store.
Reducers specify how the application's state changes in response to actions sent to the store.
The Store Holds application state, Allows access to state via getState(), and Allows state to be updated via dispatch(action). 
When your Redux is a single source of truth, it means that the only way to change your data in UI is to dispatch redux action which will change state within redux reducer.
1. What is the difference between Application state and Component state? When would be a good time to use one over the other?
Application state can be passed to all components, used well when dealing with a big application.
component state is state held in the components, used well with smaller applications.
1. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?
redux thunk allows us to run async actions. so then our action creators can have multiple dispatches
1. What is your favorite state management system you've learned and this sprint? Please explain why!
Redux, I want to work with major applications like twitter/instagram etc. So learning this early is essential!
