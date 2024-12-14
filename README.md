# React useEffect Conditional Rendering Bug

This repository demonstrates a common bug in React applications involving incorrect conditional rendering logic within the `useEffect` hook. The bug occurs when a component's title is only updated when a certain condition is met and not otherwise, resulting in an inconsistent display.

## Bug Description

The provided `MyComponent` uses `useEffect` to update the document title based on a counter value. However, the condition `if (count > 0)` prevents the title from being updated when the count is 0, leading to an unexpected behavior. 

## Solution

The solution corrects the conditional logic to ensure the title is always updated, regardless of the counter value, thus resolving the incorrect rendering issue. This is done by removing the conditional statement from the useEffect function. 
