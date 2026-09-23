#Write a Python program which accepts a sequence of comma separated 4 digitbinary numbers as its input and then check whether they are divisible by 5 or not.The numbers that are divisible by 5 are to be printed in a comma separatedsequence.

binary=input()
number=binary.split(",")
result=[]
for i in number:
  decimal=int(i,2)
  if decimal%5==0:
    result.append(i)
print(",".join(result))


#Write a Python program that accepts a sentence and calculate the number of letters and digits.

a=input()
letter=0
digit=0
for i in a:
  if i.isalpha():
    letter+=1
  elif i.isdigit():
    digit+=1
print(letter)
print(digit)

#Write a program which can compute the factorial of a given numbers.The results should be printed in a comma-separated sequence on a single line.

a=int(input())
fact=1
for i in range(1,a+1):
   fact*=i
print(fact)
  
  
