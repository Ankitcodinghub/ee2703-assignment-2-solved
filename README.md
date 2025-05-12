# ee2703-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [EE2703 Assignment 2 Solved](https://www.ankitcodinghub.com/product/ee2703-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;90819&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE2703 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

1 Introduction

In the last assignment, we have seen the basics of python. In this assignment, you will get introduced to scientific python. Make sure you have completed all the previous homework as well as the assignment before getting started with this assignment.

2 OOP and Python

Just like C++, classes help you implement OOP in Python. Classes are the blueprint of objects. They specify what the object can have. For example, say you have a class for Player. The class will tell you that your object has a property named “position”. But does not say what the “position” is. This is useful since a class can parent as many different objects as you want. Each object can have a different “position”.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [1]: class Player:
</pre>
<ul>
<li>
<pre>   ...: &nbsp;    position_x = 0
</pre>
</li>
<li>
<pre>   ...: &nbsp;    position_y = 0
</pre>
</li>
</ul>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>...:
...:
...:
...:
...:
...:
</pre>
</div>
<div class="column">
<pre>def __init__(self, color):
    self.color = color
</pre>
<pre>def move(self, distance, direction):
    if direction == ’right’:
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>...:
...:
...:
</pre>
</div>
<div class="column">
<pre>    self.position_x += distance
elif ...
</pre>
…

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Here, we defined a class Player. Let’s go line by line. 1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
1. The first line says the it’s a definition of a class and the name of the class is Player

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>The next two lines define features of the class. The player has x and y positions. These values are set to 0 by default.</li>
<li>init () is the constructor. The first argument to it is always self. self refers to the object itself!</li>
<li>The constructor takes in one extra argument color. The interesting thing here is that, the constructor is declaring a new feature for the class at run-time! In python, you can add features to an object dynamically!</li>
<li>move() here is a member function of the class. Note that the first argument to a member function should be self.</li>
</ol>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
In [2]: p1 = Player(’red’) # Creating a player object In [3]: p1.position_x

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Out[3]: 0

In [4]: p1.move(2, ’right’) # Calling a member function

<pre>In [5]: p1.position_x
Out[5]: 2
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Note that, we did not provide the parameter self here. Since first argument to member function is always self, Python passes it automatically.

Though we are seeing Python classes for the first time, you have been using the power of classes even without realizing it. For example, lists that you have been creating are actually objects of the class “List”.

Here, you are creating an object of the class list in the first line ([…] is the constructor here) and calling a member function of the object in the second line.

3 List unpacking

One peculiar thing about Python is that you can return multiple values from a function!

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>In [6]: l = [1, 4, 5, 2, 3]
In [7]: l.sort()
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>In [8]: def f():
   ...:     return 1, 2, 3, 4
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [9]: r = f(); r
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Out[9]: (1, 2, 3, 4)
In [10]: w, x, y, z = f()
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
f() is returning four values here. How the returned values get stored is heavily depended on the calling statement. In the first call to f(), Python will compile all the return values and give to us a tuple. But in the next call, return values are assigned to separate variables in the order mentioned. What will happen if you try x, y = f()? What about x, *y, z = f() ? This is called extended unpacking.

Python goes even further:

What are the values of i and j now?

3.0.1 Homework

Given a list

How can you extract the first character of ’hello’ only by using list unpacking? Do it in single statement.

4 Scientific Python

What makes python amazing is the huge collection of modules that come with it. For example, Modules like scipy, numpy, matplotlib, sympy and panda make it suitable for scientific com- puting. numpy helps with numerical computations, scipy provides special functions that will help you with scientific computing and also adds complex number support to all the functions. matplotlib provides sophisticated plotting capabilities.

Most of the underlying implementations of these libraries are in C. This ensures the efficiency of these implementations. But to make your life easy, these C implementations are wrapped in Python and given as python functions which you can directly call from python. Which means they are efficient at the same time easy to use.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [11]: a, b, c = [1, 2, 3]
In [12]: i = 1; j = 2
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [13]: i, j = j, i
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
<pre>l = [ [1, 2], ’hello’ ]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
4.1 Arrays vs Lists

