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
- I have always wondered at why math classes tend to focus so much on solving made up algebra problems. Finding equivalent functions through algebra or solving an equation for a specific variable is rewarding and intrinsically interesting in it of itself, but outside of class I couldn't think of many uses, execpt for mathmetical proofs. So far the most pertinent use of algebra I have found is in optimizing more general math functions for a very specific use. The act of using algebra to find an equivalent, simpler function than the generally defined one is very useful, especially in computer programming. Simplififying a function can often enourmously decrease the time it takes to execute on a machine, and can make your program easier to read in some cases. One example of this I have personally worked on was a function for finding how far and to which direction a robot needed to turn to face a point.

We can use the geometric definition of the dot product, ${\displaystyle \mathbf {a} \cdot \mathbf {b} =\|\mathbf {a} \|\ \|\mathbf {b} \|\cos \theta}$, to find the angle between the vector of the absolute angle $v$ the robot was facing, $\mathbf {a} = (\cos v, \sin v)$ and the vector of the point we want the robot to turn and drive towards, $\mathbf {b} = (x, y)$

This was all fine and well, but this general definition of the dot product is not in a format condusive to solving for $\theta$, so before typing it in to our program for the robot, we must first use algebra to find an equivalent function for our use case of finding $\theta$, the angle between the two vectors.

${\displaystyle \mathbf {a} \cdot \mathbf {b} =\|\mathbf {a} \|\ \|\mathbf {b} \|\cos \theta}$

${\displaystyle \frac{\mathbf {a} \cdot \mathbf {b}}{\|\mathbf {a} \|\ \|\mathbf {b}\|} = \cos \theta}$

${\displaystyle \arccos{ \frac{\mathbf {a} \cdot \mathbf {b}}{\|\mathbf {a} \|\ \|\mathbf {b}\|} } = \theta}$

Oh, also physics. I didn't really have physics class in high school, so it was a little bit of a shock to me in college. You use a lot of algebra in physics. It is really cool solving physics problems and it is very helpful to have a strong algebra background. And algebra, or figuring, really shows up everywhere, though I often didn't notice because many problems that show up in computer science or otherwise feel different or are easier to solve than textbook math problems. So getting good at textbook problems is helpful for solving many simpler problems that show up in physics or coding with great confidence. 

# Courses
All of calculus is very good algebra practice. This means through these courses you get very good at manipulating equations to solve for certain variables, transforming complex equations into a simpler equivalent form, and noticing patterns to quickly solve equations e.g. factoring, completing the square.

Calculus is also very good at teaching you how to think about and visualize curves. Calculus is a drawing class. You can draw defined curves or solve an unknown variable to draw curves such as in calculating the derivative to splice curves together smoothly.

I always felt frustrated in math classes when I couldn't understand, or at least see a line of reasoning or connection between two concepts, tricks, or formulas being taught. This often irked me, but remembering that it is ok to just learn some formulas was very helpful for me. Realizing that often specific formulas aren't extremely important and being able to gleam insight into what we are trying to calculate or express with the math is more useful outside of class helped me feel ok about not conducting an impractical deep dive on each and every formula taught in class. 

- **Calculus I:** Thinking about continuous numbers (limits) and demonstrating how to solve limits. Properties of curves like slope and area (derivatives and integrals) and tricks to solve for these properties: power rule, chain rule, u substitution. Algebra and trigonometry practice. 

- **Calculus II:** More solving derivatives and integrals. Integral puzzle solving: partial fractions, trig sub, integration by parts. Applications of integrals: arc length, volume and surface area of rotation. Thinking about infinite series (addition of terms), how to solve for convergence or divergence. Approximating other functions by addition of polynomials: taylor series. Parametric curves with calculus concepts (derivative, integrals).

- **Calculus III:** An introduction to a whole new set of problems in the calculus realm. The hint at to what these problems are is in the name; Calc III is an introduction to 3 dimensional problems. 3D neccessarily requires multiplevariables (x, y, z) and so along with vector math and 3D geometry/ functions, multivariable integration and differentiation were introduced. One of the topics that stood out the most to me was gradients, the idea of the direction and magnitude of steepest ascent (I like topographical maps). 3D extrema (optimization), contrstrained extrema (Langrange multipliers); coordinate systems (polar, cylindrical, sphereical); line, surface, and volume integration; flux and curl were covered. I thoroughly enjoyed this class. I took it over the summer of 2023 in an online asynchronous format. This is not everyone's cup of tea, but I found that focusing on one class at a time was a great experience and I was able to gain a deeper understanding through watching lectures, reading Stewart's book, and practising problems.  
  
- **Discrete:** This course is taught differently by each teacher. My teacher mainly focused on rigourous proof writing. We learned proofs using the properties of integers, the definitions of even, odd, prime, quotient + remainder, divides by (is a factor of). Definitions of sets, boolean logic, and touched on number representations. We also learned "Boolean Algebra" aka finding equivalent boolean expressions using simple and derived rules such as Demorgan's laws. Boolean logic rules are easily proved and demonstrated using truth tables to show for every possiblity of input, the expressions are equivalent. 

![image](https://user-images.githubusercontent.com/67801725/197430475-ef14f23a-1e00-4537-84d4-b9e152f8d47f.png)


