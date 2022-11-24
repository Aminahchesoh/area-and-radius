# area-and-radius
24.11.22 (aj. Anas)

import math

area = int(input("Enter the area: "))
if area > 0:
  radius = math.sqrt(area / math.pi)
  print ("The radius is", radius)
else:  
  print ("Error: the area must be a positive number")
