from random import # массив с рандомными числами
numbers = [] #массив
for i in range
print(numbers)
index = 0
sum = 1
while index < len9numbers):
   if numbers[index] %3 == 0;
      sum= sum*numbers[index]
   else:
   if numbers[index] %5 == 0;
      sum=sum*numbers[index]
if sum ==1
   sum=0
print(sum)      