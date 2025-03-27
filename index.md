title: About Collatz Conjecture
content-title: Collatz Conjecture


## Every subgroup of a cyclic group is cyclic

#### proof:
Let $H\leq G$ be any subgroup of $G$. Let $G=<a>$ where $a\in G$. Now, any element of $H$ looks like $a^m$ for some $m\geq 0$. Choose, the least positive integer $m>0$ such that $a^m \in H$.
*Claim*: $H=<a^m>$.
proof: As, $a^m\in H$, 
$$
\begin{equation}
<a^m>\subseteq H
\end{equation}
$$

Now, we will show, $<>a^m\supseteq H$.
Let $a^l \in H$ fr some $l> 0$ hence $l>m$ as $m$ is the least positive power of $a$ in $H$ amd hence, $l=mq+r$ and $0\leq r<m$. Hence $$a^l=a^{mq+r}=a^{mq}a^r$$ and hence,
$$a^r=a^la^{-mq}$$.
As, $a^l,a^{mq}\in H$ and $H$ is a subgroup then $a^r\in H$ but a cotradiction as $r<m$. Hence $r=0$ and $l=mq$ and 

$$
\begin{equation}
<a^m>\supseteq H
\end{equation}
$$

And by (1) and (2) we get,
$$
\begin{equation}
<a^m>= H
\end{equation}
$$