</div>
</div>
<div class="layoutArea">
<div class="column">
While Python lists are amazing by themselves, they are not always the best data type to depend. The flexibility they provide makes them slow. To make things faster, numpy provides array data type. numpy arrays are lot similar to C arrays. As I already mentioned, the speed come from the fact that the underlying implementation is in C.

Let’s see some examples of arrays:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [14]: from numpy import *
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
In [15]: array(range(10))

Out[15]: array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9]) # Note the way it is printed. # The output is explicitly telling you that this is an array and not a list.

<pre>In [16]: A = array([[1,2,3],[4,5,6],[7,8,9]]); A
Out[16]:
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>array([[1, 2, 3],
       [4, 5, 6],
</pre>
[7, 8, 9]])

In [17]: A * 10 # Multiplication with a scalar

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Out[17]:

<pre>array([[10, 20, 30],
       [40, 50, 60],
</pre>
[70, 80, 90]])

In [18]: A * A # Element by element multiplication

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Out[18]:

<pre>array([[ 1,  4,  9],
       [16, 25, 36],
</pre>
<pre>       [49, 64, 81]])
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
In [19]: A + 10 # Addition with a scalar Out[19]:

array([[11, 12, 13],

<pre>       [14, 15, 16],
       [17, 18, 19]])
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
In [20]: A + A # Addition with a vector Out[20]:

array([[ 2, 4, 6],

<pre>       [ 8, 10, 12],
       [14, 16, 18]])
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
In [21]: ones(10) # Try “ones?” and see what does it do Out[21]: array([1., 1., 1., 1., 1., 1., 1., 1., 1., 1.])

<pre>In [10]: B = array([ones(3) for i in range(3)]); B
Out[10]:
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>array([[1., 1., 1.],
       [1., 1., 1.],
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>       [1., 1., 1.]])
</pre>
<pre>In [22]: dot(A,B)
Out[22]:
array([[ 6.,  6.,  6.],
</pre>
<pre>       [15., 15., 15.],
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>[24., 24., 24.]])
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Now, try out the same operations with lists and see what happens. Here is an example:

arrays will give you what a mathematician would expect, while list is more for a general programming use. Arrays are quite fast compared to lists. Here are some important facts about arrays:

<ul>
<li>Array elements are all of one type, unlike lists. This is precisely to improve the speed of computation.</li>
<li>An array of integers is different from an array of reals or an array of doubles. So you can also use the second argument to create an array of the correct type.

