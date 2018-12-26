---
title: "1.2 More Limits and Rules for Limits"
date: 2018-12-26
tags: [limits]
mathjax: "true"
permalink: /limits_cont/
---

## Just y-values?
So with the example from the last lesson where

$$
\lim_{x \to 2} x^2 = 4
$$

you might start becoming suspicious. Isn't a limit just the y-value of the function at a given x-value?, you might ask. Let's see some more examples, like

$$
\lim_{x \to 3} x^2 = 9
$$

$$
\lim_{x \to 4} x^2 = 16
$$

or even changing the function to something like $$f(x) = 3x^3 + 2x + 1$$

$$
\lim_{x \to 1} f(x) = 6
$$

$$
\lim_{x \to 10} f(x) = 3021
$$

(note that $$f(1) = 6$$ and $$f(10) = 3021$$ as well).

Now you might be convinced that limits are just y-values. To some extent, you're right; a quick way of finding a limit is plugging in the x-value into the function to get the y-value.

But take a look at this limit:

$$
\lim{x \to 1} \frac{x^3 - x^2}{x-1}
$$

If a limit is indeed simply a y-value, let's plug in $$x=1$$:

$$
\begin{align}
\lim{x \to 1} \frac{x^3 - x^2}{x-1} &= \frac{1^3 - 1^2}{1-1}\\
&= \frac{1 - 1}{1-1}\\ &= \frac{0}{0}
\end{align}
$$

Hopefully you recognize that $$\frac{0}{0}$$ is impossible. Now, you might be tempted to say that there is no limit, that the limit **does not exist**.

Let's look at the graph of $$\frac{x^3 - x^2}{x-1}$$.
