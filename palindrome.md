#program to check palindrome or not!!
n=input("Enter word,number: ")
w=""
for i in n:
  w=i+w
if(n==w):
  print("palindrome...")
else:
  print("not palindrome...")
  print("try again...")
