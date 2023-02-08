### Question 1
1% * 1000000 = 10000

1/10000 = .0001 = .01%


### Question 2
* any outcomes = 1/10 * 1/9 * 1/8 = 1/720
* 10 outcome = 1/10 + 1/9 + 1/8 = 121/360
* odd outcome = 5/10 * 4/9 * 3/8 = 1/12

* 10 or odd outcome = 121/360 + 1/12 = 151/360


### Question 3
* one roll = (1 + 2 + 3 + 4 + 5 + 6)/6 = 21/6 = 7/2 = 3.5 = (6+1)/2
* two rolls = (12+2)/2 = 7
* 100 rolls = (600+100)/2 = 350


### Question 4
1. $P(x,y) = P(x)P(y)$ is true on if X and Y are independent
2. $P(x,y) = P(x|y)P(y)$ is true
3. $P(x,y) = P(x|y)P(y|x)$ is false
4. $P(x) = \sum_y P(x|y)$ is false
5. $P(x) = \sum_y P(x,y)$ is true


### Question 5
$x = \frac{1}{2}y + \frac{1}{2}(x+1)$ and $y = \frac{1}{3}y + \frac{1}{3}(x+2)$

x=4
y=3


### Question 6
1. $2^{xy} = 2^x2^y$ is false
2. $2^{x+y} = 2^x2^y$ is true
3. $2^{x+y} = 2^x+2^y$ is false
4. $\log{3^x} = \log{3}\log{x}$ is false
5. $\log{3^x} = x\log{3}$ is true
6. $\log{3^x} = 3x$ is false


### Question 7
* An operation in a linked list is O(n)
* An operation in a hashtable is O(1)


### Question 8
let an odd integer = 2k-1 where k is an integer
let F(n) = 1+3+...+(2n+1) where n is an integer

Hypothesis: Assume that F(k) = $k^{2}$
Base Case: F(1) = 1 = $1^{1}$ which is true

F(k+1) = F(k) + 2(k+1) - 1
       = $k^{2}$ + 2k + 1
       = $(k + 1)^{2}$

Since the Base case of F(n) = $n^{2}$ where n is 1 is true, and F(k+1) = $(k+1)^{2}$ 
then n is equal to the sum of the first odd integer for all integers greater than 0