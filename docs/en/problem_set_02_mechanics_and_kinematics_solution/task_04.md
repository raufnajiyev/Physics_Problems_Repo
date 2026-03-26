# Problem 4 – Circular motion

A body moves in a circle of radius \(R\) with angular velocity \(\omega\).

---

## 1. Position vector

For circular motion in the plane:

$$
\vec r(t)=\big(R\cos(\omega t),R\sin(\omega t)\big)
$$

---

## 2. Velocity vector

Differentiate position:

$$
\vec v(t)=\frac{d\vec r}{dt}
$$

$$
\vec v(t)=\big(-R\omega\sin(\omega t),R\omega\cos(\omega t)\big)
$$

---

## 3. Acceleration vector

Differentiate velocity:

$$
\vec a(t)=\frac{d\vec v}{dt}
$$

$$
\vec a(t)=\big(-R\omega^2\cos(\omega t),-R\omega^2\sin(\omega t)\big)
$$

---

## 4. Magnitudes

### Position magnitude

$$
|\vec r(t)|=\sqrt{R^2\cos^2(\omega t)+R^2\sin^2(\omega t)}
$$

$$
|\vec r(t)|=R
$$

### Velocity magnitude

$$
|\vec v(t)|=\sqrt{R^2\omega^2\sin^2(\omega t)+R^2\omega^2\cos^2(\omega t)}
$$

$$
|\vec v(t)|=R\omega
$$

### Acceleration magnitude

$$
|\vec a(t)|=\sqrt{R^2\omega^4\cos^2(\omega t)+R^2\omega^4\sin^2(\omega t)}
$$

$$
|\vec a(t)|=R\omega^2
$$

---

## 5. Show that the acceleration is centripetal

We have:

$$
\vec a(t)=\big(-R\omega^2\cos(\omega t),-R\omega^2\sin(\omega t)\big)
$$

Factor out \(-\omega^2\):

$$
\vec a(t)=-\omega^2\big(R\cos(\omega t),R\sin(\omega t)\big)
$$

Thus:

$$
\vec a(t)=-\omega^2\vec r(t)
$$

So acceleration is directed opposite to the position vector, that is, toward the center of the circle.

Therefore the acceleration is **centripetal**.

---

## Final results

$$
\vec r(t)=\big(R\cos(\omega t),R\sin(\omega t)\big)
$$

$$
\vec v(t)=\big(-R\omega\sin(\omega t),R\omega\cos(\omega t)\big)
$$

$$
\vec a(t)=\big(-R\omega^2\cos(\omega t),-R\omega^2\sin(\omega t)\big)
$$

$$
|\vec r(t)|=R
$$

$$
|\vec v(t)|=R\omega
$$

$$
|\vec a(t)|=R\omega^2
$$

and

$$
\vec a(t)=-\omega^2\vec r(t)
$$
