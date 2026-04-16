# Problem 6 – Damped oscillator

Equation:

$$
m\frac{d^2x}{dt^2}+b\frac{dx}{dt}+kx=0
$$

---

## 1. Characteristic equation

Assume a solution of the form:

$$
x(t)=e^{rt}
$$

Substitute into the equation:

$$
mr^2e^{rt}+bre^{rt}+ke^{rt}=0
$$

Since \(e^{rt}\neq 0\):

$$
mr^2+br+k=0
$$

This is the characteristic equation.

Its discriminant is:

$$
\Delta=b^2-4mk
$$

---

## 2. Classification of cases

### (a) Underdamped case

If

$$
b^2<4mk
$$

then the roots are complex:

$$
r=-\frac{b}{2m}\pm i\omega_d
$$

where

$$
\omega_d=\sqrt{\frac{k}{m}-\frac{b^2}{4m^2}}
$$

The solution is:

$$
x(t)=e^{-\frac{b}{2m}t}\big(C_1\cos(\omega_d t)+C_2\sin(\omega_d t)\big)
$$

---

### (b) Critically damped case

If

$$
b^2=4mk
$$

then the repeated root is:

$$
r=-\frac{b}{2m}
$$

The solution is:

$$
x(t)=(C_1+C_2 t)e^{-\frac{b}{2m}t}
$$

---

### (c) Overdamped case

If

$$
b^2>4mk
$$

then the roots are real:

$$
r_{1,2}=\frac{-b\pm\sqrt{b^2-4mk}}{2m}
$$

The solution is:

$$
x(t)=C_1e^{r_1 t}+C_2e^{r_2 t}
$$

---

## 3. Numerical solution idea (RK4)

To solve numerically, set

$$
v=\dot x
$$

Then:

$$
\dot x=v
$$

$$
\dot v=-\frac{b}{m}v-\frac{k}{m}x
$$

This system can be solved with RK4.

---

## 4. Effect of parameter \(b\)

- Larger \(b\) means stronger damping.
- Small \(b\): oscillations decay slowly.
- Critical \(b\): fastest return without oscillation.
- Large \(b\): no oscillation, slow return.

---

## Final results

Characteristic equation:

$$
mr^2+br+k=0
$$

Underdamped:

$$
x(t)=e^{-\frac{b}{2m}t}\big(C_1\cos(\omega_d t)+C_2\sin(\omega_d t)\big)
$$

Critically damped:

$$
x(t)=(C_1+C_2 t)e^{-\frac{b}{2m}t}
$$

Overdamped:

$$
x(t)=C_1e^{r_1 t}+C_2e^{r_2 t}
$$
