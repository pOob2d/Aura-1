# Aura

Phase 1
• Shall set-up the Raspberry Pi and configure it for the project
-Done in class already

• Shall demonstrate basic understanding of Python coding
o Create simple unit conversion program
-Select three unit conversions (Examples: Miles to Km, LBS to Kg, celcius to ferhenheit, etc)
unit=input("Enter Unit(km,lbs,grams,miles): ")
if unit=="km":
  km=int(input("enter KM value: "))
  mph = km*.62
  print(mph,"mph")
if unit =="lbs":
  lbs=int(input("enter lbs value: "))
  ounces = lbs*16
  print(ounces,"ounces")
if unit =="grams":
  grams=int(input("enter grams value: "))
  ounces = grams*.035274
  print(ounces,"ounces")
if unit =="miles":
  miles=int(input("enter miles value: "))
  foot = miles*5280
  print(foot,"feet") 
• Shall demonstrate basic understanding of Raspberry Pi I/O
o Configure LED on breadboard 
-mostly done (we still need to add the LED and resistor) 26 resister 220ohms
o Blink LED 
-how often will it blink? Every second
-What color will the LED be? Red

• Shall demonstrate basic understanding of Pygame
o Add a random rectangle to the center of the game screen
-Color? position on screen (x,y)? Size? 
o Add random ball to the top-left corner of the game screen
-Color? position on screen (x,y)? Size? 
o Add text to the top-right of the game screen
-What will it say? What font? What color?
