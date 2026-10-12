# Bubble-sort-
#bubble sort 
number = [2,6,8,12,16,29]
n = len(number)
for i in range(n-1):
  for j in range (n-i-1):
    if number[j] > number[j+1]:
      number[j],number[j+1] = number[j+1], number[j]
