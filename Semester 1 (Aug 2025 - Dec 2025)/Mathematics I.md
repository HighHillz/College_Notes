# **Mathematics I**

## 19 Aug 2025

# Introduction to the Course

The units covered in this course are:

1. Calculus  
2. Vector Calculus  
3. Sequence & Series  
4. Differential Equations  
5. Functions of Several Variables

## 21 Aug 2025

# Calculus

## Limits

Let f(x) be a function defined on (a, b) except at c. Then, as x approaches c, if f(x) approaches L, then we say  
xcf(x) \= L

A limit exists at x \= c if:  
	LHL \= xc\-f(x) \= L=RHL=xc\+f(x) \= L

## Continuity

A function f(x) is said to be continuous in (a, b) if:  
xc-f(x)=xc+f(x)=f(c)  c (a,b)   
Otherwise, it is said to be discontinuous. Continuity of a function can be found at a point in the function as well.  
Graphically, a function is continuous if its graph is smooth. i.e. There are no breaks throughout its domain.

## 22 Aug 2025

## Differentiation

The rate of change of a function is said to be the derivative of a function.  
f'(x)=dydx=h0f(x+h)-f(x)h, where h=x  
Here are different ways to write a derivative, considering y=f(x):  
dydx=f'(x)=y'  
For differentiating it n times:  
dny(dx)n=f''''...n times(x)=y''''... n times

### Chain rule

If y=f(u), u=g(x) or y=f(g(x)),   
dydx=dydududx

## Differentiability

A function f(x) is differentiable at a point if RHD=LHD  where  
RHD=h0f(x+h)-f(x)h  and  
LHD=h0f(x-h)-f(x)-h  
Graphically, A function which is continuous and has no sharp points throughout its domain is said to be differentiable.  
Here is a list of some functions and their continuity and differentiability throughout its domain:

| Function | Continuous? | Differentiable? |
| ----- | ----- | ----- |
| Polynomial (i=0naixn-i, nN) | Yes | Yes |
| Modulus (|x|) | Yes | No (at 0\) |
| Constant (a) | Yes | Yes |
| Signum (|x|x, x0; 0, x=0) | No (at 0\) | No (at 0\) |
| Greatest Integer / Floor (⌊x⌋) | No (at integers) | No (at integers) |
| Smallest Integer / Ceil (⌈x⌉) | No (at integers) | No (at integers) |
| Fractional ({x}=x-⌊x⌋) | No (at integers) | No (at integers) |
| Reciprocal (1f(x), f(x)0) | No (depends on f(x)) | No (depends on f(x)) |

## Increasing and Decreasing Functions

A function f(x) is said to to be increasing throughout (a, b) if f'(x)0, x(a,b)  
A function f(x) is said to to be decreasing throughout (a, b) if f'(x)0, x(a,b)

A function f(x) is said to to be strictly increasing throughout (a, b) if f'(x)\>0, x(a,b)  
A function f(x) is said to to be strictly decreasing throughout (a, b) if f'(x)\<0, x(a,b)

A function f(x) is said to to be constant throughout (a, b) if f'(x)=0, x(a,b)

## Increment Theorem

If a function f(x) is differentiable at a point x, then for a small increment x, the corresponding increment in the function, y=f(x+x)-f(x), can be expressed as:

y=f'(x)x+x  
where 0 as x0.  
Here,  is a small number that cancels out the error achieved by approximating the change in the function. It becomes negligible as the change in x is reduced, because the value of y gets more accurate.

## 

## 26  Aug 2025

# Minima and Maxima

## Local Minima and Maxima

For a function f(x), all the points where the function forms a peak is a local maxima, and all the deepest points of a dip is a local minima.

Mathematically, if the derivative of the function at a point is 0, and it has a *positive* slope before the point and a *negative* slope after the point, it is a **local maxima**.  
Similarly, if the derivative of the function at a point is 0, and it has a *negative* slope before the point and a *positive* slope after the point, it is a **local minima**. 

## Absolute Minima and Maxima

The maximum value of all the local maxima of a function is called the **absolute maxima** of the function.  
The minimum value of all the local minima of a function is called the **local minima** of the function.

