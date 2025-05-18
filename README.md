````markdown
# 🧿 Fortune Teller

A simple JavaScript project that randomly selects and displays one of five predefined fortunes. This mini-app demonstrates variable initialization, random number generation, conditional logic, and console output in JavaScript.

## 📋 Features

- Defines five custom fortune messages.
- Uses `Math.random()` to simulate unpredictability.
- Maps a random number to a corresponding fortune.
- Outputs a random fortune to the console on each run.

## 🛠️ Technologies

- JavaScript (Vanilla ES6)
- Node.js or browser console for execution

## 📁 Project Structure

```plaintext
fortune-teller/
│
├── README.md        # Project documentation
└── index.js         # Main JavaScript logic
```

## 📜 How It Works

1. Five variables (`fortune1` to `fortune5`) are assigned unique fortune strings.
2. A random number between 1 and 5 is generated using:

```javascript
let randomNumber = Math.floor(Math.random() * 5) + 1;
```

3. An `if-else` block checks the number and assigns the appropriate fortune:

```javascript
if (randomNumber === 1) {
  selectedFortune = fortune1;
} ...
```

4. The selected fortune is logged to the console:

```javascript
console.log(selectedFortune);
```

## 🚀 Getting Started

### Run in Browser

1. Open `index.html` (if created) or use browser DevTools Console.
2. Paste the JavaScript code.
3. Hit Enter — a random fortune appears.

### Run in Node.js

1. Make sure Node.js is installed.
2. Save the script as `index.js`.
3. Run with the terminal:

```bash
node index.js
```

## ✍️ Example Output

```bash
You will find a new hobby soon.
```

## 📌 Use Case

Ideal for learning:

* Random number generation
* Basic control flow
* JavaScript debugging and output

## 📄 License

This project is open source and free to use for educational purposes.

```
