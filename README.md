# 🌟 Turtle Graphics: Starburst Pattern Project

This fun and colorful Python project uses the built-in `turtle` graphics module to draw a vibrant **starburst pattern** on a dark background. It's a perfect mini-project to learn about loops, color cycling, angles, and graphical output in Python!

---

## 🎯 What You'll Learn

* ✅ How to use Python's `turtle` module
* ✅ Drawing with loops and color patterns
* ✅ Creating star shapes using turning angles
* ✅ Using dynamic line lengths

---

## 🎨 What It Does

This script draws a **radiating star pattern** using a loop that:

* Cycles through a list of bright neon colors
* Increases the line length with each iteration
* Turns the turtle by 144° to form a starburst

The result is a glowing, hypnotic pattern drawn in real time.

---

## 🧱 Project Code

```python
# Let's import turtle and set up a cool dark background for contrast
import turtle

screen = turtle.Screen()
screen.bgcolor("black")  # Sets the background to black for better contrast

# Now let’s create the turtle and define some bright colors
t = turtle.Turtle()
t.speed(0)  # Set the turtle speed to the fastest

colors = ["cyan", "magenta", "lime", "yellow", "orange"]  # A bright, eye-catching palette

# The magic happens in this loop:
# We'll draw 100 lines, turning 144° each time to make that star shape
for i in range(100):
    t.color(colors[i % len(colors)])  # Cycle through the colors
    t.forward(i * 2)                  # Increase line length each time
    t.right(144)                      # Turn by 144° to create a star pattern

# Keep the window open after drawing
turtle.done()
```

---

## 🧪 How to Run This Project

1. Make sure you have **Python 3** installed.
2. Copy the code above into a file named `starburst.py`
3. Open your terminal and run:

   ```bash
   python starburst.py
   ```
4. A window will open, and the turtle will draw your colorful starburst pattern!

---

## 🌈 Try These Variations

* Change the turning angle to see different geometric effects
* Add more colors to the palette
* Play with speed or total loop iterations
* Add background music using `playsound` for fun

---

## 🐍 This is part of the **Pythonly beginner series**.

Learn Python one line at a time. Follow [@Pythonly](https://github.com/Pythonlyy) for more.
