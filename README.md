# React useEffect Hook Bug

This repository demonstrates a common bug in React applications related to the `useEffect` hook and its dependency array.

The `bug.js` file contains a component with an `useEffect` hook that has an empty dependency array (`[]`). This means the effect will only run once when the component mounts.  However, the intention is likely to log the count each time it changes.

The `bugSolution.js` file shows the corrected code, including the `count` variable in the dependency array.