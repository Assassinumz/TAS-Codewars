# Python Question Set

<h4>Question 1</h4>
What is the output of the following code snippet :

```python
a = (1, 2)
a[0] += 1
```
(A) (1, 1, 2)<br>
(B) 2<br>
(C) Type Error<br>
(D) Syntax Error
<br><br>

<h4>Question 2 </h4>
Write the output of the following code snippet :

```python
a = 4.5
b = 2
print (a//b)
```
(A) 2<br>
(B) 2.0<br>
(C) 2.25<br>
(D) 0.5
<br><br>

<h4>Question 3 </h4>
Write the output for the following

```python
a = True
b = False
c = False

if a or b and c:
    print("CODEWARS")
else:
    print("codewars")
```
<br>

<h4>Question 4</h4>
What is the output of the following program?

```python
for i in [1, 2, 3, 4][::-1]:
    print(i)
```
<br>

<h4>Question 5</h4>
Write the output of the following

```python
nameList = ["Aditeya", "Ashwin", "Sourav", "Shishir"]
print(nameList[1][-1])
```
<br>

<h4>Question 6</h4>
Write a list comprehension for producing a list of numbers between 1 and 1000 that are divisible by 3.<br><br>
(A) [x in range(1, 1000) x%3==0]<br>
(B) [x for x in range(1000) if x%3==0]<br>
(C) [x%3 for x in range(1, 1000)]<br>
(D) [x%3=0 for x in range(1, 1000)]
<br>
<br>

<h4>Question 7</h4>
What is the output of the following code?

```python
a={}
a[2]=1
a[1]=[2,3,4]
print(a[1][1])
```
(A) [2,3,4]<br>
(B) 3<br>
(C) 2<br>
(D) An exception is thrown
<br>
<br>

<h4>Question 8</h4>
When the below code is executed in python the output obtained is:<br>

```python
print(0.1+0.2-0.3==0)
```
(A) True<br>
(B) False<br>
(C) Error<br>
(D) 0
<br>
<br>

<h4> Question 9</h4>
What does the following code snippet return?

```python
try:
    return 1
except:
    return 2
finally:
    return 3
```
(A) 1<br>
(B) 2<br>
(C) 3<br>
(D) Syntax error
<br>
<br>

<h4> Question 10</h4>
Write a function to split a string and convert it into an array of words.<br>

Eg: `"i love codewars" = ["i", "love", "codewars"]`
<br>
<br>
<h4> Question 11</h4>
Write the output

```python
r = lambda q: q * 2
s = lambda q: q * 3
x = 2
x = r(x)
x = s(x)
x = r(x)
print(x)
```
<br>

<h4> Question 12</h4>
Write the output for the following code snippet :

```python
count = 1
def doThis():
    global count
    for i in (1, 2, 3):
        count += 1
doThis()
print(count)
```
<br>

<h4> Question 13</h4>
Choose the right option :

```python
s=["cppbuzz Chicago"]
print(s[3:5])
```
(A) pbuzz<br>
(B) buzzc<br>
(C) bu<br>
(D) None of these
<br>
<br>

<h4> Question 14</h4>
Which statement is correct?
<br><br>
(A) List is mutable, and Tuple is immutable<br>
(B) List is immutable, and Tuple is mutable<br>
(C) Both are Immutable<br>
(D) Both are Mutable
<br>
<br>

<h4> Question 15</h4>
What is the output of the following code snippet?

```python
s = 'mnopqr'
i = 'm'
while i in s:
    print('i', end=' ')
```
(A) i i i i i....<br>
(B) m m m m m....<br>
(C) m n o p q r<br>
(D) no output
<br>
<br>

<h4> Question 16</h4>
what is the output for the following code snippet?

```python
name="Hello World"
print(type(name))
```
(A) Hello World<br>
(B) hello world<br>
(C) <class 'str'><br>
(D) str
<br>
<br>

<h4> Question 17</h4>
Suppose list1 is [3, 4, 5, 20, 5, 25, 1, 3], what is list1 after list1.pop(1)?
<br><br>
(A) [3,4,5,20,5,25,1,3]<br>
(B) [1,3,3,4,5,5,20,25]<br>
(C) [3,5,20,5,25,1,3]<br>
(D) [1,3,4,5,20,5,25]
<br>
<br>

<h4> Question 18</h4>
What is the output of the following code snippet?

```python
a=lambda x: len(x) and x[0]+a(x[1:])
s=[5,2,7,9]
print(a(s))
```
<br>

<h4>Question 19</h4>
Choose the correct code to convert only the first letter of word 'codewars' to upper case
<br><br>
(A) .upper()<br>
(B) .lower()<br>
(C) .title()<br>
(D) .capital()
<br>
<br>

<h4> Question 20</h4>
How do you import module from a sub package of a package?
<br><br>
(A) from subpackage() import module<br>
(B) from mainpackage(subpackage) import module()<br>
(C) from mainpackage.subpackage import module<br>
(D) from mainpackage.subpackage() import module()
<br>
<br>

<h4> Question 21</h4>
Complete the sequence<br>
2,9,28,65,126,__?
<br><br>
(A) 187<br>
(B) 217<br>
(C) 242<br>
(D) 344<br>
(E) 355
<br>
<br>

