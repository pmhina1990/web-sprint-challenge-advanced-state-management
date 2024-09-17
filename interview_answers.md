# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

It helps with passing down data in component tree without manually using props at every level.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

Actions - is a javascript object thats contains information and the only source of information for the store.

Reducers - are functions that take the current state and action and return the new state and tell the store HOW to do.

Store - it holds the state of the application.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

It allows us to write action creators that return a function instead of an action.
4. What is your favorite state management system you've learned and this sprint? Please explain why!

Redux
 It is easier to use, and majority of devs programmers are using it , UI libary is easy to use.