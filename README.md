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
