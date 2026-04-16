# Problem 10 – Double pendulum and deterministic chaos

A double pendulum with masses \(m_1,m_2\) and rod lengths \(l_1,l_2\) is considered.

The generalized coordinates are the angles:

$$
\theta_1(t),\qquad \theta_2(t)
$$

---

## 1. Coordinates

The Cartesian coordinates of the masses are:

For the first mass:

$$
x_1=l_1\sin\theta_1,\qquad y_1=-l_1\cos\theta_1
$$

For the second mass:

$$
x_2=x_1+l_2\sin\theta_2
$$

$$
y_2=y_1-l_2\cos\theta_2
$$

Thus:

$$
x_2=l_1\sin\theta_1+l_2\sin\theta_2
$$

$$
y_2=-l_1\cos\theta_1-l_2\cos\theta_2
$$

---

## 2. Numerical integration

The full equations of motion are nonlinear and usually solved numerically, for example by:

- Euler method,
- RK4,
- adaptive methods.

---

## 3. Sensitivity to initial conditions

If two systems start with almost identical initial angles, their trajectories can diverge strongly after some time.

This is a hallmark of deterministic chaos.

---

## 4. Interpretation

The double pendulum is deterministic, but very sensitive to initial conditions.

Thus:

- short-term prediction is possible,
- long-term prediction becomes difficult.

---

## Final results

Coordinates:

$$
x_1=l_1\sin\theta_1,\qquad y_1=-l_1\cos\theta_1
$$

$$
x_2=l_1\sin\theta_1+l_2\sin\theta_2
$$

$$
y_2=-l_1\cos\theta_1-l_2\cos\theta_2
$$

The system is nonlinear and exhibits deterministic chaos.
