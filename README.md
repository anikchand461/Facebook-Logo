# Facebook-Logo

from turtle import Turtle,Screen

s=Screen()
t=Turtle()
t.hideturtle()

#outer frame
t.fillcolor('blue')
t.pencolor('blue')
t.begin_fill()
t.up()
t.goto(-65,-100)
t.down()
for _ in range(4):
    t.fd(130)
    t.circle(25,90)
t.end_fill()

#f
t.up()
t.goto(0,-100)
t.down()
t.fillcolor('white')
t.pencolor('white')
t.begin_fill()
t.seth(90)
t.fd(115)
t.circle(-30,90)
t.fd(27)
t.seth(-90)
t.fd(25)
t.seth(180)
t.fd(20)
t.circle(10,90)
t.fd(112)
t.end_fill()

#f dash
t.up()
t.goto(0,-30)
t.down()
t.fillcolor('white')
t.begin_fill()
t.seth(0)
t.fd(50)
t.lt(75)
t.fd(23)
t.seth(180)
t.fd(78)
t.seth(-90)
t.fd(22)
t.seth(0)
t.fd(28)
t.end_fill()


#-----------------------------
#alternative...
#t.pensize(25)
#t.pencolor('white')
#t.up()
#t.goto(0,-100)
#t.down()
#t.seth(90)
#t.fd(115)
#t.circle(-30,90)
#t.fd(23)
#t.up()
#t.goto(-30,-22)
#t.down()
#t.seth(0)
#t.fd(70)

s.mainloop()
