# Exercises 1C

---

**1. For each of the following subsets of $\mathbf{F^3}$, determine whether it is a subspace of $\mathbf{F^3}$.
(a) $\lbrace (x_1, x_2, x_3) \in \mathbf{F^3}: x_1 + 2x_2 + 3x_3 = 0 \rbrace$
(b) $\lbrace (x_1, x_2, x_3) \in \mathbf{F^3}: x_1 + 2x_2 + 3x_3 = 4 \rbrace$
(c) $\lbrace (x_1, x_2, x_3) \in \mathbf{F^3}: x_1 x_2 x_3 = 0 \rbrace$
(d) $\lbrace (x_1, x_2, x_3) \in \mathbf{F^3}: x_1 = 5 x_3 \rbrace$**

(a) is a subspace of $\mathbf{F^3}$, because:

- $(0, 0, 0)$ satisfies $x_1 + 2x_2 + 3x_3 = 0$, means $0 \in U$.
  
- $U$ is closed under addition and closed under scalar multiplication, because for all $x = (x_1, x_2, x_3), y = (y_1, y_2, y_3) \in U$ and for all $\alpha \in \mathbf{F}$, we have

$$
\begin{aligned}

(x_1 + y_1) + 2(x_2 + y_2) + 3(x_3 + y_3) &= (x_1 + 2x_2 + 3x_3) + (y_1 + 2y_2 + 3y_3) = 0 \\

\alpha x_1 + 2(\alpha x_2) + 3(\alpha x_3) &= \alpha (x_1 + 2x_2 + 3x_3) = 0

\end{aligned}
$$

(b) is not a subspace of $\mathbf{F^3}$, because $0 \notin U$.

(c) is not a subspace of $\mathbf{F^3}$, because it is not closed under addition.

- $x = (1, 1, 0) \in U$ and $y = (0, 0, 1) \in U$, but $x + y = (1, 1, 1) \notin U$.

(d) is a subspace of $\mathbf{F^3}$, because:

- $(0, 0, 0)$ satisfies $x_1 = 5x_3$, means $0 \in U$.

- $U$ is closed under addition and closed under scalar multiplication, because for all $x = (x_1, x_2, x_3), y = (y_1, y_2, y_3) \in U$ and for all $\alpha \in \mathbf{F}$, we have

$$
\begin{aligned}

(x_1 + y_1) &= 5x_3 + 5y_3 = 5(x_3 + y_3) \\

\alpha x_1 &= \alpha (5x_3) = 5(\alpha x_3)

\end{aligned}
$$

---

**2. Verify all assertions about subspaces in Example 1.35.**

(a)

Let $U = \lbrace {(x_1, x_2, x_3, x_4) \in \mathbf{F^4} : x_3 = 5x_4 + b} \rbrace$, where $b \in \mathbf{F}$.

Suppose $U$ is a subspace, then $0 \in U$, means $b = 0$.

Suppose $b = 0$, then

- $(0, 0, 0, 0)$ satisfies $x_3 = 5x_4 + b$, means $0 \in U$.

- $U$ is closed under addition and closed under scalar multiplication, because for all $x = (x_1, x_2, x_3, x_4), y = (y_1, y_2, y_3, y_4)$ and for all $\alpha \in \mathbf{F}$, we have

$$
\begin{aligned}

(x_3 + y_3) &= 5x_4 + 5y_4 = 5(x_4 + y_4) \\

(\alpha x_3) &= \alpha (5x_4) = 5(\alpha x_4)

\end{aligned}
$$

- Thus, $U$ is a subspace of $\mathbf{F^4}$.

Therefore, $U$ is a subspace of $\mathbf{F^4}$ if and only if $b = 0$.

(b)

Let $U = \lbrace f: [0, 1] \rightarrow \mathbf{R}, f \text{ is continuous} \rbrace$.

For all $x \in [0, 1]$, the function $0$ such that $0(x) = 0$ is continuous, means $0 \in U$.

For all $f, g \in U$ and for all $x \in [0, 1]$, we have

$$
\begin{aligned}

(f + g)(x) = f(x) + g(x)

\end{aligned}
$$

Since the sum of two continuous functions is continuous, $f + g \in U$.

For all $\alpha \in \mathbf{R}$, we have

$$
\begin{aligned}

(\alpha f)(x) = \alpha f(x)

\end{aligned}
$$