<h4> Question 22</h4>
A clock is started at noon. By 10 minutes past 5, the hour hand has turned through
<br><br>
(A) 155°<br>
(B) 145°<br>
(C) 152°<br>
(D) 140°
<br>
<br>

<h4> Question 23</h4>
If 5@6=61 and 8@10=164, then 7@9=?
<br><br>
(A) 125<br>
(B) 63<br>
(C) 32<br>
(D) 95
<br>
<br>

<h4> Question 24</h4>
Two pipes can fill a tank in 12 minutes and 20 minutes respectively. Both pipes are opened together and after some time the first pipe is closed and the tank is full in totally 10 minutes. For how many minutes was first pipe open
<br><br>
(A) 8 minutes<br>
(B) 6 minutes<br>
(C) 7 minutes<br>
(D) 10 minutes
<br>
<br>

<h4> Question 25</h4>

<img src="https://github.com/Assassinumz/TAS-Codewars/blob/master/Preliminary/FIGURE.png">
<br><br>
These questions are based on the figure given above in which (1) Rectangle represents Males, (2) Circle represents the urbans, (3) Square represents the educated and (4) Triangle represents the civil servants.<br>
The number indicating the uneducated urban males is
<br><br>
(A) 4<br>
(B) 5<br>
(C) 8<br>
(D) 11
<br>
<br>

<h4> Question 26</h4>
There are 12 balls, all of them look identical but one of them is slightly heavier than the rest. You have a weight balance. What is the least number of times you need to use the balance to find the heavier ball ?
<br>
<br>

<h4> Question 27</h4>
You've got someone working for you for seven days and a gold bar to pay them. You must pay the worker for their work at the end of every day. If you are only allowed to make two breaks in the gold bar, how do you pay your worker? (Assuming equal amount of work is done during each dat thus requiring equal amount of pay for each day)
<br>
<br>

<h4> Question 28</h4>
Last day of a century can never be a -
<br><br>
(A) Monday<br>
(B) Tuesday<br>
(C) Wednesday<br>
(D) Friday
<br>
<br>

<h4> Question 29</h4>
Provide an algorithm to find the HCF of 2 numbers, more efficient algorithm carries more points.
<br>
<br>

<h4> Question 30</h4>
A 100-seater flight is about to take off. Each of the 100 passengers are waiting to enter, holding a ticket corresponding to their seat number. You are last in line, the 100th. One of the people in front of you is crazy (but you don't know which one) and will sit in a random empty sear (which might even be his assigned seat). The other passengers will continue to sit in their seats, unless it is alredy occupied, in which case theu go crazy too and sit in a random empty seat. Assuming they don't behave like your typical crowd and get in one by one without a stampede, what is the probability that you'll sit in assigned seat
<br><br>

# Solutions

<h4> Solution 1</h4>
Answer: (C) Type Error
<br>
<br>

<h4> Solution 2</h4>
Answer: (A) 2
<br>
<br>

<h4> Solution 3</h4>
Answer: CODEWARS
<br>
<br>

<h4> Solution 4</h4>
Answer: <br>
4<br>
3<br>
2<br>
1
<br>
<br>

<h4> Solution 5</h4>
Answer: n
<br>
<br>

<h4> Solution 6</h4>
Answer: (B) [x for x in range(1000) if x%3==0]
<br>
<br>

<h4> Solution 7</h4>
Answer: N/A
<br>
<br>

<h4> Solution 8</h4>
Answer: False
<br>
<br>

<h4> Solution 9</h4>
Answer: (D) Syntax error
<br>
<br>

<h4> Solution 10</h4>
Answer: 

```python
def Func(string):
    return string.split() 
```
<br>

<h4> Solution 11</h4>
Answer: 24
<br>
<br>

<h4> Solution 12</h4>
Answer: 4
<br>
<br>

<h4> Solution 13</h4>
Answer: (D) None of these

<br>
<br>

<h4> Solution 14</h4>
Answer: N/A
<br>
<br>

<h4> Solution 15</h4>
Answer: (A) i i i i i....
<br>
<br>

<h4> Solution 16</h4>
Answer: (C) <class 'str'>

<br>
<br>

<h4> Solution 17</h4>
Answer: (C) [3,5,20,5,25,1,3]
<br>
<br>

<h4> Solution 18</h4>
Answer: 23
<br>
<br>

<h4> Solution 19</h4>
Answer: .title()
<br>
<br>

<h4> Solution 20</h4>
Answer: (C) from mainpackage.subpackage import module

<br>
<br>

<h4> Solution 21</h4>
Answer: (C) 242

<br>
<br>

<h4> Solution 22</h4>
Answer: N/A

<br>
<br>

<h4> Solution 23</h4>
Answer: (A) 125

<br>
<br>

<h4> Solution 24</h4>
Answer: N/A

<br>
<br>

<h4> Solution 25</h4>
Answer: N/A

<br>
<br>

<h4> Solution 26</h4>
Answer: 2

<br>
<br>

<h4> Solution 27</h4>
Answer: N/A

<br>
<br>

<h4> Solution 28</h4>
Answer: (B) Tuesday

<br>
<br>

<h4> Solution 29 </h4>
Answer: N/A

<br>
<br>

<h4> Solution 30 </h4>
Answer: N/A

<br>
<br>