## First & Second Derivative Tests

These tests are used to check minima and maxima for a given function. For the **first derivative test**:

1. Find the derivative of f(x) .i.e. f’(x)  
2. Find critical points (points where f’(x) \= 0\)  
3. For each critical point, use the mathematical way to find minima and maxima.

For the **second derivative test**:

1. Find the derivative of f(x) .i.e. f’(x)  
2. Find critical points  
3. Find second derivative .i.e. f’’(x)  
4. If f’’(k) \> 0 where k is a critical point, then k is a local maxima. If f’’(k) \< 0, then k is a local minima. Use the first derivative test in case of 0\.

## 28 Aug 2025

# Antiderivative

Let f(x) be the derivative of a function F(x). Then F(x)+c is said to be the antiderivative of f(x). The constant term c represents the family of the function as differentiating it would result in the same derivative.  
Mathematically, f(x) dx=F(x)+c  
**Definite Integral**: Let f(x) be a function on     \[a, b\]. Split this range into n parts so that each small range R=b-an  
Let xi\* be a sample space on the ith interval.  
Then the area of the curve can be obtained by adding the area of rectangles in each of the n regions. The larger the value of n, the more approximate the area of the curve becomes. Thus,  
abf(x) dx=ni=1nf(xi\*)x

## Fundamental Theorem of Calculus

1. Let f(x) be a continuous function on \[a, b\]. If F(x)=axf(t) dt, then F'(x)=f(x)  
2. Let f(x) be a continuous function on \[a, b\]. If F(x) is the antiderivative of f(x), then abf(x) dx=F(b)-F(a)

## 29 Aug 2025

## Properties of Definite Integrals

1. f(x) dx=f(u) du  
2. abf(x) dx \= \-baf(x) dx  
3. abf(x) g(x) dx=abf(x) dxabg(x) dx  
4. abf(x) dx=abf(a+b-x) dx  
5. aaf(x) dx=0  
6. abf(x) dx=acf(x) dx+cbf(x) dx, if a\<c\<b

## Integration by Partial Fractions

| Integrand | Partial Fractions |
| ----- | ----- |
| px \+ q(x \- a)(x \- b) | A(x \- a)+B(x \- b) |
| px \+ q(x \- a)2 | A(x \- a)+B(x \- a)2 |
| px2 \+ qx \+ r(x \- a)(x \- b)(x \- c) | A(x \- a)+B(x \- b)+C(x \- c) |
| px2 \+ qx \+ r(x \- a)2(x \- b) | A(x \- a)+B(x \- a)2+C(x \- b) |
| px2 \+ qx \+ r(x \- a)(x2 \+ bx \+ c) | A(x \- a)+Bx \+ C(x2 \+ bx \+ c) |

It is important to note that if we have an integrand in the form f(x)g(x), then the degree (highest power the variable is raised to) of f(x)g(x) so that partial fractions can be taken. In any other case, the integrand cannot be split by using partial fractions.

## 3 Sep 2025

## Integration by Parts

Consider two functions f(x) and g(x), where f(x) is the first function and g(x) is the second function. Then:  
f(x)g(x) dx=f(x)g(x) dx-(f'(x)g(x) dx) dx  
Or, if f(x)=u and g(x) dx=dv, then:  
u dv=uv-v du  
**Finding first and second function**: To find the first and second function, we use ILATE, which stands for:

- **I**nverse trigonometric functions  
- **L**ogarithmic  
- **A**rithmetic  
- **T**rigonometric  
- **E**xponential

The topmost ones get the most priority and it goes down. So in the case of a combination of inverse trigonometric function and an arithmetic expression, we take inverse to be first and arithmetic to be second.

**Bernoulli’s Formula**: This formula does the same as expanding the integral, but it saves a lot of effort when using this technique multiple times in a question.  
u dv=uv-u'v1+u''v2- ...u''' (n times) vn=uv+i \= 1n(-1)iu''' (i times)vi  
Where, u''' (n times) means to differentiate n times, and vn means to integrate n times.

This shows an easier way to write it on paper. The arrows denote what terms are to be multiplied, and the sign in between the arrows show whether the terms are to be added or subtracted.