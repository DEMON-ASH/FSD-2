## Learning Outcomes

1. Understand lazy loading and its role in frontend performance optimization
2. Implement lazy loading in React using `React.lazy()` and `Suspense`
3. Apply lazy loading to route-based components with `react-router-dom`
4. Optimize initial bundle size to improve application load time
5. Organize a scalable React project structure for better performance

---

## What is Lazy Loading?

Lazy loading is a performance optimization technique where components are **loaded only when needed**, instead of loading the entire application upfront.

In React, lazy loading helps to:

* Minimize the initial bundle size
* Speed up the first page load
* Improve user experience in large applications

React supports lazy loading using:

* `React.lazy()`
* `Suspense`

---

## How Lazy Loading Works in React

* Components are split into separate bundles
* Bundles are loaded **only when the component or route is accessed**
* A fallback UI (such as a loader or placeholder) is displayed during loading.
