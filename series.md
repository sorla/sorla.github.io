---
layout: post
title:  "Everyday sequences and series"
date:   2023-11-30 10:05:58 +0800
categories: maths
---

# Everyday sequences and series

## Taylor
$$ f(x) \approx f(a) + \frac{f'(a)(x-a)}{1!} + \frac{f''(a)(x-a)^2}{2!} + \frac{f'''(a)(x-a)}^3{3!} ... $$

For approximating a function, a Chebyshev polynomial can provide a better fit over a range. Taylor series works well about a single point. Chebyshev tends to be slightly over in some places, slightly under in others, with balanced errors. Pade approximants (rational polynomials) are another option, giving a bit more flexibility than simple polynomials.

## Sums of integers
### Integers
$$ \sum_1^n{x} = \frac{n}{2}(n + 1) $$

### Integer squares
$$ \sum_1^n{x^2} = \frac{n}{6}(n + 1)(2n + 1) $$

## Geometric
For the first n terms (up to \\( r^{n-1} \\))

$$ \sum_{k=0}^{n-1}{ar^k} = a\frac{1-r^n}{1-r} $$

And in the limit as $$ n \to \infty $$, so long as ratio is <1:

$$ \sum_{k=0}^{\infty}{ar^k} = \frac{a}{1-r} $$
