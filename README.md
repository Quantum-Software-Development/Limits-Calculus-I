

 <p align="center">
<img src="https://github.com/Quantum-Software-Development/Math/assets/113218619/58c8c407-2971-4a65-9030-e25d76617687"/>

<br><br>

## <p align="center"> ✍️  *Resolution* of Mathematics Exercises - Calculus I - Limits and Derivatives

#### <p align="center"> AI Data Science - PUCSP University Math Repository - [Professor Eric Bacconi Gonçalves](https://www.linkedin.com/in/eric-bacconi-423137/)

<br><br>

## 1. Find the limits:

 a)  **Limit Expression:**
 <!-- $$ \Large x^2 - 9$$ -->

$$\\begin{align*}
\Large \lim_{{x \to 3}} \frac{{x^2 - 9}}{{x - 3}}
\end{align*}
\$$

<br>

*  **Simplified Form:** The numerator  $\Large x^2 - 9$, can be factored as ( (x + 3)(x - 3) ), which simplifies the expression to:

$$\\begin{align*}
\Large \lim_{{x \to 3}} (x + 3) 
\end{align*}
\$$







<!-- 
 To solve this limit, we can use factorization:
 
$$\\begin{align*}
\lim_{x \to 3}\frac{x^{2}-9}{x-3} &= \lim_{x \to 3}\frac{(x+3)(x-3)}{x-3} \\
&= \lim_{x \to 3}(x+3) \\
&= 3+3 \\
&= 6
\end{align*}
\$$

Result: The limit of the expression is 6.

-->

#

### 1b) $$\(\lim_{x \to -7}\frac{49-x^{2}}{7+x}\)$$

Again, we can use factorization:

$$\\begin{align*}
\lim_{{x \to -7}} \frac{{49 - x^2}}{{7 + x}} &= \lim_{{x \to -7}} \frac{{(7 + x)(7 - x)}}{{7 + x}} \\
&= \lim_{{x \to -7}} (7 - x) \\
&= -7 - 7 \\
&= -14
\end{align*}
\$$

Result: The limit of the expression is -14.

#

### 1c) $$\lim_{{x \to 0}} \frac{x^3}{2x^2 - x}$$

We factor out ( x ) from the denominator:

$$= \lim_{{x \to 0}} \frac{x^3}{x(2x - 1)}$$

We cancel out an ( x^2 ) term from the numerator and denominator:

$$= \lim_{{x \to 0}} \frac{x}{(2x - 1)} =\frac{0}{-1} = 0$$

Result: The limit of the expression is 0.

#

### 1d) $$f(x) = \lim_{x \to 1} \frac{x^2 - 4x + 3}{x - 1}$$

To calculate the limit, we can simplify the expression by factoring the numerator, which results in:

$$(x-1)(x-3)$$

By canceling out the ( x-1 ) term with the denominator, we get:

$$f(x) = \lim_{x \to 1} (x-3)$$

Therefore, the limit of the function as ( x ) approaches 1 is -2.

$$f(1) = -2$$

<br>

Result: The limit of the expression is -2.

#

### 1e)  $$\lim_{{x \to 1}} \frac{{x^2 - 2x + 1}}{{x - 1}}$$


To calculate the limit, we can simplify the expression by factoring the numerator, which is a perfect square trinomial. Factoring (x^2 - 2x + 1), we get ((x - 1)(x - 1)). The denominator is already in factored form as (x - 1). Thus, the function simplifies to:

$$\frac{(x - 1)(x - 1)}{x - 1}$$

After canceling out the common term ( x - 1 ), we are left with:

$$\lim_{{x \to 1}} (x - 1)$$

Since there are no more terms that depend on ( x ), this simplifies to:

$$\lim_{{x \to 1}} = x - 1 = 0$$

Result: The limit of the function as ( x ) approaches 1 is simply 0.

#

### 1f)  $$\lim_{{x \to 2}} \frac{{x - 2}}{{x^2 - 4}}$$

To solve this limit, we need to factor the denominator and simplify the expression. The denominator ( x^2 - 4 ) can be factored into ( (x + 2)(x - 2) ), which allows us to cancel out the ( x - 2 ) term in the numerator:

$$\lim_{{x \to 2}} \frac{1}{{x + 2}}$$

Substituting ( x = 2 ) into the simplified expression, the final value:

$$\frac{1}{4}$$

<br>

Result: The limit of the function as ( x ) approaches 1 is simply $$\frac{1}{4}$$


#


### 1g)   $$\(\lim_{{x \to 3}} \frac{{x^3 - 27}}{{x^2 - 5x + 6}}\)$$

<br>

This limit can be solved using factorization and polynomial division: <br><br>

$$\
\begin{align*}
\lim_{{x \to 3}} \frac{{x^3 - 27}}{{x^2 - 5x + 6}} 
&= \lim_{{x \to 3}} \frac{{(x - 3)(x^2 + 3x + 9)}}{{(x - 2)(x - 3)}} \\
&= \lim_{{x \to 3}} \frac{{x - 3}}{{x - 2}} \\
&= \frac{{3 - 3}}{{3 - 2}} \\
&= 1
\end{align*}
\$$

<br>

