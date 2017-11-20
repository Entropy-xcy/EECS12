# EECS 12 Review
## Generic
1. print function
```
print(a, b, c, sep="", end="")
```
2. General input
```
num = eval(input("Enter Number:"))
```
3. Definite loop run for n times
```
for i in range(n):
```
4. Operators
 * \+ \- \* \/ 
 * ** (power)
 * // (integer division)
 * % (modulo)
 * abs (absolute value)
5. Square root
```
import math
math.sqrt(4)
```
6. If statement
```
if <condition>:
    <body>
```
7. Condition Operator
```
<   <=   ==   >=   >   !=
```
8. Data type
 * int()
 * string()
 * float()
 * boolean()
9. Round function
```
round(3.9)
>>>4
round(3.9154, 2)
>>>3.92
```
10. Simultaneous Assignment
```
<var1?, <var2> = <expr1>, <expr2>
```
11. General definite loop
```
for i in [a, b, c, d]:
    <expr>
```
12. Range function
 * return a list
 * range(start, n, step)
 1. Find the value of 'start'
 2. Find the value of 'step'
 3. if step>0 op='<', else op='>'
 4. Check if "start op n" is true, output start, else loop
 5. Go to step 3
13. Stop a loop
```
break(go to the outer layer)
```
14. List interfaces
 * List.append(x)
 <br>
 append the element x to the list
 * \*
 <br>
 zeros = [0] * 50
 repeat 50 times
 * len(list)
 <br>
 return the length of the list
 * slice the list
 <br>
 lst = [1, 2, 3, 4]
 lst[1:3] = [2, 3]
 * in
 <br>
 ```
 x in list
 ```
 return a boolean value that whether x is in list
 * delete
 ```
 del myList[1:3]
 ```
15. String interfaces
 * \+
 <br>
 connect two string
 * \*
 <br>
 repeat the string
 * string[index]
 <br>
 indexing
 * string[begin:end]
 <br>
 slicing
 * len()
 <br>
 length
 * split
 ```
 >>>'32,24,25,57'.split(',')
 ['32','24','25','57']
 ```
 * \n
 <br>
 Enter: next line
 * string.find(s)
 <br>
 return the index when s first occurs
 * string.count(s)
 <br>
 return the number of the occurence of s
 * string.replace(old, new)
 <br>
 return a string that the old string was replaced by the new string
 <br>
 Attention: you have to use "s = s.replace(old, new)" in order to change s
16. Two dimensional list
```
>>>a = [[1, 2], [3, 4]]
>>>a[1][1]
4
```  
17. File processing
```
file = open('filename')

# return the string of that file
file.read()

# return the next line of the file
file.readline()

# return the list of all lines of the file
file.readlines()

# close the file
file.close()
```

18 ASCII table
```
# @param: the index of the char
# @return: return the char of the index of num
chr(num)

# @param: a char
# @return: return the index of that char
```

19. type function
```
# @return: return the type of x
type(x)
```
20. String formatting
(see slide for details...)
