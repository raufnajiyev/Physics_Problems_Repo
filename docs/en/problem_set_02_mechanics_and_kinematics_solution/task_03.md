# Problem 3 – Elimination of time and interpretation of acceleration

The parametric equations are:

$$
x(t)=2t^2,\qquad y(t)=3t^3
$$

---

## 1. Eliminate the parameter \(t\)

From

$$
x=2t^2
$$

we get:

$$
t^2=\frac{x}{2}
$$

Thus:

$$
t=\pm\sqrt{\frac{x}{2}}
$$

Now use

$$
y=3t^3
$$

Square both sides of \(y\) relation if needed, or use \(t^3=t\cdot t^2\):

$$
y=3t\cdot \frac{x}{2}
$$

A more convenient elimination is:

$$
y^2=9t^6
$$

From \(x=2t^2\), we get:

$$
t^6=\left(\frac{x}{2}\right)^3
$$

Therefore:

$$
y^2=9\left(\frac{x}{2}\right)^3
$$

$$
y^2=\frac{9}{8}x^3
$$

---

## 2. Trajectory

The Cartesian equation is:

$$
y^2=\frac{9}{8}x^3
$$

This is a semicubical parabola.

---

## 3. Velocity vector

Position vector:

$$
\vec r(t)=(2t^2,3t^3)
$$

Differentiate:

$$
\vec v(t)=\frac{d\vec r}{dt}=(4t,9t^2)
$$

Magnitude:

$$
|\vec v(t)|=\sqrt{(4t)^2+(9t^2)^2}
$$

$$
|\vec v(t)|=\sqrt{16t^2+81t^4}
$$

$$
|\vec v(t)|=|t|\sqrt{16+81t^2}
$$

---

## 4. Acceleration vector

Differentiate velocity:

$$
\vec a(t)=\frac{d\vec v}{dt}=(4,18t)
$$

Magnitude:

$$
|\vec a(t)|=\sqrt{4^2+(18t)^2}
$$

$$
|\vec a(t)|=\sqrt{16+324t^2}
$$

---

## 5. Is the acceleration constant?

The acceleration vector is:

$$
\vec a(t)=(4,18t)
$$

Its second component depends on \(t\), so the acceleration is **not constant**.

Also its magnitude depends on \(t\), so \( |\vec a(t)| \) is not constant either.

---

## Final results

Trajectory:

$$
y^2=\frac{9}{8}x^3
$$

Velocity:

$$
\vec v(t)=(4t,9t^2)
$$

Speed:

$$
|\vec v(t)|=\sqrt{16t^2+81t^4}
$$

Acceleration:

$$
\vec a(t)=(4,18t)
$$

Acceleration magnitude:

$$
|\vec a(t)|=\sqrt{16+324t^2}
$$

Acceleration is **not constant**.
