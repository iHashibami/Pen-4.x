# Pen! 4.x - An Julian's Editor open-source project!


**Pen! 4.x** is a custom drawing language built inside [Julian's Editor](https://global.julianseditor.com/app/), inspired by Turtle Graphics and the pen extension from Scratch. It features a simple way of programming that allows users to create shapes, animations, and patterns with code.

---

## Link to the Project

Try it here: [https://s.julianseditor.com/PvR5L1](https://s.julianseditor.com/PvR5L1)

---

## Features

* Block-based drawing system and coding (Lining.pe)

* Support for absolute positioning

* Pen state management (up, down, show, hide)

* Gradual drawing

* Control over the pen (color, size, speed)

---

## Command Overview (note: these are the block names that I made in Julian's Editor.)

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
* `circle(segments , orientation , direction , size)`

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

## Example: Drawing a circle without circle()

```
#This is a pseudocode!

setup()
repeat 36 times:
    forward(0.5)
    left(10)
```

---

## Version history

* **V1**: Initial release into the 4.x JE version!
* **V2**: Made it easier and fixed tons of bugs!
* **V3**: Added circle()!

---

## License

Pen 4.x is an open-source project, you just have to add my name. Feel free to modify, remix, and share in Julian's Editor!

---

## Creator

iHashibami - The Bo0x Studio📦

Made by a young developer passionate about programming and design.

Want to contribute or ask questions? You can open issues or fork the repository once it's on GitHub.
