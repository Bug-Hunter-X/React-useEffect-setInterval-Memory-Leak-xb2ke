# React useEffect setInterval Memory Leak

This repository demonstrates a common mistake when using the `useEffect` hook in React with `setInterval`.  Forgetting to return a cleanup function from `useEffect` can lead to memory leaks and unexpected behavior.  The provided solution shows how to correctly implement `setInterval` within `useEffect` to avoid such issues.