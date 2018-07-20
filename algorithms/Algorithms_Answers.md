Add your answers to the Algorithms exercises here.

I.

a.  O(n) = O(n^3)/O(n^2)  they cancel each other out for O(n)


b. O(log n) ,ignore the x and keep halving 


c. O(sqrt(n))


d. O(n^3)


e. O(n)


f. O(n)


g. ?


II.

a.

minVal = a[0]
maxDiff = 0

for i in l ...n:
   minVal = min(minVal, a[i])
   maxDiff = max(maxDiff, a[i] - minVal)
   
return maxDiff

b.

Use a binary search for O(log(n)) solution of optimal egg dropping height


III

a.


[6, 1, 8, 14, 2]
[1,2][6][8,14]
[1,2,6,8,14]
 
O(n^2)

[1, 2, 3, 4, 5, 6, 7]
[][1][1, 2, 3, 4, 5, 6, 7]


[][1][2, 3, 4, 5, 6, 7]


b.

O(n log(n))



