Let's review some basic concepts. The algebraic statement in question is a quadratic inequality in non-standard form. So, the first action we might take would be to rewrite it in standard form like $y \geq ax^2 + bx + c$, where $a, b,$ and $c$ are real numbers and $a \neq 0$. So, let's do that using the variables you've chosen:
$$b \geq \frac{a^2 + a -1}{2} \ \Longleftrightarrow \ y \geq \frac{x^2 + x -1}{2} = \left(\frac{1}{2}\right)x^2 + \left(\frac{1}{2}\right)x + \left(\frac{1}{2}\right)1$$
I also went ahead and exchanged your variable assignments for the more standard form, as it will make it easier to think about graphing the inequality in an $(x,y)$ coordinate system so as to analyze its critical features visually, after parsing them algebraically. Recall that every quadratic inequality takes the shape of a parabola when graphed. The sign of the numerical coefficient of the squared term $a$ will determine the projection-orientation of the parabola.

![[plot.png]]


We can determine the <span style='font-family:latin modern roman; font-style:italic; font-weight:bold'>axis of symmetry</span>  $x = \Large\frac{-b}{2a}$ of a parabola at its <span style='font-family:latin modern roman; font-style:italic; font-weight:bold'>vertex</span> $= \left(\Large\frac{-b}{2a},\frac{4ac-b^2}{4a}\right)$. If you haven't before, you should attempt deriving the <span style='font-family:latin modern roman; font-style:italic; font-weight:bold'>quadratic formula</span> for yourself, as it will help you build strong intuition for polynomials, and it reveals many insights into the behaviors of quadratics.
$$x = \frac{-b \pm \sqrt{b^2-4ac}}{2a}$$
Notice that the $discriminant = b^2 - 4ac$ gives the number and type of solutions to a quadratic equation.
	If $b^2 - 4ac > 0$, then the quadratic equation has two distinct real solutions.
	If $b^2 - 4ac = 0$, then the quadratic equation has a single real solution ($double \ root$).
	If $b^2 - 4ac < 0$, then the quadratic equation has no real solutions.

Next, we might inspect the boundary conditions — meaning what is the value of $y$ when $x = 0$ (this is equivalent to evaluating the <span style='font-family:latin modern roman;font-style:italic; font-weight:bold'>y</span>**-intercept**), and what is the value of $x$ when $y = 0$ (which is equivalent to finding its **roots/real solutions** or we might discover that the function has **complex** solutions).

Equations and inequalities of this form may be solved by (1) factoring, if the trinomial is factorable, (2) by completing the square, or (3) by the quadratic formula. The roots may also be found by graphing the function and finding the points of intersection, however this method has inadequacies of precision. Below is the graph of your inequality.

![[inequality.png]]

The basic properties and concepts for quadratic equations also hold for quadratic inequalities. To graph a quadratic inequality
	1. Replace the inequality with an equal sign;
	2. Draw the graph of the equation derived in step 1. If the original inequality contains a ≥ or ≤ symbol, then draw the graph using a solid line, if it contains a > or < symbol, draw the graph using a dashed line.
	3. Select any point not on the line and determine if this point is a solution to the inequality. If the point selected is a valid solution, shade the region on that side of the line. If the selected point does not satisfy the inequality, shade the region on the side of the line opposite that containing this point.

Much more could be said here, and there is no definite protocol for what to include and what to leave out, but hopefully this helps you navigate the wonderful space of quadratic functions.