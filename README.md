# MathMusings
Fun Math Related Quotes, Equations, And Thoughts

# Resources
- https://calculusmadeeasy.org/
- https://www.wolframalpha.com/
- https://www.desmos.com/calculator
- https://www.overleaf.com/learn/latex/Mathematical_expressions

# Quotes
- "All of these different applications of the derivative illustrate the fact that part of the power of mathematics lies in its abstractness. A single abstract mathematical concept (such as the derivative) can have different interpretations in each of the sciences. When we develop the properties of the mathematical concept once and for all, we can then turn around and apply these results to all of the sciences. This is much more efficient than developing properties of special concepts in each separate science. The French mathematician Joseph Fourier (1768–1830) put it succinctly: “Mathematics compares the most diverse phenomena and discovers the secret analogies that unite them.”"
-James Stewart, Calculus 9E

- "Some calculus-tricks are quite easy. Some are enormously difficult. The fools who write the textbooks of advanced mathematics ... seem to desire to impress you with their tremendous cleverness by going about it in the most difficult way. Being myself a remarkably stupid fellow, I have had to unteach myself the difficulties, and now beg to present to my fellow fools the parts that are not hard. Master these thoroughly, and the rest will follow. What one fool can do, another can."
-Silvanus P. Thompson, Calculus Made Easy

# Applications
- I have always wondered at why math classes tend to focus so much on solving made up algebra problems. Even into calculus the actual theory you learn such as derivatives and integrals are not inherently difficult to grasp. Derivative = slope, integral = sum of all the y values. Of course this is an oversimplification, but the real difficulties textbooks and tests like to stress are in difficult algebraic solving. Finding equivalent functions through algebra or solving an equation for a specific variable is reqarding and intrinsically interesting in it of itself, but outside of class I couldn't think of many uses, execpt for mathmetical proofs. So far the most pertinent use of algebra I have found is in optimizing more general math functions for a very specific use. The act of using algebra to find an equivalent, simpler function than the generally defined one is very useful, especially in computer programming. Simplififying a function can often enourmously decrease the time it takes to execute on a machine, and can make your program easier to read in some cases. The most relevant example of this I have personally worked on was a function for finding how far and to which direction a robot needed to turn to face a point.

We can use the geometric definition of the dot product, ${\displaystyle \mathbf {a} \cdot \mathbf {b} =\|\mathbf {a} \|\ \|\mathbf {b} \|\cos \theta}$, to find the angle between the vector of the absolute angle $v$ the robot was facing, $\mathbf {a} = (\cos v, \sin v)$ and the vector of the point we want the robot to turn and drive towards, $\mathbf {b} = (x, y)$

This was all fine and well, but this general definition of the dot product is not in a format condusive to solving for $\theta$, so before typing it in to our program for the robot, we must first use algebra to find an equivalent function for our use case of finding $\theta$, the angle between the two vectors.

${\displaystyle \mathbf {a} \cdot \mathbf {b} =\|\mathbf {a} \|\ \|\mathbf {b} \|\cos \theta}$

${\displaystyle \frac{\mathbf {a} \cdot \mathbf {b}}{\|\mathbf {a} \|\ \|\mathbf {b}\|} = \cos \theta}$

${\displaystyle \arccos{ \frac{\mathbf {a} \cdot \mathbf {b}}{\|\mathbf {a} \|\ \|\mathbf {b}\|} } = \theta}$

# Courses
- Calculus I: Continuous numbers (limits). Thinking about properties of curves like slope and tricks to solve for these properties (derivatives, integrals). Algebra practice.

![image](https://user-images.githubusercontent.com/67801725/197430475-ef14f23a-1e00-4537-84d4-b9e152f8d47f.png)


