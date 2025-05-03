# Pen-4.x - An Julian's Editor open-source project!


**Pen 4.x** is a custom drawing language built inside [Julian's Editor](https://s.julianseditor.com/PvR5L1), inspired by Turtle Graphics and the pen extension from Scratch. It features a simple command syntax that allows users to create shapes, animations, and patterns with code.

---

## Link to the Project

Try it here: [https://s.julianseditor.com/PvR5L1](https://s.julianseditor.com/PvR5L1)

---

## Features

* Block-based drawing system (Lining.pe language)

* Support for absolute and relative positioning

* Pen state management (up, down, show, hide)

* Custom movement speed

* Gradual drawing

---

## Command Overview

### Commands with Inputs:

* `forward(x)`
* `backward(x)`
* `right(x)`
* `left(x)`
* `goto(x, y)`
* `setx(x)`
* `sety(y)`
* `setheading(angle)`
* `pensize(width)`
* `pencolor(color)`
* `speed(x)`
* `bgcolor(color)`

### Commands without Inputs:

* `home()`
* `penup()` / `pendown()`
* `showturtle()` / `hideturtle()`
* `clear()` / `reset()` / `setup()` / `done()`

### Outputs:

* `isvisible()`
* `heading()`
* `position()`

---

## Example: Drawing a Circle

```
#This is a pseudocode!

setup()
repeat 36 times:
    forward(0.5)
    left(10)
```

---

## Version History

* **V1**: Initial release into the 4.x JE version!

---

## License

Pen 4.x is an open-source project. Feel free to modify, remix, and share!

---

## Creator

iHashibami - The Bo0x Studio📦

Made by a young developer passionate about programming and design.

Want to contribute or ask questions? You can open issues or fork the repository once it's on GitHub.
