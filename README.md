# React Router v6 Catch-All Route Issue

This repository demonstrates a common issue with catch-all routes (`/*`) in React Router v6. The catch-all route unintentionally overrides other routes, causing unexpected behavior. 

The problem arises when the catch-all route is placed after more specific routes.  Even with correct path matching, the catch-all route always intercepts, preventing access to other defined paths.

The solution involves reordering the routes, ensuring more specific paths are checked before the catch-all route.