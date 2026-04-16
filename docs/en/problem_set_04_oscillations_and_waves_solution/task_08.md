# Problem 8 – Two coupled springs (two degrees of freedom)

Two masses are connected by springs with constants \(k_1\), \(k_2\), and \(k_3\).

Let \(x_1(t)\) and \(x_2(t)\) be the displacements.

---

## 1. Equations of motion

For the first mass:

$$
m\ddot x_1=-(k_1+k_2)x_1+k_2x_2
$$

For the second mass:

$$
m\ddot x_2=k_2x_1-(k_2+k_3)x_2
$$

So the system is:

$$
m\ddot x_1+(k_1+k_2)x_1-k_2x_2=0
$$

$$
m\ddot x_2-k_2x_1+(k_2+k_3)x_2=0
$$

---

## 2. Natural frequencies

Assume harmonic solutions:

$$
x_1=A_1 e^{i\omega t},\qquad x_2=A_2 e^{i\omega t}
$$

Substituting leads to a linear algebra system.  
The natural frequencies are obtained from the determinant condition:

$$
\det(K-\omega^2 M)=0
$$

where \(K\) is the stiffness matrix and \(M\) is the mass matrix.

---

## 3. Normal modes

Each natural frequency corresponds to a mode shape:

- symmetric mode,
- antisymmetric mode.

The mode vectors are found from the eigenvectors of the system matrix.

---

## 4. Energy exchange

Because the masses are coupled, energy can transfer from one mass to the other.

This leads to coupled oscillatory motion and beating-like behavior.

---

## Final results

Equations of motion:

$$
m\ddot x_1+(k_1+k_2)x_1-k_2x_2=0
$$

$$
m\ddot x_2-k_2x_1+(k_2+k_3)x_2=0
$$

Natural frequencies are obtained from:

$$
\det(K-\omega^2 M)=0
$$
