# Problem 10 – Analysis of motion from numerical data

Given:

$$
x(t)=t+\frac{1}{20}t^2,\qquad t\in[0,10]
$$

with time step

$$
\Delta t=0.1
$$

---

## 1. Approximate velocity using finite differences

The forward finite difference approximation is:

$$
v(t_i)\approx \frac{x(t_{i+1})-x(t_i)}{\Delta t}
$$

where

$$
t_i=i\Delta t
$$

---

## 2. Approximate acceleration using finite differences

Acceleration is approximated from velocity:

$$
a(t_i)\approx \frac{v(t_{i+1})-v(t_i)}{\Delta t}
$$

Alternatively, directly from position:

$$
a(t_i)\approx \frac{x(t_{i+1})-2x(t_i)+x(t_{i-1})}{(\Delta t)^2}
$$

---

## 3. Analytical solution

Differentiate the given function:

$$
x(t)=t+\frac{1}{20}t^2
$$

Velocity:

$$
v(t)=\frac{dx}{dt}=1+\frac{1}{10}t
$$

Acceleration:

$$
a(t)=\frac{dv}{dt}=\frac{1}{10}
$$

So the exact results are:

$$
v(t)=1+0.1t
$$

$$
a(t)=0.1
$$

---

## 4. Effect of the time step on accuracy

If \(\Delta t\) is smaller, the numerical approximations are more accurate.

If \(\Delta t\) is larger, the approximation error increases.

Thus:

- smaller step → better accuracy,
- larger step → worse accuracy.

---

## Final results

Exact position:

$$
x(t)=t+\frac{1}{20}t^2
$$

Exact velocity:

$$
v(t)=1+0.1t
$$

Exact acceleration:

$$
a(t)=0.1
$$

Finite-difference velocity:

$$
v(t_i)\approx \frac{x(t_{i+1})-x(t_i)}{\Delta t}
$$

Finite-difference acceleration:

$$
a(t_i)\approx \frac{v(t_{i+1})-v(t_i)}{\Delta t}
$$

or

$$
a(t_i)\approx \frac{x(t_{i+1})-2x(t_i)+x(t_{i-1})}{(\Delta t)^2}
$$
