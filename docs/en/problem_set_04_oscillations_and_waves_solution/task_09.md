# Problem 9 – Chain of \(N\) springs (discrete wave model)

A system of \(N\) masses connected by springs is considered.

---

## 1. Equations of motion

Let \(x_n(t)\) be the displacement of the \(n\)-th mass.

For an interior mass, Newton's second law gives:

$$
m\ddot x_n
=
k(x_{n+1}-x_n)-k(x_n-x_{n-1})
$$

Thus:

$$
m\ddot x_n=k(x_{n+1}-2x_n+x_{n-1})
$$

This is the discrete wave equation.

---

## 2. Numerical solution

The system can be solved numerically for different values of \(N\), for example:

- \(N=20\)
- \(N=50\)
- \(N=100\)

Time stepping methods can be used to observe the motion.

---

## 3. Local initial disturbance

If one mass is initially displaced, the disturbance propagates through the chain.

This models wave propagation in a discrete medium.

---

## 4. Propagation speed

The speed of propagation depends on:

- spring constant \(k\),
- mass \(m\).

Larger \(k\) gives faster propagation.  
Larger \(m\) gives slower propagation.

---

## Final results

Equation of motion for the \(n\)-th mass:

$$
m\ddot x_n=k(x_{n+1}-2x_n+x_{n-1})
$$

This is the discrete analogue of the wave equation.
