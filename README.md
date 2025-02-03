# React Native useEffect Infinite Loop

This repository demonstrates a common error in React Native involving the `useEffect` hook and how to resolve it. The issue arises when a function is included in the dependency array of `useEffect`, causing an infinite loop due to the function being recreated on every render. The solution involves memoizing the function using `useCallback`. 