# React Router v6 Nested Routes Issue with Wildcard Parent Route

This repository demonstrates an uncommon bug encountered when using nested routes in React Router v6, specifically when a parent route includes a wildcard ('*') path.  The issue involves nested routes within the wildcard parent route failing to render as expected. The problem is related to route matching and how the wildcard route interacts with nested route definitions.

## Bug Description:
Nested routes within a parent route with a wildcard path ('*') are not rendered.  The wildcard route seems to capture all requests preventing the nested routes from being matched.

## Solution:
The solution involves a careful consideration of the route structure and possibly restructuring the routes to avoid using a wildcard parent for nested routes.  Avoiding the use of wildcard in this case is the most straightforward solution.