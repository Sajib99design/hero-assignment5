
## 📌 Repository & Live Demo
- **Repo:** https://github.com/Sajib99design/hero-assignment5.git;
- **Live:** https://sajib99design.github.io/hero-assignment5;

# Questions & Answers

---

### 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
**Answer:**
- **getElementById** → It’s a DOM method used to get a single element by ID.
- **getElementsByClassName** → It’s a DOM method  used to find a group of elements with the same class.
- **querySelector** → It’s a DOM method  used to get the first element with an ID or class.
- **querySelectorAll** → It’s a DOM method  used to get all the elements in the code with an ID or class.

---

### 2. How do you create and insert a new element into the DOM?
**Answer:**
To create a new element  `document.createElement("TagName")`.
To insert a new element  `append()`.

---

### 3. What is Event Bubbling and how does it work?
**Answer:**
Event bubbling is a mechanism in JavaScript where an event starts from the target element (the innermost child) and then propagates upward through its ancestors in the DOM tree, all the way up to the root element.
For example, if you click on a button inside a div, the click event will first be handled by the button, then bubble up to the div, then to its parent, and finally to the document.

---

### 4. What is Event Delegation in JavaScript? Why is it useful?
**Answer:**
Event Delegation in JavaScript is a process of getting all the children elements by adding one single event listener to the parent element. It works by the event bubbling process.
It is useful because it reduces the number of event listeners in the code, making it more efficient, easier to maintain, and improving overall performance.

---

### 5. What is the difference between preventDefault() and stopPropagation() methods?
**Answer:**
- **preventDefault()** → It stops the default behavior of an event (for example, stopping a form submit button).
- **stopPropagation()** → It stops event bubbling.

---
