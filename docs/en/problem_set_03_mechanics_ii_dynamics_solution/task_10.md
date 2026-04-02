# Problem 10 – Numerical model of a dynamical system

Potential:

$$
U(x)=\frac{k}{2}x^2+\lambda x^4
$$

---

## 1. Determine the force

The force is related to the potential by:

$$
F(x)=-\frac{dU}{dx}
$$

Differentiate:

$$
\frac{dU}{dx}=kx+4\lambda x^3
$$

Thus:

$$
F(x)=-(kx+4\lambda x^3)
$$

---

## 2. Equation of motion

By Newton's second law:

$$
m\ddot x=F(x)
$$

So:

$$
m\ddot x=-(kx+4\lambda x^3)
$$

or

$$
m\ddot x+kx+4\lambda x^3=0
$$

This is a nonlinear oscillator equation.

---

## 3. Numerical solution

To solve numerically, we rewrite the system as first-order equations:

Let

$$
v=\dot x
$$

Then:

$$
\dot x=v
$$

$$
\dot v=-\frac{1}{m}(kx+4\lambda x^3)
$$

These equations can be solved numerically, for example by:

- Euler's method,
- improved Euler,
- Runge-Kutta methods.

---

## 4. Effect of initial energy on motion

The total energy is:

$$
E=\frac12 mv^2+\frac{k}{2}x^2+\lambda x^4
$$

If the initial energy is small:

- motion stays near the origin,
- the oscillation is close to harmonic.

If the initial energy is larger:

- the motion explores the nonlinear part of the potential,
- oscillations become more strongly distorted.

---

## 5. Phase portrait

The phase portrait is the graph in the \((x,v)\)-plane.

For bounded motion:

- trajectories are closed curves.

Because of the quartic term \(\lambda x^4\), the shape differs from the simple ellipse of the harmonic oscillator.

---

## Final results

Potential:

$$
U(x)=\frac{k}{2}x^2+\lambda x^4
$$

Force:

$$
F(x)=-(kx+4\lambda x^3)
$$

Equation of motion:

$$
m\ddot x+kx+4\lambda x^3=0
$$

Equivalent first-order system:

$$
\dot x=v
$$

$$
\dot v=-\frac{1}{m}(kx+4\lambda x^3)
$$
