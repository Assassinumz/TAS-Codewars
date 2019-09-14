# C++ Question Set

<h4>Question 1</h4>
What is the output of the following program?

```cpp
#include<iostream>
using namespace std;
int main()
{
    cout<<-1-1-1;
    return 0;
}
```
<br>

<h4>Question 2 </h4>
Write the output of the following program?

```cpp
int main()
{
    int a = 10;
    int b, c;
    b = a++;
    c=a;
    cout<<a<<b<<c;
    return 0;
}
```
<br>

<h4>Question 3 </h4>
What's the difference between thses 2 statements?
<br><br>
#include<iostream>
#include "iostream"
<br><br>

<h4>Question 4</h4>
What library does `sizeof()` belong to?
<br><br>

<h4>Question 5</h4>
What would the output of the following code snippet be?

```cpp
for(int i = 0 ; ; i=(i+1)%2)
{
    cout<<i<<endl;
}
```
<br>

<h4>Question 6</h4>
Debug the following code to find factorial of the number using Recursion

```cpp
int f=0;
int Fact(int d)
{
    if(d>1)
    {
        f=f*d;
        return(Fact(d-1));
    }
    else
    return f-1;
}
```
<br>

<h4>Question 7</h4>
Write a code snippet that prints the line "Hello World" without the use of a semicolon
<br>
<br>

<h4>Question 8</h4>
What is the output of the following code snippet?

```cpp
int i = 1, j = 10;
do
{
    if(i++ > --j)
    {
        continue;
    }
}while(i<5);
cout<<i<<j;
```
<br>

<h4> Question 9</h4>
What exactly is the difference between an endl and a `\n`
<br>
<br>


<h4> Question 10</h4>
Write the output of the following snippet?

```cpp
int x, y, res;
x = 200, y = 100;
res = x+y>2000 ? 5000-x : 2000+x+y;
cout<<res;
```
<br>

<h4> Question 11</h4>
Write the output of the following program?

```cpp
int main()
{
    int a=1;
    switch(a)
    {
        case 1:
                cout<<"One";
        case 2:
                cout<<"Two";
        case 3:
                cout<<"Three";
        default:
                break;
    }
}
```
<br>

<h4> Question 12</h4>
Which of the following is an invalid variable name?
<br><br>
(A) abc123
(B) a_bc12
(C) _abc123
(D) 1abc23
<br><br>

<h4> Question 13</h4>
Rewrite the code snippet removing all the error. Marks will not be awarded if a correct line is rewritten differently.

```cpp
#include<iostream>
using namespace std;
int main()
{
    int a = 10.7;
    int b = 23;
    double c = a+b;
    cout>>c>>endl;
    return 0;
}
```
<br>

<h4> Question 14</h4>
What is the output of the following code snippet? If there's any error, explain the error.

```cpp
int* greater(int a, int b)
{
    if(a>b)
            return &a;
    else
            return &b;
}
int main()
{
    int a=10,b=8;
    int* c=greater(a,b);
    cout<<*c;
    return 0;
}
```
<br>

<h4> Question 15</h4>
State two differences between a class and a struct (Be as brief as possible)
<br>
<br>

<h4> Question 16</h4>
What does the following function do?

```cpp
int a(int* b, int L){
    if(!L)
            return 0;
    return b[0]+a(b+1, L-1);
}
```
<br>

<h4> Question 17</h4>
What is the output of the following program?

```cpp
int main()
{
    int t=10;
    while(t--)
            cout<<t;
    return 0;
}
```
<br>

<h4> Question 18</h4>
What is the output of the following program?

```cpp
int main()
{
    cout<< 1 && 0 && 3;
    return 0;
}
```
<br>

<h4>Question 19</h4>
What is the output of the following program?
<br><br>

```cpp
int main()
{
    cout << "\"Codewars!\"";
    return 0;
}
```
<br>

<h4> Question 20</h4>
Find the odd one out:
<br><br>
(A) ios::out<br>
(B) ios::app<br>
(C) ios::ate<br>
(D) ios::trunc
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
Answer: -3
<br>
<br>

<h4> Solution 2</h4>
Answer: 111011
<br>
<br>

<h4> Solution 3</h4>
Answer: #include<iostream.h> is used for system header, while #include "iostream" looks for the header file in the current working directory.
<br>
<br>

<h4> Solution 4</h4>
Answer: iostream
<br>
<br>

<h4> Solution 5</h4>
Answer: 1<br>
0<br>
1<br>
0<br>
...
<br>
<br>

<h4> Solution 6</h4>
Answer: N/A
<br>
<br>

<h4> Solution 7</h4>
Answer: 

```cpp
int main()
{
switch(printf("hello world")){}
return 0;
}
```
<br>

<h4> Solution 8</h4>
Answer: 56
<br>
<br>

<h4> Solution 9</h4>
Answer: endl is manipulator while \n is character. endl doesn't occupy any memory whereas \n is character so It occupy 1 byte memory.
<br>
<br>

<h4> Solution 10</h4>
Answer: 2300
<br>

<h4> Solution 11</h4>
Answer: OneTwoThree
<br>
<br>

<h4> Solution 12</h4>
Answer: (D) 1abc23
<br>
<br>

<h4> Solution 13</h4>
Answer:

```cpp
#include<iostream>
using namespace std;
int main()
{
    float a = 10.7;
    int b = 23;
    double c = a+b;
    cout<<c<<endl;
    return 0;
}
```
<br>

<h4> Solution 14</h4>
Answer: N/A
<br>
<br>

<h4> Solution 15</h4>
Answer: A class can hold both data members and member functions while a struct can contain only variables
<br>
<br>

<h4> Solution 16</h4>
Answer: N/A

<br>
<br>

<h4> Solution 17</h4>
Answer: 9876543210
<br>
<br>

<h4> Solution 18</h4>
Answer: 1
<br>
<br>

<h4> Solution 19</h4>
Answer: "Codewars!\"
<br>
<br>

<h4> Solution 20</h4>
Answer: N/A

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
