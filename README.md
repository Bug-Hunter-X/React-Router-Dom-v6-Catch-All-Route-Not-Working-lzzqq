# React Router Dom v6 Catch All Route Not Working

This repository demonstrates a common issue encountered when using the catch-all route (`/*`) in React Router Dom v6.  The catch-all route is intended to handle any unmatched routes, but in certain configurations, it may not function as expected.

The provided code showcases the problem and its solution.  The `bug.js` file shows the incorrect implementation, while `bugSolution.js` provides the corrected code.

## Problem:
The catch-all route does not catch the unmatched routes, resulting in unexpected behavior, often a blank screen or an error.

## Solution:
The solution involves ensuring that the catch-all route is placed correctly within the `Routes` component and properly handles the unmatched routes.