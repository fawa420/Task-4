def calcArea(s):
 Area_of_hexagon= 1.5*1.732*s 
 return Area_of_hexagon
def calcPeri(s):
 Perimeter_of_hexagon= 6*s
 return Perimeter_of_hexagon
def calcAngleSum():
 a=120
 Sum_of_all_the_angles_of_hexagon= 6*a
 return   Sum_of_all_the_angles_of_hexagon
def calcAreaSquare(s):
 length=s+1
 Area_of_square= (length)*2  
 return  Area_of_square
def calcPeriSquare(s):
 length=s+1    
 Perimeter_of_square= 4*length
 return Perimeter_of_square
def display():
  print("Area of Hexagon is :", Area_of_hexagon)
  print("Perimeter of Hexagon is",Perimeter_of_hexagon)
  print("Sum of Angles of hexagon is :",Sum_of_all_the_angles_of_hexagon)
def display2(): 
   print("Area of square is :", Area_of_square)
   print(" Perimeter of square :",Perimeter_of_square)

s=7
print("Enter 1 to calculate area,Perimeter,Sum of all the angles of hexagon :")
print("Enter 2 to calculate area and perimeter of square :")
print("Enter any other key to  exit :")
x=input()
if(x=="1"):
     Area_of_hexagon = calcArea(s)
     Perimeter_of_hexagon = calcPeri(s)
     Sum_of_all_the_angles_of_hexagon = calcAngleSum()
     display()
elif(x=="2"):
     Area_of_square = calcAreaSquare(s)
     Perimeter_of_square = calcPeriSquare(s)
     display2()
else:
     print()
