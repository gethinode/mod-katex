---
title: KaTeX test site
description: Site to test KaTeX module.
date: 2023-07-20
---

This is an inline $-b \pm \sqrt{b^2 - 4ac} \over 2a$ formula

This is not an inline formula:

$$x = a_0 + \frac{1}{a_1 + \frac{1}{a_2 + \frac{1}{a_3 + a_4}}}$$  
$$\forall x \in X, \quad \exists y \leq \epsilon$$

As of Hugo v0.122.0, you may author LaTeX formulae using the standard syntax directly in Markdown

````markdown
The probability of getting \(k\) heads when flipping \(n\) coins is:
\[
\tag*{(1)} P(E) = {n \choose k} p^k (1-p)^{n-k}
\]
````

For details, please have a look at the section [Mathematics in Markdown ](https://gohugo.io/content-management/mathematics/) of the official hugo documentation.

As an alternative to the standard syntax used above, formulae can also be authored using a [GLFM math block](https://docs.gitlab.com/ee/user/markdown.html#math):

````markdown
The probability of getting \(k\) heads when flipping \(n\) coins is:
```math
\tag*{(1)} P(E) = {n \choose k} p^k (1-p)^{n-k}
```
````
Both standard syntax and `math` block render to the same formula:

The probability of getting \(k\) heads when flipping \(n\) coins is:
```math
\tag*{(1)}  P(E) = {n \choose k} p^k (1-p)^{n-k}
```
