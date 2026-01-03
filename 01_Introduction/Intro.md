# Introduction to React
React JS is a JavaScript library used for building fast, interactive, and reusable user interfaces, especially for single-page applications (SPAs).
It was developed by Facebook (Meta) and is widely used by companies like Netflix, Instagram, WhatsApp, Airbnb, and Uber.

React focuses mainly on the View layer of an application (MVC architecture), meaning it handles how the UI looks and behaves.

## Definition of React JS
React JS is an open-source, component-based JavaScript library used to create dynamic and high-performance user interfaces using a virtual DOM.
 
**Beginner tip:**  
&nbsp; &nbsp; &nbsp; React works only on the **UI part (frontend)** of an application.

**Interview line:**  
&nbsp; &nbsp; &nbsp; React is a JavaScript library used to build reusable UI components.

---

## Why React JS Was Created?
React is widely used because it makes UI development easier, faster, and more organized.

**Before React:** <br>
&nbsp; &nbsp; &nbsp; 🔹Developers directly manipulated the real DOM. <br>
&nbsp; &nbsp; &nbsp; 🔹UI updates were slow and complex. <br>
&nbsp; &nbsp; &nbsp; 🔹Code was hard to maintain for large applications. <br>

**React solves these problems by:** <br>
&nbsp; &nbsp; &nbsp; 🔹Using Virtual DOM. <br>
&nbsp; &nbsp; &nbsp; 🔹Breaking UI into reusable components. <br>
&nbsp; &nbsp; &nbsp; 🔹Making UI updates efficient and predictable. <br>

---

### Key Features of React JS  <br><br>

1️⃣ Component-Based Architecture <br>
&nbsp; &nbsp; &nbsp; 🔹UI is divided into small, reusable components. <br>
&nbsp; &nbsp; &nbsp; 🔹Each component has its own logic and UI. <br>
&nbsp; &nbsp; &nbsp; 🔹Improves code reusability and maintainability. <br>

<b> Example: </b> <br>

&nbsp; &nbsp; &nbsp; function Button() { <br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; return &lt;button&gt; Click Me &lt;/button&gt;; <br>
&nbsp; &nbsp; &nbsp; } <br>

2️⃣ Virtual DOM<br>
&nbsp; &nbsp; &nbsp; 🔹React creates a virtual copy of the real DOM.<br>
&nbsp; &nbsp; &nbsp; 🔹Changes are first applied to the virtual DOM.<br>
&nbsp; &nbsp; &nbsp; 🔹React compares (diffing) and updates only the changed parts.<br>
&nbsp; &nbsp; &nbsp; 🔹Results in faster performance.<br> 

<b> Example: </b> <br>

&nbsp; &nbsp; &nbsp; function Button() { <br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; return &lt;button&gt; Click Me &lt;/button&gt;; <br>
&nbsp; &nbsp; &nbsp; } <br>

3️⃣ JSX (JavaScript XML) <br>
&nbsp; &nbsp; &nbsp; 🔹JSX allows writing HTML inside JavaScript.<br>
&nbsp; &nbsp; &nbsp; 🔹Makes code more readable and expressive.<br>

<b> Example: </b> <br>

&nbsp; &nbsp; &nbsp; const element = &lt;h1&gt;Hello React&lt;/h1&gt;; <br>

4️⃣ One-Way Data Binding <br>
&nbsp; &nbsp; &nbsp; 🔹Data flows from parent to child.<br>
&nbsp; &nbsp; &nbsp; 🔹Makes application more predictable.<br>
&nbsp; &nbsp; &nbsp; 🔹Easier debugging and testing.<br>

5️⃣ State and Props <br>
&nbsp; &nbsp; &nbsp; <b>State:<b> Manages component’s internal data.<br>
&nbsp; &nbsp; &nbsp; Props: Pass data from parent to child components.<br>

6️⃣ Hooks <br>
Introduced in React 16.8.<br>
Allow using state and lifecycle features in functional components.<br>
🔹Common Hooks:<br>
&nbsp; &nbsp; &nbsp; 🔹useState<br>
&nbsp; &nbsp; &nbsp; 🔹useEffect<br>
&nbsp; &nbsp; &nbsp; 🔹useContext<br>
&nbsp; &nbsp; &nbsp; 🔹useRef<br>

---
