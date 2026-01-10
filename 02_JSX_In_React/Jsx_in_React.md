## JSX In React:-<br>
JSX stands for JavaScript XML. It is a syntax extension for JavaScript used in React.<br>
JSX allows us to write HTML-like code inside JavaScript.<br>

JSX makes React code easier to read, write, and understand.<br>

**Example:-**
<pre> &nbsp; &nbsp; const element = &lt;h1&gt;Hello World&lt;/h1&gt;; </pre>

---

## Why JSX is Used in React?<br>
JSX is used because:<br>
&nbsp; &nbsp;🔹 JSX combines UI (HTML) and logic (JavaScript) in one place.<br>
&nbsp; &nbsp;🔹 Code becomes clean and readable.<br>
&nbsp; &nbsp;🔹 Easier to create dynamic content.<br>
&nbsp; &nbsp;🔹 Helps React understand UI structure clearly.<br>

**Code Without JSX:**
<pre> &nbsp; &nbsp; React.createElement("h1", null, "Hello World"); </pre>

**Code With JSX:**
<pre> &nbsp; &nbsp; &lt;h1&gt;Hello World&lt;/h1&gt; </pre>

&nbsp; &nbsp; ✔ JSX reduces complexity.<br>
&nbsp; &nbsp; ✔ Improves developer productivity.<br>

**👉 JSX is not compulsory, but almost every React project uses it.** <br>

---

## How JSX Works Internally?<br>
JSX does not run directly in the browser.<br>

JSX Process:<br>
&nbsp; &nbsp; &nbsp; 🔹 JSX is written by the developer.<br>
&nbsp; &nbsp; &nbsp; 🔹 Babel converts JSX into JavaScript.<br>
&nbsp; &nbsp; &nbsp; 🔹 JavaScript creates React elements.<br>
&nbsp; &nbsp; &nbsp; 🔹 React renders them to the DOM.<br>

**JSX Code:** <br>
<pre> &nbsp; &nbsp; const element = &lt;h1&gt;Hello!!!&lt;/h1&gt; </pre>
**Converted Code:** <br>
<pre> &nbsp; &nbsp; const element = react.createElement("h1", null, "hello")</pre>

**Note:** 👉 So JSX is just syntactic sugar for **React.createElement()**.<br>

---

## JSX Rules (Most Important): <br>
These rules are very commonly asked in interviews.<br>

**Rule 1:** JSX Must Have One Parent Element.<br>
&nbsp; &nbsp; JSX must return a single root element.<br>
**Wrong way to right JSX:**<br>
<pre> &nbsp; &nbsp; &lt;h1&gt;Hello!!!&lt;/h1&gt; <br> &nbsp; &nbsp; &lt;p&gt;React&lt;/p&gt; </pre>

**Correct way to write:** <br>
<pre> &nbsp; &nbsp; &lt;div&gt; <br> &nbsp; &nbsp; &nbsp; &nbsp; &lt;h1&gt;Hello, friends&lt;/h1&gt; <br> &nbsp; &nbsp; &nbsp; &nbsp; &lt;p&gt;It is React tutorial.&lt;/p&gt; <br> &nbsp; &nbsp; &lt;/div&gt; </pre>

**OR**<br>
**Using Fragment:** <br>
<pre> &nbsp; &nbsp; &lt;&gt; <br> &nbsp; &nbsp; &nbsp; &nbsp; &lt;h1&gt;Hello, friends&lt;/h1&gt; <br> &nbsp; &nbsp; &nbsp; &nbsp; &lt;p&gt;It is React tutorial.&lt;/p&gt; <br> &nbsp; &nbsp; &lt;/&gt; </pre>
**Note:** ✔ Fragment avoids extra &lt;div&gt; in DOM.<br>
