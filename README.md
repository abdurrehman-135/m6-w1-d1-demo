##  Factory Pattern OOP Demo (Week 6 – Day 1)

###  Overview

This project demonstrates the **Factory Design Pattern** using JavaScript and Node.js. It shows how to create different object types (Laptop and Tablet) through a centralized factory function, promoting clean, scalable, and reusable code.

---

###  Concepts Covered

* Object-Oriented Programming (OOP)
* Constructor Functions
* Factory Pattern
* Module Exports/Imports in Node.js

---

###  Project Structure

```
/factory
  ├── laptop.js
  ├── tablet.js
  ├── gadgetFactory.js
  └── index.js
```

---

###  How It Works

* `laptop.js` and `tablet.js` define constructors for each gadget type.
* `gadgetFactory.js` contains a `createGadget()` method that dynamically creates objects based on type.
* `index.js` uses the factory to generate and log gadget objects.

---

### Run the Project

```bash
node ./factory/index.js
```

---





