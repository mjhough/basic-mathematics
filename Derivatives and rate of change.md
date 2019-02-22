# Derivatives and rate of change

- rate of change = slope
- But how do we find the slope of a line that isn't straight?

####

## Derivatives
- The derivative of a function gives the slope of that function at any point.
- The process of finding the derivative is called differentiation.


- The derivative of $f(x)$ can be written in 2 ways:
  - $f'(x)$, pronounced "$f$ prime $x$" or "$f$ dashed $x$"
  - $\frac{df}{dx}$, pronounced "df dx". **NOTE: This is not a fraction!** It is just notation.

- Sometimes derivatives do not exist at certain points.
  - Eg, the graph of $y=1/x$ does not exist at $x=0$.


###
- #### Interpreting derivatives
  - The derivative of a function is itself a function, whose value at any point $x$ gives the slope of the original function at that point $x$.
  - Both the original function and the derivative function can be plotted on a set of axes. Their should be a relationship between the function and its derivative. For example, we can see that the function and its derivative are related in the graph below:
![](http://www.teacherschoice.com.au/maths_library/calculus/plot_d1.gif)


###

- #### Calculating derivatives
  - Simple differentiation rules
    - If $n$ is any non-zero number and $f(x)=x^n$ then:
      - $f'(x)=nx^{n-1}$. In other words, bring the power to the front, and minus 1 from the power.
    - If $c$ is any constant and $f(x)=c$ then:
      - $f'(x)=0$, because the slope of $y=c$ is 0.
    - If $c$ is any constant then $(cf)'=cf'$, or $f(x)=cx^n$ becomes $f'(x)=cnx^{n-1}$. We don't touch the constant out the front.
    - $(f+g)'=f'+g'$
    - $(f-g)'=f'-g'$