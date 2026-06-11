# 🚀 Modern Frontend & Architecture Separation

## 🎯 Goal

Master frontend architecture concepts and confidently explain how modern web applications work under the hood.

---

## 📅 7-Day JavaScript & Frontend Tracker

### Progress

* [x] ~~Day 1~~
* [x] Day 2
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

* [x] ~~Solve 3 closure-based coding problems~~
* [x] ~~Create a counter using closures~~
* [x] ~~Explain closures in your own words~~

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

* [x] ~~Predict output of hoisting examples~~
* [x] ~~Create notes on TDZ~~
* [x] ~~Solve 3 interview questions~~

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


# 📚  Resources: Modern Frontend & Architecture

## Day 1: Closures & Scope

### Articles

* JavaScript.info → Closures
* MDN Web Docs → Closures

### Videos

* Akshay Saini (Namaste JavaScript) – Closures
* Kyle Simpson – Scope & Closures

### Practice

* LeetCode Easy problems using callbacks
* JavaScript30 exercises

---

## Day 2: Hoisting & Execution Context

### Articles

* JavaScript.info → Variables & Hoisting
* MDN → Hoisting

### Videos

* Namaste JavaScript Episode 3 & 4
* Frontend Masters JavaScript Deep Dive

### Practice

* Predict the output questions
* InterviewBit JavaScript MCQs

---

## Day 3: Event Loop & Async JavaScript

### Must-Watch

* Philip Roberts: "What the heck is the Event Loop anyway?"
* Namaste JavaScript Event Loop Series

### Articles

* JavaScript.info → Event Loop
* MDN → Promises & Async/Await

### Practice

* Promise output questions
* Async JavaScript coding challenges

---

## Day 4: Event Delegation & DOM

### Articles

* MDN → Event Bubbling
* JavaScript.info → Event Delegation

### Practice Projects

* Dynamic Todo List
* FAQ Accordion
* Dropdown Menu

### Interview Focus

* Event Bubbling
* Capturing
* Delegation
* stopPropagation()

---

## Day 5: React Fundamentals

### Documentation

* React Official Docs (react.dev)

### Videos

* Dave Gray React Course
* Net Ninja React Series

### Build

* Todo App
* Notes App
* Counter App

### Interview Focus

* Props vs State
* Component Re-rendering
* Controlled Components

---

## Day 6: Virtual DOM & Lifecycle

### Documentation

* React.dev → Rendering
* React.dev → Effects

### Videos

* Namaste React
* Web Dev Simplified React Internals

### Interview Focus

* Virtual DOM
* Reconciliation
* React Fiber
* useEffect Lifecycle

### Explain Like an Engineer

"React compares the new Virtual DOM tree with the previous one, calculates the minimal changes, and updates only the affected DOM nodes."

---

## Day 7: SPA Architecture & Optimization

### Articles

* GraphQL Official Docs
* REST API Tutorial
* React.dev Performance Guides

### Learn

* React.memo
* useMemo
* useCallback
* Lazy Loading
* Code Splitting

### Interview Focus

#### SPA vs Traditional Web Apps

Traditional:

* Server renders HTML on every request
* Full page reloads

SPA:

* Loads once
* Updates UI dynamically
* Communicates through APIs

#### Why REST/GraphQL?

* Separation of concerns
* Independent frontend/backend deployment
* Reusable APIs
* Mobile app support
* Better scalability

---

# 🎯 Bonus Interview Resources

### JavaScript

* Namaste JavaScript (Complete Series)
* JavaScript.info
* MDN Web Docs

### React

* React.dev
* Namaste React
* Epic React (Advanced)

### Frontend Interviews

* Frontend Interview Handbook
* GreatFrontEnd
* Frontend Masters

---



