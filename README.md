  3 import time
  4 
  5 # set the background color for the page
  6 bg = turtle.Screen()
  7 bg.bgcolor("light blue")
  8 
  9 
 10 my_turtle = turtle.Turtle()
 11 my_turtle.shape("turtle")
 12 my_turtle.speed(1)
 13 
 14 # draw sun
 15 my_turtle.color("yellow")
 16 my_turtle.pensize(3)
 17 my_turtle.penup()
 18 my_turtle.setposition(150, 150)
 19 my_turtle.begin_fill()
 20 my_turtle.pendown()
 21 my_turtle.circle(50)
 22 my_turtle.end_fill()
 23 
 24 # draw rays
 25 my_turtle.penup()
 26 my_turtle.goto(150, 140)
 27 my_turtle.pendown()
 28 my_turtle.goto(150, 130)
 29 
 30 my_turtle.penup()
 31 my_turtle.goto(150, 260)
 32 my_turtle.pendown()
 33 my_turtle.goto(150, 270)
 34 
 35 my_turtle.penup()
 36 my_turtle.goto(210, 200)
 37 my_turtle.pendown()
 38 my_turtle.goto(220, 200)
