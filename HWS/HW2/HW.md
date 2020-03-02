<font face = Times New Roman>
<font Size = 3>

# <center>Assigment 1</center>

### Question 1

**i.** $S=\{x \in \mathbb{R} | x = \sqrt {2} + k, k \in \mathbb{N} \}$

**ii.** proof: For any arbitrary $k\in \mathbb{N}$, we define $$S_k := (\sqrt{2} + k, \sqrt{2} + k + 1)$$ according to the definition, $S_k \subset \mathbb{R} \setminus S$. For arbitrary $x \in S_k$, let $\delta = min\{x- \sqrt{2} - k, \sqrt{2} + k + 1 - x\}$, $\exists B(x, \delta)$ is an open ball, thus $S_k$ is an open set.
Then the complement of $S$ in $\mathbb{R}$ $\overline{S} = \bigcup_{k \in \mathbb{N}} S_k$ is an open set. Therefore, $S$ is an closed set.
**iii.** proof: Since $\mathbb{N}$ is unbounded (according to the Archimedes character), $S$ is an unbounded set.
**iv.** $B((0, 0, 4), 1)$
**v.** proof: Obviously it is an open set since it is an oepn ball.
**vi.** proof: Denote point $(0, 0, 4)$ as $\vec x$, for arbitrary $\vec y$ in $B(\vec{x}, 1)$, $d(\vec x, \vec y) < 1$, thus $B(\vec x, 1)$ is bounded.
**vii.** $diam(B) = 2$.
proof: For arbitrary points $\vec{p}, \vec{q} \in B(\vec{x}, 1), d(\vec{x}, \vec{p}) < 1, d(\vec{x}, \vec{q}) < 1$, thus $d(\vec{x}, \vec{y}) < 2$ according to the triangular inequality.
Now consider two point sequences 
$$A_k = \{ (0, 0, 3 + \frac{1}{2 ^ k}) | k \in \mathbb{N} \}, B_k = \{ (0, 0, 5 - \frac{1}{2 ^ k}) | k \in \mathbb{N} \}$$
Obviously $A_k, B_k \subset B(\vec{x}, 1)$.
Then we can tell
$$\lim_{k \to \infty} d(A_k, B_k) = 2$$
Which means $\forall \varepsilon > 0, \exists N > 0$, when $k > N, d(A_k, B_k) > 2 - \varepsilon$. Then we can tell $sup(\vec{p}, \vec{q}) = 2$, which means $diam(B) = 2$.

### Question 2

**i.** $$\lim_{(x, y) \to (3.5)} (\frac{\sin (y - x)}{y - x}, \sqrt{y ^ 2 - x ^ 2})$$ existss  since when $(x, y) \to (3.5), y - x$ is nonzero. The limit is equal to $(\frac{\sin 2}{2}, 4)$
**ii.** $$\lim_{(x, y) \to (0, 0)} \frac{x ^ 4 - y ^ 3}{x ^ 3 - y ^ 4}$$ doesn't exists.
proof: Replace $y$ with $kx (k \in \mathbb{R})$, then the original formula is equal to $$\lim_{x \to 0} \frac{x ^ 4 - k ^ 3 x ^ 3}{x ^ 3 - k ^ 4 x ^ 4}$$ = $$\lim_{x \to 0} \frac{x - k ^ 3}{1 - k ^ 4 x}$$ = $-k ^ 3$ which is uncertain. Therefore, the limit doesn't exists.
**iii.** $$\lim\limits_{^{x \to \infty}_{y \to \infty}} \frac{x ^ 3 - y ^ 3}{x ^ 4 - y ^ 4}$$ 

