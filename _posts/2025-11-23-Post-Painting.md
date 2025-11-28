---
layout: posts
title: Forest painting
---

## My first computer art project



![My painting](../assets/images/painitg.jpg "painting Picture")


``` python


import turtle
import random


turtle.colormode(255) 

turtle.tracer(0)

def border():
    a=6
    color=( 255 , 173 , 20 )
    turtle.penup()
    turtle.setpos(0,360)
    turtle.pendown()
    turtle.color("yellow")
    turtle.fillcolor(color)
    turtle.begin_fill()
    for i in range(60):
        turtle.forward(38) 
        turtle.right(a)
    turtle.end_fill()
    turtle.hideturtle()

border() 


def draw_sun():
    t=turtle.Turtle()
    t.shape("circle")
    t.color("white")
    t.penup()
    t.setpos(20,80)
    t.pendown()
    t.shapesize(18)
    t.stamp()
    t.hideturtle()

draw_sun()

def mountain():
    t=turtle.Turtle()
    t.setheading(90)
    t.shape("triangle")
    t.color("black")
    t.penup()
    t.setpos(-195,-98)
    t.pendown()
    x=-180
    y=-50
    p=13
    for i in range(4):
        t.penup()
        t.setpos(x,y)
        t.pendown()
        t.shapesize(p) 
        t.stamp()
        x=x+80
        y=y-17
        p=p-3
    t.hideturtle()

mountain()

turtle.penup()
turtle.speed(0)
turtle.setheading(90)
turtle.setpos(250,-280)
turtle.color("black")
turtle.pendown()






def sabzeh():
 x=random.randint(-280,220)
 y=random.randint(-200,-132)
 t=turtle.Turtle()
 t.penup()
 t.setpos(x,y)
 t.pendown()
 t.setheading(90)
 t.forward(6)
 t.pensize(2)
 t.color("green")
 t.backward(6)
 t.hideturtle()
for i in range(4000):
 sabzeh()
 
```

---
**description**: jungle with puthon
