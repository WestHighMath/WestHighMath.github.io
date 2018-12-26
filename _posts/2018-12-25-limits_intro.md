---
title: "Limits"
date: 2018-12-25
tags: [limits]
mathjax: "true"
---

Welcome to your first calculus lesson! We'll be starting with a fundamental concept to calculus known as **limits**.

If you are still a little shaky about the idea of functions, I suggest you go [here](/function_review/) for a quick review.

Before we go in depth with formal definitions, we begin with some motivation to intuitively understand what limits are.

## Motivation
Suppose we have the function:

$$ f(x) = x^2 $$

We know that at $$x = 2$$, $$f(2) = 4$$ since $$2^2 = 4$. But what about the $$x$$ values near $$x = 2$$? Like $$x = 1.9$$

$$f(1.9) = 1.9^2 = 3.61$$

or $$x = 1.99$$

$$f(1.9) = 1.99^2 = 3.9601$$

How about $$x = 2.1$$ ?

$$f(2.1) = 2.1^2 = 4.41$$

or $$x = 2.01$$

$$f(2.01) = 2.01^2 = 4.0401$$

You get the idea; we're plugging in numbers getting closer and closer to $$2$$ from either side of it.

Now, let's look at a function table of these values (excuse my bad handwriting/drawing skills):

<img src="{{ site.url }}{{ site.baseurl }}/images/limits_motivation.png" alt="linearly separable data">

From the table, you might able to see a pattern. What's happening to the value of the function as we make $$x$$ closer and closer to $$2$$? The function is getting closer and closer to $$4$$.

If you're not convinced, plug in values close to 2, like $$1.999999$$ or $$2.000001$$. You'll see that $$f(x)$$ is some number extremely close to 4, but **not $$4$$ itself$**.

The value we get by asking ourselves, **what number is the function approaching as $$x$$ approaches some value?**, is what we call the **limit** of the function as we **approach some $$x$$ value**.
