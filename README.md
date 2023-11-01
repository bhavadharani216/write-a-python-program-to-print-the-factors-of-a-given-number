# write-a-python-program-to-print-the-factors-of-a-given-number

print("Enter number.")
num=int(input())
print("The factors of",num,"are...")
for i in range(1,num + 1):
   if num %i == 0:
      print(i)
