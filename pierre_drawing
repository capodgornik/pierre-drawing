'''
Author: Celine Podgornik
Date: January 25th 2017

Description:
This program uses turtle to draw a picture of my cat, Pierre, going for a walk on a nice and cloudy day.
'''

import turtle
    
def shape(madison, x):
    '''
    This function draws a diamond.
    
    Parameters:
    madison: a turtle that is used to draw the diamond.
    x: an int that determines the side length of the shape.

    Returns: None
    '''
    
    madison.penup()
    madison.forward(x)
    madison.pendown()
    madison.left(120)
    madison.forward(x)
    madison.left(120)
    madison.forward(x)
    madison.left(60)
    madison.forward(x)
    madison.left(120)
    madison.forward(x)
    return None
    
def pentagon(pierre, x):
    '''
    This function draws a pentagon.
    
    Parameters:
    pierre: a turtle that is used to draw the pentagon.
    x: an int that determines the side length of the shape.

    Returns: None
    '''
    
    pierre.forward(x)
    pierre.left(72)
    pierre.forward(x)
    pierre.left(72)
    pierre.forward(x)
    pierre.left(72)
    pierre.forward(x)
    pierre.left(72)
    pierre.forward(x)
    pierre.left(162)
    return None    
    
def triangle(pierre, x):
    '''
    This function draws a triangle.
    
    Parameters:
    pierre: a turtle that is used to draw the triangle.
    x: an int that determines the side length of the shape.

    Returns: None
    '''

    pierre.forward(x)
    pierre.left(120)
    pierre.forward(x)
    pierre.left(120)
    pierre.forward(x)
    pierre.left(30)
    return None    
    
def rectangle(inky, length, width):
    '''
    This function draws a rectangle.
    
    Parameters:
    inky: a turtle that is used to draw the rectangle.
    x: an int that determines the side length of the shape.

    Returns: None
    '''
    
    inky.forward(length)
    inky.right(90)
    inky.forward(width)
    inky.right(90)
    inky.forward(length)
    inky.right(90)
    inky.forward(width)
    inky.setheading(0)
    return None
    
def draw_p(madison):
    '''
    This function draws the letter "P".
    
    Parameters:
    madison: a turtle that is used to draw the letter.

    Returns: None
    '''
    
    madison.left(90)
    madison.forward(25)
    madison.right(90)
    madison.forward(12.5)
    madison.right(90)
    madison.forward(12.5)
    madison.right(90)
    madison.forward(12.5)
    return None

def draw_i(pierre):
    '''
    This function draws the letter "I".
    
    Parameters:
    pierre: a turtle that is used to draw the letter.

    Returns: None
    '''
    
    pierre.forward(25)
    pierre.backward(12.5)
    pierre.left(90)
    pierre.forward(25)
    pierre.left(90)
    pierre.forward(12.5)
    pierre.right(180)
    pierre.forward(25)
    return None
    
def draw_e(pierre):
    '''
    This function draws the letter "E".
    
    Parameters:
    pierre: a turtle that is used to draw the letter.

    Returns: None
    '''

    pierre.forward(25)
    pierre.backward(25)
    pierre.left(90)
    pierre.forward(12.5)
    pierre.right(90)
    pierre.forward(20)
    pierre.backward(20)
    pierre.left(90)
    pierre.forward(12.5)
    pierre.right(90)
    pierre.forward(25)
    return None
    
def draw_r(madison):
    '''
    This function draws the letter "r".
    
    Parameters:
    pierre: a turtle that is used to draw the letter.

    Returns: None
    '''
    
    madison.left(90)
    madison.forward(25)
    madison.right(90)
    madison.forward(12.5)
    madison.right(90)
    madison.forward(12.5)
    madison.right(90)
    madison.forward(12.5)
    madison.left(135)
    madison.forward(19)
    return None
    
def jump(madison, x):
    '''
    This function makes the turtle jump.
    
    Parameters:
    madison: a turtle that is used for the jump.
    
    Returns: none.
    '''
    
    madison.penup()
    madison.fd(x)
    madison.pendown()    
