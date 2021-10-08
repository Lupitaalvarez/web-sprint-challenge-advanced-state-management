# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

- The API can help keep your state relatively clean.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

- Actions passes information into the store. Reducers are used to change state, and the store is an object that holds the state.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

- Since the Redux action -> reducer flow is synchronous, we will use Redux Thunk to make the flow asynchronous and make API calls from our action creators. Redux Middleware intercepts the normal Redux flow and can make a call before actions make it to the reducer.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

- 