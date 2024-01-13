#a. Write a program that checks if a number entered by the user is even or odd.
num = float(input("Enter your number : "))
if num % 2 == 0:
    print (f"{num} this number is even")
else:
    print (f"{num} this number is odd")  
#b. Create a program that asks the user for their age and then determines if they are eligible to vote (considering the legal voting age is 18)    
age = int(input("Enter your age : "))
vote_age = 18
if age >= vote_age :
    print(f"{age} is able to vote")
else:
    print(f"{age} is unable to vote")    
#d. Create a program that takes two numbers from the user and determines which one is greater or if they are equal.
num1 = int(input("Enter your number : "))
num2 = int(input("Enter your number : "))
if num1 > num2 :
    print(f"{num1} is greater than {num2}")
elif num2 > num1:
    print (f"{num2} is greater than {num1}")
else:
    print(f"{num1} and {num2} are equal !")       
#e. Write a program that asks the user for their grade and then prints out whether they've passed (grade >= 60) or failed.
grade = float(input("Enter your grade : "))
passmark=60
if grade >= passmark:
    print("You have passed")
else:
    print("You Have faild")    
#f.Create a program that determines if a given year is a leap year or not.
year = float(input("Enter Year : "))
if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
    print(f"{year} is leap year")
else:
    print(f"{year} is not leap year")    
#h.Develop a program that takes a user input for a number and checks if it's positive, negative, or zero.
num=float(input("Enter your number : "))
if num > 0:
    print(f"{num} is positive number")
elif num < 0 :
    print(f"{num} is negetive number")
else:
    print(f"{num} is equal")        
#i. Create a program that asks the user for three numbers and finds the largest among them.
num1=float(input("Enter number : "))
num2=float(input("Enter number : "))
num3=float(input("Enter number : "))
large_num = max(num1,num2,num3)
print(f"{large_num} is largest number")
#j. Write a program that determines whether a given character is a vowel or a consonant.
word = str(input("Enter word : "))
if word.lower() in 'aeiou':
    print(f"{word} is vowel")
elif word.isalpha():
    print(f"{word} is consonant")
else:
    print(f"{word} is not a vaild word")        
#l. Create a program that asks the user for their exam score and determines their grade (A, B, C, D, or F) based on the score.
mark = float(input("Enter your mark: "))
if mark >= 80 and mark <= 100:
    print("A+")
elif mark >= 70 and mark <= 79:
    print("A")    
elif mark >= 60 and mark <= 69:
    print("A-")    
elif mark >= 50 and mark <= 59:
    print("B")    
elif mark >= 40 and mark <= 49:
    print("C")    
elif mark >= 33 and mark <= 39:
    print("D")    
elif mark >= 0 and mark <= 32:
    print("F")
else:
    print(f"{mark} is invaild !")        


    


  
