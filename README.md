# MyEditor - A Web-Based HTML, CSS, and JS Live Editor

MyEditor is a web-based live code editor where users can write and preview HTML, CSS, and JavaScript in real-time. The editor is built using **React**, **Monaco Editor**, and features a **live preview** using an iframe. It's designed for developers and learners to easily experiment with web development code.

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://mycodeditor.vercel.app/)

---

## **Features**

- **Real-Time Preview**: Instantly view the output of your HTML, CSS, and JavaScript as you type.
- **Monaco Editor**: Leverage the power of **Monaco Editor**, the same editor used in **Visual Studio Code**.
- **Syntax Highlighting**: Supports **HTML**, **CSS**, and **JavaScript** with syntax highlighting.
- **Auto-Completion**: Basic auto-completion for HTML tags and JavaScript functions.
- **Live Console Output**: View the `console.log()` and errors directly in the application.
- **Lightweight**: No server setup required — works entirely in the browser.
- **Easy to Extend**: Easily add support for more languages and features.
- **Customizable UI**: Supports a clean, responsive, and customizable layout for different devices.

---

## **Tech Stack**

- **React**: JavaScript library for building user interfaces.
- **Monaco Editor**: Lightweight, fast code editor used in VS Code.
- **JavaScript/TypeScript**: Core language for the frontend logic.
- **Vite**: A modern build tool for fast development with React.
- **CSS**: Styling for the code editor and layout.
- **HTML**: Base structure for displaying and previewing content.

---

## **Installation**

To run the editor locally, follow the instructions below:

### **Prerequisites**

- Ensure you have **Node.js** and **npm** installed. If not, you can download and install them from [Node.js](https://nodejs.org/).

### **Clone the repository**

```bash
git clone https://github.com/azhar0i0/MyEditor.git
cd MyEditor
```

### **Install dependencies**
```
npm install
```
### **Run the development server**
```
npm run dev
```
This will start the Vite development server and open the app in your browser.

---

### **Usage**
Once the development server is running, you can open your browser and navigate to ``` http://localhost:5173 ``` (or the port specified in the terminal).

The app will have three editable sections:

HTML Editor: Where you can write and edit HTML code.

CSS Editor: Where you can write and edit CSS styles.

JavaScript Editor: Where you can write and edit JavaScript code.

Below the editor, a live preview window will show the real-time output of your code.


---

### **Contributing**

We welcome contributions to improve the project! If you'd like to contribute, follow these steps:

Fork the repository.

Clone your fork to your local machine.

Create a new branch (git checkout -b feature-name).

Make your changes and commit them (git commit -am 'Add feature').

Push to your branch (git push origin feature-name).

Create a pull request.
