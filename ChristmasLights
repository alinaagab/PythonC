from sense_hat import SenseHat
from time import sleep

sense = SenseHat()
b = (0,0,255)
p = (204,102,153)
y = (255,255,0)
r = (255,0,0)
g = (0,255,0)
o = (0,255,0)
n = (255,153,102)
w = (255,255,255)

image = [
b,p,y,g,o,n,w,r,
g,w,b,y,p,o,r,n,
b,p,y,g,o,n,w,r,
g,w,b,y,p,o,r,n,
b,p,y,g,o,n,w,r,
g,w,b,y,p,o,r,n,
b,p,y,g,o,n,w,r,
g,w,b,y,p,o,r,n,
]
  
sense.set_pixels(image)
  
while True :
    sleep (0.30)
    sense.flip_h()
