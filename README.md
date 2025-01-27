# Incorrect State Update in React's useState Hook
This repository demonstrates a common error in React when working with the `useState` hook: directly modifying the state variable instead of using the setter function.  The `bug.js` file shows the problematic code, while `bugSolution.js` provides the correct solution.

The error arises from directly assigning a new value to the `count` variable (`count = count + 1;`).  This does not trigger a re-render.  React's state management requires the use of the setter function provided by the `useState` hook to update the state correctly.