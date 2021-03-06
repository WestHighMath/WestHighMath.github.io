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
\lim_{x \to 1} \frac{x^3 - x^2}{x-1}
$$

If a limit is indeed simply a y-value, let's plug in $$x=1$$:

$$
\begin{align}
\lim_{x \to 1} \frac{x^3 - x^2}{x-1} &= \frac{1^3 - 1^2}{1-1}\\
&= \frac{1 - 1}{1-1}\\ &= \frac{0}{0}
\end{align}
$$

Hopefully you recognize that $$\frac{0}{0}$$ is impossible. Now, you might be tempted to say that there is no limit, that the limit **does not exist**.

Let's look at the graph of $$\frac{x^3 - x^2}{x-1}$$.

<img src="{{ site.url }}{{ site.baseurl }}/images/limit_hole_graph.png" alt="hole">

Remember that we're trying to find the limit as $$x$$ approaches $$1$$. Notice we have a hole at $$x = 1$$. This means if we plug in $$x = 1$$, there is no y-value. We have now confirmed this algebraically and graphically.

But a limit is asking what happens when you get **close** to a certain x-value, **not at the x-value itself**. So, looking at the points **near** $$x = 1$$, we can see that corresponding y-values are getting closer and closer to $$y = 1$$.

Now, we can properly answer the example question:

$$
\lim_{x \to 1} \frac{x^3 - x^2}{x-1} = 1
$$

The purpose of this section is to get you understand that conceptually, limits are not y-values. Sure, in some cases, you can plug in the x-value to find the limit, but like the example above, you sometimes can't do that. Limits describe the **behavior** of the function as it **approaches** an x-value.

I'll discuss some techniques to solving limits like the one above in the next lesson. But first, let's look at some rules for limits.

## Rules for limits

### Sum rule for limits

Given two different functions, f(x) and g(x), the limit of the sum of functions is the sum of their limits. So,

$$
\begin{align}
\lim_{x \to a} [f(x) + g(x)] &= \lim_{x \to a} f(x) + \lim_{x \to a} g(x)
\end{align}
$$

### Constant rule for limits

The limit of a constant is the constant itself regardless of what $$x$$ is approaching

$$
\lim_{x \to a} c = c
$$

This rule makes sense if you look at the graph below.

<img src="{{ site.url }}{{ site.baseurl }}/images/limit_constant_rule.png alt="constant_rule">

$$y = c$$ is just a horizontal line, so no matter what $$x$$ you choose, $$y$$ always equals $$c$$

### Constant multiple rule for limits

The limit of a function that is multiplied by a constant is the a constant multiple of the limit.

$$
\lim_{x \to a} k \cdot f(x) = k \cdot \lim_{x \to a} f(x)
$$

### Product rule for limits

The limit of the product of functions is the product of their limits.

$$
\begin{align}
\lim_{x \to a} [f(x)g(x)] &= \lim_{x \to a} f(x) \cdot \lim_{x \to a} g(x)
\end{align}
$$

### Quotient rule for limits

Same can be said for quotient of two functions.

$$
\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{\lim_{x \to a} f(x)} {\lim_{x \to a} g(x)}
$$

provided that

$$
\lim_{x \to a} g(x) \neq 0
$$

because we don't like division by zero.
