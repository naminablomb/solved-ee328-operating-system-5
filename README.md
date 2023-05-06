Download Link: https://assignmentchef.com/product/solved-ee328-operating-system-5
<br>



<h1>Simple GUI Programming</h1>

<h2>1 PROBLEM</h2>

<h3>1.1 DESCRIPTION</h3>

Write a program that displays the Olympic rings. Make the rings colored in the Olympic colors like below:

If you like to make it fancier, you can add “USA” on top the rings (not required), like following:

You are not required to draw exactly the same as in the pictures. Anything looks similar is fine.

And the color in the intersection part of the rings is not strictly required.

<h2>2 ALGORITHM</h2>

<h3>2.1 DRAW CIRCLES</h3>

By extending <em>JFrame </em>we are able to use varieties of methods to draw pictures. When <em>setVisible(true) </em>is executed, <em>paint(Graphics g </em>will be executed automatically. In this method we use <em>drawOval() </em>to draw circles with set locations. In the meantime <em>setColor() </em>is used to change color of different circles. <em>drawString() </em>is used to print strings as well.

1

Figure 3.1: Screenshot of GUI Programming

<h3>2.2 DETAILS IN IMPLEMENTATION</h3>

At first the stroke of the circle is too thin to be similar to Olympic Rings. After referring to some websites I convert the object <em>Graphics </em>to <em>Graphics2D </em>to use the method <em>setStroke()</em>. Then the thickness of the circle can be modified.

<h2>3 RESULTS</h2>

<h3>3.1 ENVIRONMENT</h3>

<ul>

 <li>Windows 10</li>

 <li>Java Development Kit 1.8.0_131</li>

 <li>Eclipse</li>

</ul>

3.2 SCREENSHOTS OF THE RESULT

We use command line to compile and execute the program. The result is shown in Fig. 3.1.

<h3>3.3 THOUGHTS</h3>

GUI programming is interesting. And with Java this process becomes much easier.

2