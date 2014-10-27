10-27-2014-HW
=============
def gradePrice():
   grade=eval(input("What grade are you in? if you are not in school type 20: "))
   if grade<7:
      return 0
   elif grade>=7 and grade<=8:
      return 5
   elif grade>8 and grade<13:
      return 7
   else:
      return 12

def totalPrice():
   print ("This program tells you the amount of money required to go watch a movie.")
   weather=input("What is the weather today?(sunny, rainy, hailing or snowing?) ")
   if weather=="rainy":
      return gradePrice()-2
   elif weather=="sunny":
      return gradePrice()+2
   elif weather=="hailing":
      return "Free of charge!"
   else:
      return gradePrice()+1.50