#==========================================================
def main():
    '''
    When this program is run, first the turtle draws a border of diamonds around the edges using for loops. Then, the turtle draws the clouds and Pierre.
    Finally, the program writes Pierre's name at the bottom of the picture (within the border). 
    '''

    rory = turtle.Turtle()
    rory.pensize(5)
    rory.speed(0)
    rory.shape('turtle')
    rory.penup()
    rory.goto(-300,225)
    rory.pendown()
    turtle.bgcolor('lightsteelblue')
    
    for i in range(6):
        for j in range(2):
            if j%3 == 0:
                rory.begin_fill()
                rory.color('turquoise')
                rory.pencolor('blue')
            else:
                rory.begin_fill()
                rory.color('turquoise')
                rory.pencolor('green')
            shape(rory, 50)
            rory.end_fill()
            rory.setheading(0)
    
    for i in range(1):
        for j in range(5):
            if j%6 == 0:
                rory.begin_fill()
                rory.color('turquoise')
                rory.pencolor('blue')
            elif j%6 == 1:
                rory.begin_fill()
                rory.color('turquoise')
                rory.pencolor('green')
            elif j%6==2:
                rory.begin_fill()
                rory.color('turquoise')
                rory.pencolor('blue')
            elif j%6==3:
                rory.begin_fill()
                rory.color('turquoise')
                rory.pencolor('green')
            elif j%6==4:
                rory.begin_fill()
                rory.color('turquoise')
                rory.pencolor('blue')
            else:
                rory.begin_fill()
                rory.color('turquoise')
                rory.pencolor('green')  
            rory.penup()
            rory.setheading(270)
            rory.forward(90)
            rory.setheading(180)
            rory.forward(50)
            rory.pendown()
            rory.setheading(0)
            shape(rory, 50)
            rory.end_fill()
            
    rory.setheading(180)
    rory.penup()
    rory.forward(50)
        
    for i in range(5):
        for j in range(2):
            if j%3 == 0:
                rory.begin_fill()
                rory.color('turquoise')
                rory.pencolor('green')
            else:
                rory.begin_fill()
                rory.color('turquoise')
                rory.pencolor('blue')
            rory.setheading(180)
            shape(rory, 50)
            rory.end_fill()
    rory.begin_fill()
    rory.color('turquoise')
    rory.setheading(180)
    rory.pencolor('green')
    shape(rory, 50)
    rory.end_fill()
          
    for i in range(1):
        for j in range(4):
            rory.penup()
            rory.setheading(0)
            rory.forward(50)
            rory.setheading(90)
            rory.forward(90)
            rory.pendown()
            rory.setheading(180)
            if j%5==0:
                rory.begin_fill()
                rory.color('turquoise')
                rory.pencolor('blue')
            elif j%5 == 1:
                rory.begin_fill()
                rory.color('turquoise')
                rory.pencolor('green')
            elif j%5==2:
                rory.begin_fill()
                rory.color('turquoise')
                rory.pencolor('blue')
            elif j%5==3:
                rory.begin_fill()
                rory.color('turquoise')
                rory.pencolor('green')
            else: 
                rory.begin_fill()
                rory.color('turquoise')
                rory.pencolor('blue')   
            shape(rory, 50)
            rory.end_fill()
    
    rory.penup()
    rory.goto(-150,65)
    rory.setheading(90)
    rory.begin_fill()
    rory.color('lightslateblue')
    rory.pencolor('purple')
    shape(rory, 100)
    rory.end_fill()
    rory.penup()
    rory.goto(-50,50)
    rory.pendown()
    rory.setheading(90)
    rory.begin_fill()
    rory.color('lightslateblue')
    rory.pencolor('purple')
    shape(rory, 140)
    rory.end_fill()
    rory.penup()
    rory.goto(50,50)
    rory.pendown()
    rory.setheading(90)
    rory.begin_fill()
    rory.color('lightslateblue')
    rory.pencolor('purple')
    shape(rory, 140)
    rory.end_fill()
    rory.penup()
    rory.goto(150,65)
    rory.setheading(90)
    rory.begin_fill()
    rory.color('lightslateblue')
    rory.pencolor('purple')
    shape(rory, 100)
    rory.end_fill()
    
    rory.penup()
    rory.goto(-75,5)
    rory.pendown()
    rory.setheading(0)
    rory.begin_fill()
    rory.color('white')
    rory.pencolor('black')
    pentagon(rory, 50)
    rory.end_fill()
    rory.setheading(108)
    rory.forward(50)
    rory.right(72)
    rory.begin_fill()
    rory.color('hotpink')
    rory.pencolor('black')
    triangle(rory, 50)
    rory.end_fill()
    rory.left(90)
    rory.forward(50)
    rory.right(72)
    rory.begin_fill()
    rory.color('hotpink')
    rory.pencolor('black')
    triangle(rory, 50)
    rory.end_fill()
    rory.penup()
    rory.setheading(270)
    rory.forward(30)
    rory.right(90)
    rory.forward(15)
    rory.pendown()
    rory.setheading(0)
    rory.begin_fill()
    rory.color('yellow')
    rory.pencolor('black')
    rory.circle(5)
    rory.end_fill()
    rory.penup()
    rory.setheading(0)
    rory.forward(30)
    rory.pendown()
    rory.begin_fill()
    rory.color('yellow')
    rory.pencolor('black')
    rory.circle(5)
    rory.end_fill()
    rory.setheading(270)
    rory.penup()
    rory.forward(10)
    rory.setheading(180)
    rory.forward(10)
    rory.pendown()
    rory.setheading(180)
    rory.begin_fill()
    rory.color('hotpink')
    rory.pencolor('hotpink')
    triangle(rory, 10)
    rory.end_fill()
    rory.setheading(240)
    rory.forward(10)
    rory.setheading(270)
    rory.pencolor('black')
    rory.forward(10)
    rory.setheading(145)
    rory.penup()
    rory.forward(15)
    rory.setheading(270)
    rory.pendown()
    rory.circle(13,180)
    rory.penup()
    rory.backward(27)
    rory.setheading(180)
    rory.forward(40)
    rory.pendown()
    rory.setheading(0)
    rory.begin_fill()
    rory.color('white')
    rory.pencolor('black')
    rectangle(rory,150,50)
    rory.end_fill()
    rory.setheading(0)
    rory.forward(33)
    rory.setheading(90)
    rory.forward(3)
    rory.setheading(180)
    rory.begin_fill()
    rory.color('black')
    rory.pencolor('black')
    triangle(rory,10)
    rory.end_fill()
    rory.penup()
    rory.setheading(180)
    rory.forward(18)
    rory.setheading(270)
    rory.forward(53)
    rory.pendown()
    rory.begin_fill()
    rory.color('white')
    rory.pencolor('black')
    rectangle(rory,35,15)
    rory.end_fill()
    rory.forward(135)
    rory.setheading(270)
    rory.begin_fill()
    rory.color('white')
    rory.pencolor('black')
    rectangle(rory,35,15)
    rory.end_fill()
    rory.setheading(90)
    rory.forward(50)
    rory.left(90)
    rory.forward(10)
    rory.setheading(90)
    rory.begin_fill()
    rory.color('white')
    rory.pencolor('black')
    rectangle(rory, 75, 10)
    rory.end_fill()
    
    rory.color('black')
    rory.penup()    
    rory.goto(-200,-150)
    rory.pendown()
    rory.pencolor('blue')
    draw_p(rory)
    rory.left(90)
    rory.forward(15)
    rory.left(90)
    jump(rory, 40)
    draw_i(rory)
    rory.right(90)
    jump(rory, 25)
    rory.setheading(0)
    jump(rory,20)
    draw_e(rory)
    rory.right(90)
    jump(rory,25)
    rory.setheading(0)
    jump(rory, 25)
    draw_r(rory)
    rory.setheading(0)
    jump(rory, 25)
    draw_r(rory)
    rory.setheading(0)
    jump(rory, 25)
    draw_e(rory)
    jump(rory, 50)
    
    input('Press enter to end.')  # keeps the turtle graphics window open

if __name__ == '__main__':
    main()
