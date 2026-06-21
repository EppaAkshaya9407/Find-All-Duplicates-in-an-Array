# Find-All-Duplicates-in-an-Array
from collections import Counter
nums=list(map(int,input("Enter numbers separated by space:").split()))
cunt=Counter(nums)
r=[]
for i,c in count.items():
    if c==2:
        r.append(i)
print(r)