Eg:</li>
<li>Arrays are stored row wize by default. This can be changed by setting some arguments in numpy functions. This storage is consistent with C.</li>
<li>The size and shape methods give information about arrays. In above examples,
size gives the number of elements in the array. shape gives the dimensions while len gives only the number of rows.
</li>
<li>Arrays can be more than two dimensional. This is a big advantage over Matlab and its tribe. Scilab has hypermatrices, but those are slow. Here arrays are intrinsically multi-dimensional</li>
</ul>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>In [23]: a = [list(i) for i in A]; a
Out[23]: [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
</pre>
<pre>In [24]: a + a
Out[24]: [[1, 2, 3], [4, 5, 6], [7, 8, 9], [1, 2, 3], [4, 5, 6], [7, 8, 9]]
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>x=array([[1,2],[3,4]], dtype=complex)
</pre>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
x.size # returns 4 x.shape # returns (2, 2) len(x) # returns 2

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
• The dot operator does tensor contraction. The sum is over the last dimension of the first argument and the first dimension of the second argument. In the case of matrices and vectors, this is exactly matrix multiplication.

Note that numpy also has a matrix data type. But this is not recommended to use. In fact, the community is planning to remove it in future.

4.2 where()

Sometimes we want to know the indices in a matrix that satisfy some condition. The method to do that in Python is to use the where command. To find the even elements in the above matrix we can do:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [25]: A=array([[1,2,3],[4,5,6],[7,8,9]]);A
Out[25]:
array([[1, 2, 3],
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>       [4, 5, 6],
       [7, 8, 9]])
</pre>
In [26]: coords = where(A%2==0) # Returns the coords of even elements In [27]: coords # This is a tuple

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Out[27]: (array([0, 1, 1, 2]), array([1, 0, 2, 1]))
In [28]: i, j = where(A%2==0)
In [29]: B=array([[6,6,6],[4,4,4],[2,2,2]])
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [30]: i, j = where((A&gt;3)&amp;(B&lt;5)&gt;0)
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
What does the last line here do? Break it down to pieces and understand what each piece does. Can you replace the &amp; with and? Why not?

Here is another peculiar thing about arrays.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [31]: A
Out[31]:
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>array([[1, 2, 3],
       [4, 5, 6],
</pre>
<pre>       [7, 8, 9]])
In [32]: i, j = where(A%2==0); i
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Out[32]: array([0, 1, 1, 2])
</pre>
<pre>In [33]: j
Out[33]: array([1, 0, 2, 1])
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [34]: A[i, j]
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Out[34]: array([2, 4, 6, 8])
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Notice what is happening in the last command. Can you do the same with lists?

4.2.1 Homework

• Explain what is happening in the last command here to your TA.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [35]: A
Out[35]:
array([[1, 2, 3],
</pre>
<pre>       [4, 5, 6],
       [7, 8, 9]])
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [36]: A[i][j]
Out[36]:
array([[4, 5, 6],
</pre>
[1, 2, 3],

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>[4, 5, 6],
[4, 5, 6]])
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
• Generate an array (of shape (3,3)) of random numbers.

5 Solving Linear Equations

Solving linear equations are quite simple using numpy. Let’s try and solve:

3×0 + x1 = 9 (1)

</div>
</div>
<div class="layoutArea">
<div class="column">
The above equation can be written as:

Where,

</div>
<div class="column">
x0 + 2×1 = 8 (2) Ax = b (3)

􏰀3 1􏰁

A=12 (4)

􏰀 x1 􏰁

x=x (5)

2

􏰀9􏰁

b=8 (6)

</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
All you need to do is to create the matrices:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [37]: import numpy as np
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [38]: A = np.array([[3,1], [1,2]]); A
Out[38]:
array([[3, 1],
</pre>
[1, 2]])

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>In [39]: b = np.array([9,8]); b
Out[39]: array([9, 8])
</pre>
<pre>In [40]: x = np.linalg.solve(A, b); x
Out[40]: array([2., 3.])
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
The numpy.linalg.solve() solved the set of equations for us.

Note that the first line is same as “import numpy”. But “as np” here allows you to write

np.array() instead of numpy.array(). This is simply to save some typing efforts.

6 Spice – Part 2

In the last assignment, we read a netlist file and parsed it. In this assignment, we will solve the circuits. We have n node voltages (say Vi ; i = 0 to n − 1) and k currents (say Iij ) (the currents through the k voltage sources). The system of equations are:

1. n KCL equations at the n nodes.

2. k equations of the type Vi − Vj = εij for nodes connected by voltage sources.

As long as a loop consisting purely of voltage sources or a node connected purely to current sources does not exist, a unique solution is possible. Write the equations in the form

</div>
</div>
<div class="layoutArea">
<div class="column">
The node equations take the form

</div>
</div>
<div class="layoutArea">
<div class="column">
A·V⃗ +B·I⃗=⃗b (7) 􏰂Vi −Vj +􏰂Iij =−􏰂Iij (8)

</div>
</div>
<div class="layoutArea">
<div class="column">
Zij

where the first sum is over the passive branches, the second sum over voltage sources and the

</div>
</div>
<div class="layoutArea">
<div class="column">
third sum is over current sources. The auxiliary equations take the form

Vi − Vj = Eij (9) The dependent sources have similar equations that you can easily derive for yourself.

</div>
</div>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
<ul>
<li>Explain how a loop consisting purely of voltage sources will result in the system of equations becoming inconsistent.</li>
<li>Explain how a node connected purely to current sources will result in the system of equations becoming inconsistent.
Now, write the equation 7 in the following form:

Mx = b (10)
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
i.e.,

</div>
</div>
<div class="layoutArea">
<div class="column">
7

1.

2.

</div>
<div class="column">
Assignment

Parse the netlist and create list(s) of different components. You may define class(es) for components and create objects for each component to store them nicely. Component name, connected nodes, value etc… can be the features of this(these) class(es). Remember that list elements can be class objects too.

Create a table of distinct nodes present in the circuit. Assign numbers to the nodes so that they correspond to the rows (columns) of the incidence matrix. You may use a dictionary for doing this. You could then store the node number as the value with the node name as the key.

Note: You can assume that ground node is always named as GND. The ground node will add an extra equation:

Vk = 0 (12) where k is the node number of GND. You may keep it as V0 always.

Construct matrices M and b using numpy arrays.

Solve the equation Mx = b.

Print all the unknowns. (All node volatges and current through voltage sources) Solve the following circuits with your program:

</div>
</div>
<div class="layoutArea">
<div class="column">
3. 4. 5. 6.

</div>
</div>
<div class="layoutArea">
<div class="column">
a11 … a1n b11 … b1k V1  I1  … … … … … …… … an1 … ann bn1 … bnk Vn  In 

</div>
</div>
<div class="layoutArea">
<div class="column">


 …

</div>
<div class="column">


… … 0 0 0I1=E1 (11)

</div>
</div>
<div class="layoutArea">
<div class="column">
 …

… …

</div>
<div class="column">
0 0 0 0

</div>
<div class="column">
0  …   …  0 Ik Ek

</div>
</div>
<div class="layoutArea">
<div class="column">
… … …

</div>
</div>
<div class="layoutArea">
<div class="column">
This matrix needs to be solved to obtain currents and voltages.

Note that this can be readily solved using the method specified in section 5.

</div>
</div>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
(a) A simple resistive circuit (use RL = 1, 10 and 100Ω)

</div>
</div>
<div class="layoutArea">
<div class="column">
n1

10V +−

n0

</div>
<div class="column">
R1 = 2Ω

</div>
<div class="column">
n2

</div>
<div class="column">
R3 = 5Ω

R2=3Ω

</div>
<div class="column">
n3

RL

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1: Resistive circuit

</div>
</div>
<div class="layoutArea">
<div class="column">
7. Can you use the same techniques to solve for ac circuits? We only have to interpret the impedance as complex numbers and the solution will follow. We will only work with circuits with single frequency at steady state.

Till now, we only had a single command in the netlist (.circuit … .end). We now allow a new command .ac.

This is a single line command. It will appear after the .circuit … .end block and specify the frequency of a voltage source.

We will also modify the way voltage source and current values are given. We will use the following representations:

Similar representations will follow for current sources. Solve the following circuits:

(a) A band-pass filter for the current in the resistor

</div>
</div>
<div class="layoutArea">
<div class="column">
GND

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>.ac  V...  frequency
</pre>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
V… n1 n2 ac Vp−p phase # ac voltage source V… n1 n2 dc v # dc voltage source

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
10

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
1.0 F 1.0 kΩ

n1 n2 n3

5 Vp−p

0 Voffset 1 kHz

</div>
<div class="column">
1.0 μH

</div>
</div>
<div class="layoutArea">
<div class="column">
n0

</div>
<div class="column">
GND

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 2: Band-pass filter

(b) A low-pass filter, for the voltage across the load resistor

</div>
</div>
<div class="layoutArea">
<div class="column">
n1

n0

</div>
<div class="column">
4.5 kΩ

Vp−p = 1 0 Voffset 1 kHz

</div>
<div class="column">
n2

</div>
<div class="column">
80.96 μH

2.485 pF

</div>
<div class="column">
n3

</div>
<div class="column">
80.96 μH n4

GND

</div>
</div>
<div class="layoutArea">
<div class="column">
4 kΩ

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 3: Low-pass filter

</div>
</div>
<div class="layoutArea">
<div class="column">
Submit a single program on Moodle. It should be able to solve ac as well as dc circuits.

</div>
</div>
<div class="layoutArea">
<div class="column">
11

</div>
</div>
</div>
