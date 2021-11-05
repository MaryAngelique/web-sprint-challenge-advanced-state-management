# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?
    The Context API can be used to share data with multiple components and enables you to exchange unique details and assists in solving prop-drilling

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
    Actions carry payloads of information from applications to store
    Reducers are pure functions that takes an action of the previous state and returns the new state
    A store is an immutable object tree which holds the application's state 

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?
    Redux-thunk is middleware which allows the returning of functions not just actions
    The 'action-creator" is changed by returning a function that performs a conditional dispatch    

4. What is your favorite state management system you've learned and this sprint? Please explain why!
    N/A