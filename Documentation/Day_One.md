# 📚 React Learning Notes & Documentation

## 🔗 Reference Material
- **YouTube Tutorial:**  
  https://www.youtube.com/watch?v=TtPXvEcE11E&t=4999s  

- **React Template (Recommended):**  
  https://supersimple.dev/react-basics  

---

## ⚛️ React Fundamentals

### 📌 Overview
React is a **front-end JavaScript library** used to build interactive and dynamic user interfaces, especially for single-page applications.

### 🧠 Key Concepts
- **JSX (JavaScript XML)**  
  A syntax extension that allows writing HTML-like code inside JavaScript. It is compiled into standard JavaScript.

- **Components**  
  Applications should be built using **reusable components** to improve maintainability and scalability.

- **Variables & Data Handling**  
  Variables store dynamic values and can be embedded inside JSX using `{}`.

- **Fragments (`<> </>`)**  
  Used to group multiple elements without adding extra nodes to the DOM.

---

## 🤖 AI Notes & Code Examples


## 📄 File: `chatbot-react.html` (Basic Example)

### 📌 Description
A minimal JSX implementation that demonstrates how to create and render React elements into the DOM.

### 🧠 Key Concepts
- JSX syntax
- Element creation
- Embedding expressions (`{1 + 1}`)
- Rendering using:
  ```js
  ReactDOM.createRoot(...).render(...)