## cmpinf0010-lab6-7


Revision Group49


__Group members: Xinge Cai, Yurui Luo, Nick Cao__




In this program, users can input two strings and it will tell users how many vawels and consonants in each string. Vawels include AEIOUY and Consonants include all other letters. We believe this letter is very suitable for primary education.

Everyone is able to edit and make this program better.

**Code explantion**
strenter = input("Please enter a string")
strenter2 = input("Please enter another string") 
  these two code is asking users to input the to sentences they want to check.
##
strleng = len(strenter)
count = 0
  These two codes put sentence into the program and get ready to check the vawels and consonants.
  
for letter in strenter:
    if letter == 'a':
        count = count + 1
    if letter == "e":
        count = count + 1
    if letter == "i":
        count = count + 1
    if letter == "o":
        count = count + 1
    if letter == "u":
        count = count + 1
    if letter == "y":
        count = count + 1
    These codes are check vawels and consonants one letter by one.
    
print("The number of vawels is", count)
print("The number of consonants is", lengaa)
  These code are output the all the results, count stand  for number of vawels and lengaa stand for number of consonants.
