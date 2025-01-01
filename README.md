# React useEffect Hook Missing Dependency

This example demonstrates a common issue with the React `useEffect` hook: missing dependencies in the dependency array.  The effect runs after every render, even when the state it uses doesn't change.  The correct dependency array is shown in the `bugSolution.js` file.