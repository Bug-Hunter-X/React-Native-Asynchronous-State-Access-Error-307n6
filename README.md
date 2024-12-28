# React Native Asynchronous State Access

This repository demonstrates a common error in React Native applications: attempting to access a state variable before it has been initialized, often in asynchronous operations like API calls. The error occurs because the asynchronous task to update state hasn't completed by the time the variable is accessed. 

The `bug.js` file showcases the incorrect code that leads to this error. The `bugSolution.js` file provides a solution using optional chaining and useEffect's second parameter to handle the asynchronous nature of the state update.  This issue highlights the importance of understanding asynchronous programming when working with React Native and state management.