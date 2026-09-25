# React Front-End Project

## 📌 Project Overview

This is a basic React front-end project developed to understand the fundamentals of React application development and component-based UI design.

The project demonstrates how to:

* Create a React application
* Create and use functional components
* Import and render components
* Apply CSS styling
* Organize React components into separate files
* Run and test a React application locally

---

## 🛠️ Technologies Used

* React
* JavaScript
* HTML
* CSS
* npm
* Create React App

---

## 📂 Project Structure

```text
React-Front-end/
│
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
│
├── src/
│   ├── components/
│   │   ├── Hello.js
│   │   └── Welcome.js
│   │
│   ├── App.css
│   ├── App.js
│   ├── App.test.js
│   ├── index.css
│   ├── index.js
│   ├── reportWebVitals.js
│   └── setupTests.js
│
├── package.json
└── README.md
```

---

## 🧩 Components

### App Component

`App.js` is the main application component.

It imports and renders the following components:

* `Welcome`
* `Hello`

```javascript
import Hello from "./components/Hello";
import Welcome from "./components/Welcome";

function App() {
  return (
    <div>
      <Welcome />
      <Hello />
    </div>
  );
}
```

### Welcome Component

The `Welcome.js` component displays a welcome message.

It contains:

* A heading
* A paragraph describing the project

### Hello Component

The `Hello.js` component displays a simple greeting message.

---

## 🎨 Styling

The project uses CSS files for styling.

### App.css

Contains styling for the main application.

### index.css

Contains global styling applied to the application.

---

## ⚙️ Prerequisites

Before running the project, make sure the following are installed:

* Node.js
* npm

You can verify the installation using:

```bash
node -v
npm -v
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone <YOUR-GITHUB-REPOSITORY-URL>
```

Navigate to the project directory:

```bash
cd React-Front-end
```

Install the required dependencies:

```bash
npm install
```

---

## ▶️ Run the Application

Start the development server:

```bash
npm start
```

The application will run at:

```text
http://localhost:3000
```

Open the URL in a web browser to view the application.

---

## 🧪 Testing

The project includes a basic test file.

Run the tests using:

```bash
npm test
```

---

## 🏗️ Build

To create a production build:

```bash
npm run build
```

The optimized application will be generated in the `build` directory.

---

## 📚 Learning Objectives

This project was created to practice the following React concepts:

* React application structure
* Functional components
* Component importing and exporting
* JSX
* CSS integration
* Rendering components
* Basic project organization
* Running a React application using npm

---

## 👨‍💻 Author

**Sasikiran**

---

## 📄 License

This project is created for learning and practice purposes.
