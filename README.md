# 📚 Unit 3 Cheat Sheet — Code.org JavaScript Essentials

Welcome to the Unit 3 Cheat Sheet! This resource was created to help students better understand key programming concepts while learning JavaScript in Code.org's Game Lab.

This cheat sheet includes beginner-friendly explanations and examples of:
- Variables
- Positioning on the screen
- Sprites and animations
-The draw() loop
-The counter pattern
- Conditionals
- Comparison operators
- Best practice tips

## 🔍 What's Inside
## 🔤 What is JavaScript?
An overview of JavaScript and how it's used in animations and interactive programs in Code.org.
## 🔢 Variables
How to declare, update, and use variables in programs.
```js
var score = 0;
score = score + 1;
text(score, 200, 100);
```
## 📍 Positioning
Explanation of the coordinate system and how to position sprites using x and y.
## 🧸 Sprites
How to create and control characters or images using blocks like:
```js
createSprite(x, y);
sprite.setAnimation("name");
sprite.scale = 0.5;
```
## 🔄 The draw() Loop
The core game loop that updates the screen 30–60 times per second. Example:
```js
function draw() {
  background("white");
  drawSprites();
}
```
## 🧠 Counter Pattern
Used to update variables over time, commonly for:
- Movement
- Score tracking
- Timers
#### Example:
```js
score = score + 1;
```
## 🧠 Conditionals
Let your program make decisions based on certain conditions.
```js
if (score > 10) {
  console.log("You're doing great!");
} else {
  console.log("Keep trying!");
}
```
## ⚖️ Comparison Operators
| Symbol | Meaning           | Example         |
|--------|-------------------|-----------------|
| `==`   | Equal to          | `score == 10`   |
| `!=`   | Not equal         | `lives != 0`    |
| `>`    | Greater than      | `points > 50`   |
| `<`    | Less than         | `speed < 5`     |
| `>=`   | Greater or equal  | `score >= 100`  |
| `<=`   | Less or equal     | `level <= 3`    |

## 💡 Tips for Beginners
- End every statement with a semicolon ;
- Use camelCase for variable names (e.g., myScore, playerSpeed)
- Keep your code clean and readable with proper spacing and indentation

## 🖥️ How to Use
Open the index.html file in your browser to view the full cheat sheet as a web page.
Make sure the style.css file is in the same directory to load the styles correctly.
## 📁 Project Structure

```
├── index.html     # The main cheat sheet page
├── style.css      # Custom styles for formatting
├── README.md      # You're here!
```


## 👩‍🏫 Made For
Teachers, students, and anyone learning the basics of JavaScript in a visual, engaging way through Code.org’s Game Lab platform.