# task1
check if age is valid or not task 2 age should be always float task 3 create a func that usea boolean data type to check if output true or false task 4 if age is less than 12 you are child, if age is 12 you are semi considerate child task 5 if age is 12 and 20 you are teenager and if your age is 18 and 20 you are adult and teenager

def valid_age():
 age = float(input("Enter your age"))
 if age<0:
  print ("invalid age")
  is_active = false
 elif age<12:
  print ("you are child")
  
 elif age==12:
  print("you are semi-considerate child")
  
 elif age>12 and age<20:
  print ("you are a teenager")
  
 else:
  print ("you are an adult")
  

 return(age)
valid_age()
