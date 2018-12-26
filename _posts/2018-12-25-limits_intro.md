---
title: "1.1 Limits"
date: 2018-12-25
tags: [limits]
mathjax: "true"
permalink: /limits_intro/
---

Welcome to your first calculus lesson! We'll be starting with a fundamental concept to calculus known as **limits**.

If you are still a little shaky about the idea of functions, I suggest you go [here](/function_review/) for a quick review.

Before we go in depth with formal definitions, we begin with some motivation to intuitively understand what limits are.

## Motivation
Suppose we have the function:

$$ f(x) = x^2 $$

We know that at $$x = 2$$, $$f(2) = 4$$ since $$2^2 = 4$$. But what about the $$x$$ values near $$x = 2$$? Like $$x = 1.9$$

$$f(1.9) = 1.9^2 = 3.61$$

or $$x = 1.99$$

$$f(1.9) = 1.99^2 = 3.9601$$

How about $$x = 2.1$$ ?

$$f(2.1) = 2.1^2 = 4.41$$

or $$x = 2.01$$

$$f(2.01) = 2.01^2 = 4.0401$$

You get the idea; we're plugging in numbers getting closer and closer to $$2$$ from either side of it.

Now, let's look at a function table of these values (excuse my bad handwriting/drawing skills):

<img src="{{ site.url }}{{ site.baseurl }}/images/limits_motivation.png" alt="motivation">

From the table, you might able to see a pattern. What's happening to the value of the function as we make $$x$$ closer and closer to $$2$$? The function is getting closer and closer to $$4$$.

If you're not convinced, plug in values close to 2, like $$1.999999$$ or $$2.000001$$. You'll see that $$f(x)$$ is some number extremely close to 4, but **not $$4$$ itself**.

The value we get by asking ourselves, **what number is the function approaching as $$x$$ approaches some value?**, is what we call the **limit** of the function as we **approach some $$x$$ value**.

Now, we are ready to delve more deeply into the concept of the limit.

## Limits

Using the example above, we can say with words that the **limit** of the function $$f(x) = x^2$$ as we approach $$x = 2$$ is equal to $$4$$.

The formal mathematical notation for what we just said is

$$
\lim_{x \to 2} x^2 = 4
$$

or

$$
\lim_{x \to 2} f(x) = 4
$$

where $$f(x) = x^2$$.

"lim" stands for limit. $$x \to 2$$ means "as $$x$$ approaches 2". Then we put in our function. We can put it in directly like the first example. Or, we can simply put in $$f(x)$$ and define $$f(x)$$ afterwards like in the second example. Then, we write what the limit equals.

To reinforce this idea of limits, let's look at this same example but graphically.

<img src="{{ site.url }}{{ site.baseurl }}/images/limit_graph_example.png" alt="motivation">

We have a graph of $$f(x) = x^2$$. We can easily see that at $$x = 2$$, $$y = f(2) = 4$$. The two points on either side of $$x = 2$$ give $$y$$ points on the graph that are close to $$y = 4$$. You can imagine that as we push our $$x$$ points closer to 2, the $$y$$ points will get closer to 4.

## Definition of a Limit

In general terms, a limit is defined as

$$
\lim_{x \to a} f(x) = L
$$

This says the limit of $$f(x)$$ as $$x$$ approaches $$a$$ is $$L$$, where $$a$$ and $$L$$ are some real number.

This definition is informal but is sufficient for AP and IB courses, but if you want the formal definition, click [here]() for the epsilon-delta definition of a limit.

You have finished the introductory lesson on limits. Click [here](/limits_cont/) to continue.
