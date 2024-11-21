# Bootstrap with Vite 🚀

A quick and easy setup guide to integrate **Bootstrap** with **Vite** for modern frontend development.

---

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v14+ recommended)
- npm (comes with Node.js)

---

## 🛠️ Installation Guide

Follow these steps to set up Bootstrap in a Vite project:

### 1️⃣ Create a Vite Project

Run the following command to create a new Vite project:

```bash
npm create vite@latest my-vite-app

```
### Replace my-vite-app with your desired project name. Navigate to the project folder:
```bash
cd my-vite-app

```
### 2️⃣ Install Dependencies ans Bootstrap
---
Install the required packages:
```bash
npm install
npm install bootstrap @popperjs/core

```

### 4️⃣ Import Bootstrap Styles and Scripts
---
Import CSS
In your entry file (e.g., main.js or main.jsx), add:
```bash
import 'bootstrap/dist/css/bootstrap.min.css';
```
#### Import JavaScript (Optional)
If you need Bootstrap's JavaScript components (e.g., modals, tooltips):
```bash
import 'bootstrap/dist/js/bootstrap.bundle.min.js';
```
### 5️⃣ Start the Development Server
#### Run the following command to start the server:
```bash
npm run dev
```

### ✨ Example Usage 
Here’s an example React component using Bootstrap:
```bash
function App() {
  return (
    <div className="container mt-5">
      <h1 className="text-primary">Hello, Bootstrap with Vite!</h1>
      <button className="btn btn-success">Click Me</button>
    </div>
  );
}

export default App;
```


### 🛡️ Technologies Used
Vite: A fast and modern build tool for frontend projects.
Bootstrap: A popular CSS framework for responsive designs.
Node.js: A JavaScript runtime for managing dependencies.

### 📝 License
This project is licensed under the MIT License.
Feel free to use and customize this setup for your projects! ⭐