Since a continuous function multiplies a constant is continuous, $\alpha f \in U$.

Therefore, $U$ is a subspace of $\mathbf{R^{[0, 1]}}$.

(c)

Let $U = \lbrace f : \mathbf{R} \rightarrow \mathbf{R}, \text{ f is differentiable} \rbrace$.

For all $x \in R$, the function $0$ such that $0(x) = 0$ is differentiable, means $0 \in U$.

For all $f, g \in U$ and for all $x \in \mathbf{R}$, we have

$$
\begin{aligned}

(f + g)(x) = f(x) + g(x)

\end{aligned}
$$

Since the sum of two differentiable functions is differentiable, $f + g \in U$.

For all $\alpha \in \mathbf{R}$, we have

$$
\begin{aligned}

(\alpha f)(x) = \alpha f(x)

\end{aligned}
$$

Since a differentiable function multiplies a constant is differentiable, $\alpha f \in U$.

Therefore, $U$ is a subspace of $\mathbf{R^R}$.

(d)

Let $U = \lbrace f : (0, 3) \rightarrow \mathbf{R}, f'(2) = b \rbrace$.

Suppose $U$ is a subspace of $\mathbf{R^{(0, 3)}}$, then for all $x \in (0, 3)$, the zero function $0$ such that $0(x) = 0$ is an element of $U$, means $0'(x) = 0 \Rightarrow b = 0$.

Suppose $b = 0$, then

- For all $x \in (0, 3)$, the function $0$ such that $0(x) = 0$, we have $0(2) = 0 \Rightarrow 0'(2) = 0 \Rightarrow b = 0$, means $0 \in U$.

- $U$ is closed under addition and closed under scalar multiplication, because for all $f, g \in U$ and $\alpha \in \mathbf{R}$, we have

$$
\begin{aligned}

(f + g)'(2) = f'(2) + g'(2) = 0

\\

(\alpha f)'(2) = \alpha f'(2) = 0

\end{aligned}
$$

Therefore, $U$ is a subspace of $\mathbf{R^{(0, 3)}}$ if and only if $b = 0$.

(e)

Let $U = \lbrace (a_n)_{n = 1}^{\infin} : a_n \in \mathbf{C}, \lim\limits_{n \to \infin} a_n = 0 \rbrace$.

The limit of the zero sequence $(0, 0, 0, ...)$ is $0$, means $0 \in U$.

$U$ is closed under addition and closed under scalar multiplication, because for all $x = (x_n)_{n = 1}^{\infin}, y = (y_n)_{n = 1}^{\infin} \in U$ and for all $\alpha \in \mathbf{C}$, we have

$$
\begin{aligned}

\lim\limits_{n \to \infin}(x_n + y_n) &= \lim\limits_{n \to \infin}x_n + \lim\limits_{n \to \infin}y_n = 0 + 0 = 0 \Rightarrow x + y \in U

\\

\lim\limits_{n \to \infin}(\alpha x_n) &= \alpha \lim\limits_{n \to \infin}x_n = \alpha 0 \Rightarrow \alpha x \in U

\end{aligned}
$$

Therefore, $U$ is a subspace of $\mathbf{C^\infin}$.

---

**3. Show that the set of differentiable real-valued functions of $f$ on the interval $(-4, 4)$ such that $f'(-1) = 3f(2)$ is a subspace of $\mathbf{R^{(-4, 4)}}$.**

Let $U = \lbrace f : (-4, 4) \rightarrow \mathbf{R}, f \text{ is differentiable and } f'(-1) = 3f(2) \rbrace$.

For all $x \in (-4, 4)$, the function $0$ such that $0(x) = 0$ is differentiable, and $0'(-1) = 0 = 3(0(2))$, means $0 \in U$.

$U$ is closed under addition and closed under scalar multiplication, because for all $f, g \in U$ and for all $\alpha \in \mathbf{R}$, we have

$$
\begin{aligned}

(f + g)'(-1) &= f'(-1) + g'(-1) = 3f(2) + 3g(2) = 3(f(2) + g(2)) = 3 ((f + g)(2))

\\

(\alpha f)'(-1) &= \alpha f'(-1) = \alpha (3f(2)) = 3(\alpha f(2)) = 3((\alpha f)(2))

\end{aligned}
$$

Therefore, $U$ is a subspace of $\mathbf{R^{(-4, 4)}}$.

---
