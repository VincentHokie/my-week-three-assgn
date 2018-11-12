# my-week-three-assgn
coding with python
#The current year is declared so as to be able to calculate the age
current_year=int (2018)
#This is to allow the user input his birth year
user_input=int(input("enter your birth year please"))
result=int(current_year - user_input)
#The conditional logic
if result < 18:
    print("You are a minor")
elif result > 18 and result < 36:
    print("you are a youth")
else:
    print("you are an elder")
