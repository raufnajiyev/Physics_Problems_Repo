# Problem 7 – Work of a force along a trajectory

Given force:

$$
\vec F(x,y)=(y,2x)
$$

Trajectory:

$$
x=t, \qquad y=t^2, \qquad t\in[0,1]
$$

We determine the velocity vector, the work done by the force along the trajectory, and the numerical approximation using a Riemann sum.

---

# 1. Velocity vector

The trajectory can be written as the position vector:

$$
\vec r(t)=(x(t),y(t))=(t,t^2)
$$

Differentiate to obtain the velocity vector:

$$
\vec v(t)=\frac{d\vec r(t)}{dt}
$$

$$
\vec v(t)=\left(\frac{d}{dt}t,\frac{d}{dt}t^2\right)
$$

$$
\vec v(t)=(1,2t)
$$

So

$$
d\vec r=\vec v(t)\,dt=(1,2t)\,dt
$$

---

# 2. Work done by the force along the trajectory

The work of a force field along a curve is:

$$
W=\int_C \vec F \cdot d\vec r
$$

Since the curve is parameterized by \(t\), we write:

$$
W=\int_0^1 \vec F(\vec r(t))\cdot \vec v(t)\,dt
$$

---

## Step 1: Substitute the trajectory into the force field

Given

$$
\vec F(x,y)=(y,2x)
$$

and

$$
x=t,\qquad y=t^2
$$

we get

$$
\vec F(\vec r(t))=(t^2,2t)
$$

---

## Step 2: Compute the dot product

We already have

$$
\vec v(t)=(1,2t)
$$

So

$$
\vec F(\vec r(t))\cdot \vec v(t)
=
(t^2,2t)\cdot(1,2t)
$$

$$
=t^2\cdot 1 + 2t\cdot 2t
$$

$$
=t^2+4t^2
$$

$$
=5t^2
$$

Therefore

$$
W=\int_0^1 5t^2\,dt
$$

---

## Step 3: Compute the integral

$$
W=5\int_0^1 t^2\,dt
$$

$$
W=5\left[\frac{t^3}{3}\right]_0^1
$$

$$
W=5\left(\frac13-0\right)
$$

$$
W=\frac53
$$

So the analytical value of the work is:

$$
W=\frac53
$$

Approximate numerical value:

$$
W\approx 1.6667
$$

---

# 3. Riemann sum form

The integral

$$
W=\int_0^1 5t^2\,dt
$$

can be written as the limit of a Riemann sum.

Divide the interval \([0,1]\) into \(N\) equal parts:

$$
\Delta t=\frac1N
$$

Take sample points

$$
t_i=\frac{i}{N}, \qquad i=1,2,\dots,N
$$

Then the Riemann sum is

$$
W_N=\sum_{i=1}^{N} 5t_i^2\,\Delta t
$$

Substitute \(t_i=\frac{i}{N}\) and \(\Delta t=\frac1N\):

$$
W_N=\sum_{i=1}^{N} 5\left(\frac{i}{N}\right)^2\frac1N
$$

$$
W_N=\frac{5}{N^3}\sum_{i=1}^{N} i^2
$$

Using the formula

$$
\sum_{i=1}^{N} i^2=\frac{N(N+1)(2N+1)}{6}
$$

we obtain

$$
W_N=\frac{5}{N^3}\cdot \frac{N(N+1)(2N+1)}{6}
$$

$$
W_N=\frac{5(N+1)(2N+1)}{6N^2}
$$

As \(N\to\infty\),

$$
W_N\to \frac53
$$

which agrees with the analytical result.

---

# 4. Numerical interpretation for HTML/JS

In an HTML/JS application, we can:

1. draw the trajectory
   $$
   x=t,\qquad y=t^2,\qquad t\in[0,1]
   $$

2. evaluate the force field along the path,

3. compute the approximate work using a finite Riemann sum,

4. compare the numerical result with the exact value

$$
W=\frac53
$$

5. show that increasing \(N\) improves the approximation.

---

# Final results

Position vector:

$$
\vec r(t)=(t,t^2)
$$

Velocity vector:

$$
\vec v(t)=(1,2t)
$$

Force along the trajectory:

$$
\vec F(\vec r(t))=(t^2,2t)
$$

Dot product:

$$
\vec F(\vec r(t))\cdot\vec v(t)=5t^2
$$

Work integral:

$$
W=\int_0^1 5t^2\,dt
$$

Exact result:

$$
W=\frac53
$$

Approximate value:

$$
W\approx 1.6667
$$

Riemann sum:

$$
W_N=\sum_{i=1}^{N} 5\left(\frac{i}{N}\right)^2\frac1N
$$

Closed form of the sum:

$$
W_N=\frac{5(N+1)(2N+1)}{6N^2}
$$