Result: The limit of the function as ( x ) approaches 1 is simply $$\frac{1}{4}$$


#

### 1h: $$\(\lim_{{x \to \infty}} \frac{{x^2}}{{2x^2 - x}}\)$$

In this case, we can use L'Hôpital's rule, as the limit is of the form \(\frac{0}{0}\) or \(\frac{\infty}{\infty}\) when \(x\) tends to infinity.

$$\
\begin{align*}
\lim_{{x \to \infty}} \frac{{x^2}}{{2x^2 - x}} &= \lim_{{x \to \infty}} \frac{{\frac{d}{dx}[x^2]}}{{\frac{d}{dx}[2x^2 - x]}} \\
&= \lim_{{x \to \infty}} \frac{{2x}}{{4x - 1}} \\
&= \lim_{{x \to \infty}} \frac{{2}}{{4 - \frac{1}{x}}} \\
&= \frac{2}{4} \\
&= \frac{1}{2}
\end{align*}
\$$

<br>

 Result: The limit of the expression is $$\frac{1}{2}$$

<br><br>

## 2. Solve the Limits:


### 2a): ( $\lim_{x \to \infty} \frac{1}{x^2}$ )

The limit as ( x ) approaches infinity for ( $\frac{1}{{x^2}}$ ):

is: $\lim_{{x \to \infty}} \frac{1}{{x^2}} = 0$ 

As ( x ) increases without bound, the value of ( \frac{1}{{x^2}} ) approaches 0 because the denominator grows much faster than the numerator.

#


### 2b): ( $\lim_{x \to -\infty} \frac{1}{x^2}$ )

The limit as ( x ) approaches negative infinity for ( $\frac{1}{{x^2}}$ ) is: 

$\lim_{{x \to -\infty}} \frac{1}{{x^2}} = 0$

As ( x ) decreases without bound, the value of ( $\frac{1}{{x^2}}$ ) approaches 0, similar to part a), because squaring a negative number results in a positive number, which grows larger.

#

### 2c): (  $\lim_{x \to \infty} x^4$ )

The limit as ( x ) approaches infinity for ( x^4 ) is: grows at an increasing rate and approaches infinity for ( x^4 ) is:

$\lim_{{x \to \infty}} x^4 = \infty$


If you have more expressions or need further assistance, feel free to ask!

Similar to the previous expressions, the term ( 2x^5 ) grows at a faster rate than the others, causing the expression to approach infinity.

#

### 2d): ( $\lim_{{x \to \infty}} (2x^4 - 3x^3 + x + 6)$ )

The limit as ( x ) approaches infinity for ( $2x^4 - 3x^3 + x + 6$ ) is:

$\lim_{x \to \infty} (2x^4 - 3x^3 + x + 6) = \infty$ 

As ( x ) grows larger, the term ( 2x^4 ) dominates, leading the expression to increase without bound.

#

### 2e):

The limit as ( x ) approaches negative infinity for ( 2x^4 - 3x^3 + x + 6 ) is:

$\lim_{x \to -\infty} (2x^4 - 3x^3 + x + 6) = \infty$ 

Even though ( x ) is negative, the highest power term ( x^4 )  will still lead the expression to increase without bound because the even power makes it positive.


#

### 2f) : The limit as ( x ) approaches infinity for ( 2x^5 - 3x^2 + 6 ) is: 

The limit as ( x ) approaches negative infinity for ( 2x^4 - 3x^3 + x + 6 ) is: 

$\lim_{x \to -\infty} (2x^4 - 3x^3 + x + 6) = \infty  Even though ( x ) is negative, y.



  






 






























<!--
 <br><br>

 ## 3.Calculate the Following Limits

### 3a: Finding the limit of a polynomial function as x approaches infinity

The given function is a polynomial function of the form: 

<br>

$$f(x)=axn+bxn−1+cxn−2+...+dx+e$$

As x approaches infinity, the highest power of x in the function dominates the value of the function. This means that we can ignore all the lower-order terms, and simply consider the behavior of the highest-order term.
In this case, the highest-order term is 2x4. As x approaches infinity, x4 also approaches infinity, and so the function f(x) also approaches infinity.

Therefore, the limit of the function as x approaches infinity is infinity. We can write this mathematically as:

<br>

$$x→∞lim x32x4−3x3+x+6 =0$$

#

### 3b:Finding the limit of a rational function as x approaches infinity

<br>

The given function is a rational function of the form 

<br>

$$f(x)=cxm+fxm−1+...+gx+haxn+bxn−1+...+dx+e$$

<br>

, where n > m. As x approaches infinity, the highest power of x in the numerator dominates the value of the numerator, and the highest power of x in the denominator dominates the value of the denominator.  This means that we can ignore all the lower-order terms, and simply consider the behavior of the highest-order terms.

In this case, the highest-order term in the numerator is 2x4, and the highest-order term in the denominator is x3. 

As x approaches infinity, 2x4 grows much faster than x3, and so the function f(x) approaches zero.









#

######  <p align="center"> [Copyright 2024 Quantum-Software-Development. Code released under the MIT license.](https://github.com/Quantum-Software-Development/Q-Star/blob/f5115a1a073bdb3fa68c51bb3b3414c8e0b0270e/LICENSE)










