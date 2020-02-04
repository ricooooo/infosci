#this is my jiournal

-2020.2.4-the second class-

1.what did you do
 
 how to make colored circle 
 how to make different size circles.
 

2.what did you learn

def setup():
  size (1000,1000)
  background(230)
  textAlign(CENTER)


def draw():
    print("")
    
def mouseClicked():
  x = mouseX 
  y = mouseY
  r = 50
  myred = random (100,255)
  mygreen = random (150,250)
  myblue = random (250,300)
  fill(myred, mygreen, myblue)
 
  circle (x,y,r)
  fill(0)
  textSize(r/3);
  text("HiHi", x,y)
  
  print(x,y)
 

#Home work
how to make the line to the center from the circle
add line from circle for circles
