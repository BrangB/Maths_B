# my-npm-package

A simple npm package for math utilities.

## Installation
```sh
npm install maths_b
```

or using yarn:
```sh
yarn add maths_b
```

---

## 📖 Usage

Import and use the package in your JavaScript project:

### **ES6+ Import**
```js
import { add, substract } from "maths_b";

console.log(add(5, 3));      // Output: 8
console.log(substract(10, 4)); // Output: 6
```

### **CommonJS Import**
```js
const { add, substract } = require("maths_b");

console.log(add(5, 3));      // Output: 8
console.log(substract(10, 4)); // Output: 6
```

---

## 📌 API Reference

### `add(a, b)`
- **Description:** Returns the sum of `a` and `b`.
- **Parameters:**
  - `a` *(number)* – First number.
  - `b` *(number)* – Second number.
- **Returns:** `number` – Sum of `a` and `b`.
- **Example:**
  ```js
  add(2, 3); // 5
  ```

### `substract(a, b)`
- **Description:** Returns the result of subtracting `b` from `a`.
- **Parameters:**
  - `a` *(number)* – First number.
  - `b` *(number)* – Number to subtract.
- **Returns:** `number` – Difference of `a` and `b`.
- **Example:**
  ```js
  substract(10, 4); // 6
  ```

---

## 🔥 Features
✅ Simple and lightweight  
✅ Supports CommonJS and ES6+  
✅ Works in Node.js and browser  

---

## 🛠️ Contributing

We welcome contributions! Follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make changes and commit (`git commit -m "Add new feature"`).
4. Push to your branch (`git push origin feature-name`).
5. Open a pull request.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 📞 Support & Contact

For any issues, please [open an issue](https://github.com/yourusername/maths_b/issues) or contact me at [your-email@example.com](mailto:your-email@example.com).

