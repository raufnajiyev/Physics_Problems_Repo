# Problem 10 – Angular momentum in circular motion

Consider circular motion in the \(xy\)-plane:

$$
\vec r(t)=\big(R\cos(\omega t),\;R\sin(\omega t),\;0\big)
$$

We determine the velocity, the angular momentum, its direction, and verify the relation between torque and the time derivative of angular momentum.

---

# 1. Velocity vector

The velocity is the derivative of the position vector:

$$
\vec v(t)=\frac{d\vec r(t)}{dt}
$$

Differentiate each component:

$$
\vec v(t)=\left(
\frac{d}{dt}\big(R\cos(\omega t)\big),
\frac{d}{dt}\big(R\sin(\omega t)\big),
\frac{d}{dt}(0)
\right)
$$

$$
\vec v(t)=\big(-R\omega\sin(\omega t),\;R\omega\cos(\omega t),\;0\big)
$$

The speed is:

$$
|\vec v(t)|=
\sqrt{(-R\omega\sin(\omega t))^2+(R\omega\cos(\omega t))^2}
$$

$$
|\vec v(t)|=
\sqrt{R^2\omega^2\sin^2(\omega t)+R^2\omega^2\cos^2(\omega t)}
$$

$$
|\vec v(t)|=R\omega
$$

So the speed is constant.

---

# 2. Angular momentum with respect to the origin

Angular momentum is defined as

$$
\vec L(t)=m\,\vec r(t)\times \vec v(t)
$$

We compute the cross product:

$$
\vec r(t)\times \vec v(t)=
\begin{vmatrix}
\mathbf i & \mathbf j & \mathbf k \\
R\cos(\omega t) & R\sin(\omega t) & 0 \\
-R\omega\sin(\omega t) & R\omega\cos(\omega t) & 0
\end{vmatrix}
$$

Only the \(k\)-component remains:

$$
\vec r(t)\times \vec v(t)=
\big(0,\;0,\;R^2\omega\cos^2(\omega t)+R^2\omega\sin^2(\omega t)\big)
$$

$$
\vec r(t)\times \vec v(t)=\big(0,\;0,\;R^2\omega\big)
$$

Therefore

$$
\vec L(t)=m\big(0,\;0,\;R^2\omega\big)
$$

So:

$$
\vec L(t)=\big(0,\;0,\;mR^2\omega\big)
$$

---

# 3. Show that \( |\vec L| = mR^2\omega \) is constant

The magnitude of the angular momentum vector is:

$$
|\vec L|=\sqrt{0^2+0^2+(mR^2\omega)^2}
$$

$$
|\vec L|=mR^2\omega
$$

Since \(m\), \(R\), and \(\omega\) are constants, the magnitude of \(\vec L\) is constant.

Also, the vector has only a \(z\)-component, so it is perpendicular to the \(xy\)-plane of motion.

---

# 4. Direction of \( \vec L \) (right-hand rule)

The direction of angular momentum is determined by the right-hand rule:

- point the fingers of your right hand in the direction of \(\vec r\),
- curl them toward \(\vec v\),
- your thumb points in the direction of \(\vec L\).

For the motion

$$
\vec r(t)=\big(R\cos(\omega t),R\sin(\omega t),0\big)
$$

the particle moves counterclockwise in the \(xy\)-plane (for \(\omega>0\)).

Therefore:

$$
\vec L
$$

points in the **positive \(z\)-direction**.

If the motion were clockwise, then \(\vec L\) would point in the negative \(z\)-direction.

---

# 5. Optional: constant centripetal force and torque

For uniform circular motion, the centripetal acceleration is

$$
\vec a(t)=\frac{d\vec v}{dt}
$$

Differentiate velocity:

$$
\vec a(t)=\big(-R\omega^2\cos(\omega t),\;-R\omega^2\sin(\omega t),\;0\big)
$$

Thus the force is

$$
\vec F(t)=m\vec a(t)=\big(-mR\omega^2\cos(\omega t),\;-mR\omega^2\sin(\omega t),\;0\big)
$$

This force points toward the center, so it is a centripetal force.

The torque is defined as

$$
\vec \tau=\vec r\times \vec F
$$

Compute:

$$
\vec r(t)\times \vec F(t)=
\begin{vmatrix}
\mathbf i & \mathbf j & \mathbf k \\
R\cos(\omega t) & R\sin(\omega t) & 0 \\
-mR\omega^2\cos(\omega t) & -mR\omega^2\sin(\omega t) & 0
\end{vmatrix}
$$

The rows are proportional, so the cross product is zero:

$$
\vec \tau=\vec 0
$$

So the torque is zero.

---

# 6. Verify the relationship \( \vec \tau = \frac{d\vec L}{dt} \)

We found

$$
\vec L(t)=\big(0,\;0,\;mR^2\omega\big)
$$

Differentiate with respect to time:

$$
\frac{d\vec L}{dt}=\big(0,\;0,\;0\big)
$$

So

$$
\frac{d\vec L}{dt}=\vec 0
$$

From the previous section we also found

$$
\vec \tau=\vec 0
$$

Therefore:

$$
\vec \tau=\frac{d\vec L}{dt}
$$

This confirms the general law for uniform circular motion.

---

# Physical interpretation

- The particle moves in a circle of radius \(R\) with constant angular speed \(\omega\).
- Its velocity is tangent to the circle.
- The angular momentum is constant in magnitude and direction.
- Because the centripetal force always points along the radius, it produces no torque about the center.
- As a result, angular momentum is conserved.

---

# Final results

Position vector:

$$
\vec r(t)=\big(R\cos(\omega t),\;R\sin(\omega t),\;0\big)
$$

Velocity:

$$
\vec v(t)=\big(-R\omega\sin(\omega t),\;R\omega\cos(\omega t),\;0\big)
$$

Angular momentum:

$$
\vec L(t)=\big(0,\;0,\;mR^2\omega\big)
$$

Magnitude:

$$
|\vec L|=mR^2\omega
$$

Acceleration:

$$
\vec a(t)=\big(-R\omega^2\cos(\omega t),\;-R\omega^2\sin(\omega t),\;0\big)
$$

Centripetal force:

$$
\vec F(t)=\big(-mR\omega^2\cos(\omega t),\;-mR\omega^2\sin(\omega t),\;0\big)
$$

Torque:

$$
\vec \tau=\vec 0
$$

Verification:

$$
\vec \tau=\frac{d\vec L}{dt}
$$
