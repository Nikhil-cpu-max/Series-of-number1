# Series-of-number1
s=int(input("enter your starting number:"))
e=int(input("enter your ending number:"))
u=int(input("enter your increment number:"))
choice=input("h for herizontal and v for vertical what do you want enter")
choice2=input("r for reverse and f for forward")
if choice2=="f":
  if choice=="h":
    for i in range(s,e+1,u):
      print(i,end=" ")
  else:
      for i in range(s,e+1,u):
        print(i)
else:
  if choice=="h":
    for i in range(s,e-1,-u):
        print(i,end=" ")
  else:
    for i in range(i,e-1,-u):
       print(i)
