# Problem 1 – Vectors and linear transformations

## Given vectors

$$
\vec a = (2,-1,3), \quad \vec b = (1,4,-2)
$$

---

# 1. Length of vectors

Vector length formula:

$$
|\vec v| = \sqrt{x^2+y^2+z^2}
$$

### Length of **a**

$$
|\vec a| = \sqrt{2^2 + (-1)^2 + 3^2}
$$

$$
= \sqrt{4 + 1 + 9}
$$

$$
= \sqrt{14}
$$

### Length of **b**

$$
|\vec b| = \sqrt{1^2 + 4^2 + (-2)^2}
$$

$$
= \sqrt{1 + 16 + 4}
$$

$$
= \sqrt{21}
$$

---

# 2. Normalized vector

Formula:

$$
\hat a = \frac{\vec a}{|\vec a|}
$$

$$
\hat a =
\left(
\frac{2}{\sqrt{14}},
\frac{-1}{\sqrt{14}},
\frac{3}{\sqrt{14}}
\right)
$$

---

# 3. Dot product

Formula:

$$
\vec a \cdot \vec b = a_x b_x + a_y b_y + a_z b_z
$$

Calculation:

$$
(2)(1) + (-1)(4) + (3)(-2)
$$

$$
= 2 - 4 - 6
$$

$$
= -8
$$

---

# 4. Angle between vectors

Formula:

$$
\vec a \cdot \vec b = |\vec a||\vec b|\cos\theta
$$

$$
\cos\theta =
\frac{-8}{\sqrt{14}\sqrt{21}}
$$

---

# 5. Cross product

$$
\vec a \times \vec b =
\begin{vmatrix}
i & j & k \\
2 & -1 & 3 \\
1 & 4 & -2
\end{vmatrix}
$$

Result:

$$
\vec a \times \vec b = (-10,7,9)
$$

---

# Parallelogram area

$$
|\vec a \times \vec b|
=
\sqrt{(-10)^2+7^2+9^2}
$$

$$
=
\sqrt{100+49+81}
$$

$$
=
\sqrt{230}
$$

---

# Matrix transformation

Given matrix:

$$
A =
\begin{pmatrix}
2 & 1 & 0 \\
0 & 1 & -1 \\
1 & 0 & 1
\end{pmatrix}
$$

Compute:

$$
A\vec a
$$

$$
=
\begin{pmatrix}
2 & 1 & 0 \\
0 & 1 & -1 \\
1 & 0 & 1
\end{pmatrix}
\begin{pmatrix}
2 \\
-1 \\
3
\end{pmatrix}
$$

Result:

$$
A\vec a = (3,-4,5)
$$

---

# Determinant

$$
det(A)=3
$$

---

# Orientation

Since

$$
det(A) > 0
$$

the transformation **preserves orientation of space**.
