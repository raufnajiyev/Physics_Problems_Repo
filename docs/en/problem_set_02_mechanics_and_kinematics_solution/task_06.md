# Problem 6 – Cycloid: trajectory of a point on a rolling circle

A cycloid is given by:

$$
x(t)=R(\omega t-\sin(\omega t)),\qquad
y(t)=R(1-\cos(\omega t))
$$

---

## 1. Velocity vector

Differentiate both components.

### x-component:

$$
\frac{dx}{dt}=R\left(\omega-\omega\cos(\omega t)\right)
$$

$$
\frac{dx}{dt}=R\omega(1-\cos(\omega t))
$$

### y-component:

$$
\frac{dy}{dt}=R\omega\sin(\omega t)
$$

So the velocity vector is:

$$
\vec v(t)=\big(R\omega(1-\cos(\omega t)),\;R\omega\sin(\omega t)\big)
$$

---

## 2. Acceleration vector

Differentiate velocity.

### x-component:

$$
\frac{d^2x}{dt^2}=R\omega^2\sin(\omega t)
$$

### y-component:

$$
\frac{d^2y}{dt^2}=R\omega^2\cos(\omega t)
$$

So the acceleration vector is:

$$
\vec a(t)=\big(R\omega^2\sin(\omega t),\;R\omega^2\cos(\omega t)\big)
$$

---

## 3. Magnitude of velocity

$$
|\vec v(t)|=
\sqrt{\big(R\omega(1-\cos(\omega t))\big)^2+\big(R\omega\sin(\omega t)\big)^2}
$$

Factor out \(R\omega\):

$$
|\vec v(t)|=
R\omega\sqrt{(1-\cos(\omega t))^2+\sin^2(\omega t)}
$$

Expand:

$$
(1-\cos(\omega t))^2+\sin^2(\omega t)
=1-2\cos(\omega t)+\cos^2(\omega t)+\sin^2(\omega t)
$$

$$
=2-2\cos(\omega t)
$$

Thus:

$$
|\vec v(t)|=
R\omega\sqrt{2-2\cos(\omega t)}
$$

Using

$$
1-\cos\theta=2\sin^2\frac{\theta}{2}
$$

we get:

$$
|\vec v(t)|=
2R\omega\left|\sin\frac{\omega t}{2}\right|
$$

---

## 4. When does the point stop?

The point stops when:

$$
|\vec v(t)|=0
$$

Thus:

$$
2R\omega\left|\sin\frac{\omega t}{2}\right|=0
$$

So:

$$
\sin\frac{\omega t}{2}=0
$$

Hence:

$$
\frac{\omega t}{2}=k\pi
$$

$$
t=\frac{2k\pi}{\omega},\qquad k\in\mathbb Z
$$

These are the moments when the point temporarily stops relative to the ground.

---

## 5. Maximum value of velocity

The maximum occurs when

$$
\left|\sin\frac{\omega t}{2}\right|=1
$$

So:

$$
|\vec v|_{\max}=2R\omega
$$

---

## 6. Magnitude of acceleration

$$
|\vec a(t)|=
\sqrt{(R\omega^2\sin(\omega t))^2+(R\omega^2\cos(\omega t))^2}
$$

$$
|\vec a(t)|=
R\omega^2\sqrt{\sin^2(\omega t)+\cos^2(\omega t)}
$$

$$
|\vec a(t)|=R\omega^2
$$

So acceleration magnitude is constant.

---

## 7. Maximum value of acceleration

Since \( |\vec a(t)|=R\omega^2 \) is constant, the maximum value is:

$$
|\vec a|_{\max}=R\omega^2
$$

---

## 8. Comparison with circular motion in the moving frame

In the reference frame attached to the center of the circle, the point moves on a circle of radius \(R\).

In the ground frame, the center translates while the point rotates, and the resulting trajectory is a cycloid.

So:

- in the moving frame → circular motion,
- in the ground frame → cycloid.

---

## Final results

Velocity:

$$
\vec v(t)=\big(R\omega(1-\cos(\omega t)),\;R\omega\sin(\omega t)\big)
$$

Acceleration:

$$
\vec a(t)=\big(R\omega^2\sin(\omega t),\;R\omega^2\cos(\omega t)\big)
$$

Velocity magnitude:

$$
|\vec v(t)|=2R\omega\left|\sin\frac{\omega t}{2}\right|
$$

Stopping times:

$$
t=\frac{2k\pi}{\omega},\qquad k\in\mathbb Z
$$

Maximum velocity:

$$
|\vec v|_{\max}=2R\omega
$$

Acceleration magnitude:

$$
|\vec a(t)|=R\omega^2
$$

Maximum acceleration:

$$
|\vec a|_{\max}=R\omega^2
$$
