# Making-a-set-and-finding-words-in-it.
This is python program to make a set and find ford in it given by user


'''This python program will help user to give input from which the pythob program will search for the word in it.
If you feel any error in the code then you can fork it and send me a pull request.
'''
# Here is the code:
name = ["Yashwant", "Kirti", "Ram", "Shyam"]  # You can also add more names.
user = input("Enter your names to search\n")

if user in name:   # Here i have used the conditional operators.
    print("Their is a match for your word")
else:
    print("No match found!")
    print("Try again Sir!!!")    

