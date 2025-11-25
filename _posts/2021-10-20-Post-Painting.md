---
layout: posts
title: Forest painting
---

# My first computer art project



![alt text](../assets/images/Screenshot (2).png "painting Picture")


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





def sq():
    color=(40,57,4)
    t = turtle.Turtle()
    t.color(color)
    t.penup()
    t.setpos(-100,-220)
    t.shape("square")
    t.shapesize(3)
sq()

def tre():
    # color=(74,57,4)
    color=(34,26,2)
    h = turtle.Turtle()
    h.color(color)
    h.setheading(90)
    h.penup()
    h.setpos(-100,-173)
    h.shape("triangle")
    h.shapesize(3)
tre()

def su():
    color=(34,26,2)
    k= turtle.Turtle()
    k.color(color)
    k.penup()
    k.setpos(-150,-220)
    k.pendown()
    k.shape("square")
    k.shapesize(3, stretch_len=8)
su()
def mo():
    color=(54,40,4)
    t = turtle.Turtle()
    t.fillcolor(color)
    t.begin_fill()
    t.penup()
    t.setpos(-201,-141)
    t.pendown()
    t.forward(100)
    t.right(120)
    t.forward(62)
    t.right(60)
    t.forward(100)
    t.right(120)
    t.forward(62)
    t.end_fill()
    t.hideturtle()

mo()

def door():
    c=(54,40,4)
    t=turtle.Turtle()
    t.shape("square")
    t.shapesize(1)
    t.color(c)
    t.penup()
    t.setpos(-100,-230)
    t.pendown()
door()
turtle.update()
turtle.mainloop()



```

---
**title**: jungle with puthon
