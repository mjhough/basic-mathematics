# Logarithms and exponentials
### Exponentials
- Involve the variable in the power. For example: $3^x$. $x$ is the variable here.
- Look like below on the graph. A smaller base to the varying exponent will mean a flatter, steadier growth:
![Exponentials](http://bhs-methods34.wikispaces.com/file/view/04Aexp1.gif/191265098/327x299/04Aexp1.gif)
#####
- Exponential growth:
  - Take the form $y=Ca^x$ where $a>1$ and $C>0$.
  - $C$ is a constant representing some initial conditions, such as the population at time 0 etc.
  - The base $a$ is a constant that depends on the problem. It determines how quickly the quantity grows.
  - The above graph shows only exponential growth equations

  - Example Q: There are four cockroaches in a student's house at time $x=0$. The population size $P$ triples every week. Write an expression for the population size $P(x)$ after $x$ weeks:
    - Use the standard form: $y=Ca^x$
    - 4 is the initial value, $C$
    - 3 is the base because it triples every $x$ weeks.
    - Therefore the expression looks like this: $P(x) = 4\times3^x$
#####
- Compound interest:
  - Is an exponential growth exponential
  - Growth depends on 2 things: the initial amount invested and the interest rate.
  - If $P$ dollars are invested at an interest rate of $r$ per time period (where r is the decimal representation of a percentage) for a total of $x$ time periods, then the final value $F(x)$ of the investment is given by $F(x) = P(1+r)^x$. This is the compound interest formula.
  - **NOTE: The time period represents the number of times it compounds. For example, if compounding monthly for 2 years that means the time period is 24 months, or 24. Also, note that if asked to calculate the final amount if an amount is invested at 9% per annum compounding monthly. In this case, we need to divide the per annum interest rate by the number of times it compounds in that time period. So 0.09/12 = 0.0075.**
#####
- Exponential decay
  - Exponential functions with negative powers.
  - $y$ gets smaller as $x$ gets bigger
  - Goes from high on the negative (left) side to low on the positive (right) side
  - All graphs pass through the point (0, 1) and y will never be 0 as long as $a > 1$
#####
- The exponential function $e^x$
  - Any exponential growth function can be written as $y=Ca^x$, where $a > 1$, and any exponential decay function can be written as $y=Ca^{-x}$, again where $a > 1$.
#####
- The mathematical constant $e$
  - The mathematical constant, $e$, is an irrational number that arises ina alrge number of places. Because $e$ is irrational, like $\pi$, it's value cannot be written exactly as a fraction or decimal. Its approximate value is $e \approx 2.71828$.
  - $e$ is the most frequently used base for exponential equations.
  - $e^x$ is called the exponential function.
#####
- General form of exponential functions
  - $y=Ce^{kx}$, where $C$ and $k$ are constants, $k\neq0$ (and usually $C>0$).
  - If $k$ is positive, the function gives exponential growth.
  - If $k$ is negative the function gives exponential decay.

### Logarithms
- Logarithms help us find the variable in the exponent. Eg. If, $81=3^x$, how can we find $x$?
- The inverse of an exponential function is called a **logarithm**.
- Let $a > 0$, $a\neq1$, and $y=a^x$. We can then say that $x=\log_a{y}$, where $a$ is the base. When we see this, we can ask the question, to what power should $a$ be raised to get the answer $y$. For example, $100=10^2$, therefore $2=\log_{10}{100}$.
- Logarithms can be taken to any base greather than 0 and not equal to 1.
- The most common bases are 10 and e. You will often see $\log_{10}{x}$ written as just $\log{x}$, and $\log_e{x}$ written as just $\ln{x}$.
- Logarithms with a base of $e$ are called natural logarithms.
#####
- Strange things happen if you try to evaluate a log of a negative number. So for the purpose of this, we will only use positive values for $a$ and $b$ in the case of $\log_{a}{b}$
#####
### Important logarithm rules!
- If $a > 0$, $a\neq1$, $x,y>0$, and $r$ is any real number, then:
- $\log_a{(x^r)}=r\log_a{x}$
- $\log_a{(xy)} = \log_a{x}+\log_a{y}$
- $\log_a{(\frac{x}{y})}=\log_a{x}-\log_a{y}$
######
- Change of base rule:
  - We can convert the base of a logarithm to something else we can convert it to a fraction like so:
    1. $a^x=b$
    2. $\log(a^x)=\log b$
    3. $x\log a = \log b$
    4. $x=\frac{\log b}{\log a}$
    5. $x=\frac{\ln a}{\ln b}$
  - This can be simplified to: $\log_a{b}=\frac{\log b}{\log a}=\frac{\ln b}{\ln a}$