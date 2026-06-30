# JavaScript

JavaScript (JS) is a high-level, interpreted programming language used to create interactive and dynamic web applications. It is one of the three core technologies of web development, alongside HTML and CSS.

---

## 📋 Prerequisites

Before writing JavaScript code, make sure you have the following installed:

- **Node.js** (includes npm)
- **Visual Studio Code** (recommended)
- **Git**
- **A modern web browser**
  - Google Chrome
  - Mozilla Firefox
  - Microsoft Edge

---

## ▶️ Running a JavaScript File

### Using Node.js

Run a JavaScript file from the terminal:

```bash
node index.js
```

### Example

```javascript
console.log("Hello, World!");
```

### Output

```text
Hello, World!
```

---

## 🌐 Running JavaScript in a Browser

Create the following files:

```
project/
│── index.html
└── script.js
```

### index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript Example</title>
</head>
<body>

    <h1>Hello JavaScript</h1>

    <script src="script.js"></script>
</body>
</html>
```

### script.js

```javascript
console.log("Hello from JavaScript!");
```

### Run the Application

You can run the application by:

- Opening `index.html` directly in your web browser.
- Right-clicking `index.html` and selecting **Open With** → Your Browser.
- Using the **Live Server** extension in Visual Studio Code.

---

