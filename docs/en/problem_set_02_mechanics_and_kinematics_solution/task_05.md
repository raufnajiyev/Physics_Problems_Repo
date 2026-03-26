# Problem 5 – Elliptical motion (purely kinematic)

The parametric equations are:

$$
x(t)=a\cos(\omega t),\qquad y(t)=b\sin(\omega t)
$$

---

## 1. Velocity

Position vector:

$$
\vec r(t)=\big(a\cos(\omega t),b\sin(\omega t)\big)
$$

Differentiate:

$$
\vec v(t)=\frac{d\vec r}{dt}
$$

$$
\vec v(t)=\big(-a\omega\sin(\omega t),b\omega\cos(\omega t)\big)
$$

---

## 2. Acceleration

Differentiate velocity:

$$
\vec a(t)=\frac{d\vec v}{dt}
$$

$$
\vec a(t)=\big(-a\omega^2\cos(\omega t),-b\omega^2\sin(\omega t)\big)
$$

---

## 3. Magnitude of velocity

$$
|\vec v(t)|=\sqrt{a^2\omega^2\sin^2(\omega t)+b^2\omega^2\cos^2(\omega t)}
$$

$$
|\vec v(t)|=\omega\sqrt{a^2\sin^2(\omega t)+b^2\cos^2(\omega t)}
$$

So the magnitude of velocity is generally **not constant**.

It is constant only if \(a=b\), that is, in the circular case.

---

## 4. Where is the velocity maximum?

We maximize:

$$
|\vec v(t)|=\omega\sqrt{a^2\sin^2(\omega t)+b^2\cos^2(\omega t)}
$$

So we maximize:

$$
a^2\sin^2(\omega t)+b^2\cos^2(\omega t)
$$

- if \(a>b\), maximum occurs when \(\sin^2(\omega t)=1\),
- if \(b>a\), maximum occurs when \(\cos^2(\omega t)=1\).

Thus:

- for \(a>b\), the maximum velocity occurs at
  $$
  \omega t=\frac{\pi}{2},\frac{3\pi}{2},\dots
  $$
- for \(b>a\), the maximum velocity occurs at
  $$
  \omega t=0,\pi,2\pi,\dots
  $$

The maximal value is:

$$
|\vec v|_{\max}=\omega\max(a,b)
$$

---

## 5. Magnitude of acceleration

$$
|\vec a(t)|=\sqrt{a^2\omega^4\cos^2(\omega t)+b^2\omega^4\sin^2(\omega t)}
$$

$$
|\vec a(t)|=\omega^2\sqrt{a^2\cos^2(\omega t)+b^2\sin^2(\omega t)}
$$

---

## Final results

Velocity:

$$
\vec v(t)=\big(-a\omega\sin(\omega t),b\omega\cos(\omega t)\big)
$$

Acceleration:

$$
\vec a(t)=\big(-a\omega^2\cos(\omega t),-b\omega^2\sin(\omega t)\big)
$$

Velocity magnitude:

$$
|\vec v(t)|=\omega\sqrt{a^2\sin^2(\omega t)+b^2\cos^2(\omega t)}
$$

Acceleration magnitude:

$$
|\vec a(t)|=\omega^2\sqrt{a^2\cos^2(\omega t)+b^2\sin^2(\omega t)}
$$

The speed is **not constant** in general.

Maximum speed:

$$
|\vec v|_{\max}=\omega\max(a,b)
$$
