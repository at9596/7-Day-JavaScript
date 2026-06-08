# 🚀 Week 2: Modern Frontend & Architecture Separation

## 🎯 Goal

Master frontend architecture concepts and confidently explain how modern web applications work under the hood.

---

## 📅 7-Day JavaScript & Frontend Tracker

### Progress

* [ ] Day 1
* [ ] Day 2
* [ ] Day 3
* [ ] Day 4
* [ ] Day 5
* [ ] Day 6
* [ ] Day 7

---

## Day 1: Closures & Scope

### Topics

* Lexical Scope
* Closures
* Function Scope vs Block Scope
* Practical Closure Use Cases

### Tasks

* [ ] Solve 3 closure-based coding problems
* [ ] Create a counter using closures
* [ ] Explain closures in your own words

### Notes

```
A closure allows a function to remember variables
from its outer scope even after the outer function
has finished execution.
```

---

## Day 2: Hoisting & Execution Context

### Topics

* Execution Context
* Hoisting
* var vs let vs const
* Temporal Dead Zone (TDZ)

### Tasks

* [ ] Predict output of hoisting examples
* [ ] Create notes on TDZ
* [ ] Solve 3 interview questions

### Notes

```
JavaScript moves declarations to memory during
the creation phase before execution begins.
```

---

## Day 3: Event Loop & Async JavaScript

### Topics

* Call Stack
* Web APIs
* Callback Queue
* Microtasks vs Macrotasks
* Promises
* Async/Await

### Tasks

* [ ] Draw Event Loop diagram
* [ ] Solve 5 async output questions
* [ ] Build a Promise-based API call example

### Notes

```
Promises are placed in the microtask queue,
which gets higher priority than the callback queue.
```

---

## Day 4: Event Delegation & DOM

### Topics

* Event Bubbling
* Event Capturing
* Event Delegation
* DOM Traversal

### Tasks

* [ ] Build dynamic list with event delegation
* [ ] Explain bubbling vs capturing
* [ ] Practice DOM manipulation

### Notes

```
Event delegation reduces memory usage by attaching
a single listener to a parent element.
```

---

## Day 5: React Fundamentals

### Topics

* Components
* JSX
* Props
* State
* State Updates

### Tasks

* [ ] Build a Todo App
* [ ] Create reusable components
* [ ] Explain Props vs State

### Interview Explanation

**State:** Internal mutable data managed by a component.

**Props:** Read-only data passed from parent to child components.

---

## Day 6: Virtual DOM & Component Lifecycle

### Topics

* Real DOM
* Virtual DOM
* Reconciliation
* Lifecycle Methods
* Hooks

### Tasks

* [ ] Learn React rendering process
* [ ] Practice useEffect
* [ ] Explain Virtual DOM

### Interview Answer

❌ Bad:

```
Virtual DOM makes React fast.
```

✅ Good:

```
Direct DOM manipulation is expensive.
The Virtual DOM creates an in-memory representation
of the UI and calculates the minimal changes required.
React batches updates and applies only the necessary
DOM operations, reducing reflows and repaints.
```

---

## Day 7: SPA Architecture & Optimization

### Topics

* SPA vs Traditional Web Apps
* REST APIs
* GraphQL
* Memoization
* Lazy Loading
* Code Splitting

### Tasks

* [ ] Implement lazy loading
* [ ] Learn React.memo
* [ ] Compare REST vs GraphQL
* [ ] Write SPA architecture notes

### Interview Answer

#### Why SPAs use REST/GraphQL?

```
SPAs separate frontend and backend concerns.

The frontend handles rendering and user interactions,
while the backend exposes data through APIs.

This architecture improves scalability, enables
independent deployments, supports mobile clients,
and reduces full-page reloads, resulting in a
more responsive user experience.
```

---

