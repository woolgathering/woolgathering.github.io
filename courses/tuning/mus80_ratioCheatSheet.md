# Ratio Cheatsheet

Ratios can be thought of as either _pitches_ or _intervals_, depending on the context. In both cases, the math is the same. There three parts to getting new ratios:

- __Ascend (multiply) or descend (divide)__
  - To find the interval between two pitches expressed as intervals, descend the ratio of the smaller from the larger (i.e divide the bigger ratio by the smaller).
- __Reduce__: reduce both the numerator and denominator by their highest common factor
- __Bring into an octave__: if needed, independently divide/multiply the numerator and/or denominator by a factors of 2 (octaves) to bring the ratio into the interval of 1 to 2.

__Inversion__<br/>
To invert an interval (get the opposite), all you do is take the reciprocal. Example: the inversion of $\frac{3}{2}$ is $\frac{2}{3}$. Then we bring that into an octave by multiplying the numerator by 2: $\frac{4}{3}$. So the inversion of a fifth is a fourth.

__Something to remember__: we only want integers in our ratios. You'll see otherwise but it's confusing.

## Ascending and Descending

### Ascending
When we have a pitch as a ratio and we want to ascend a given interval also expressed as a ratio, we want to _multiply_ the two together.

#### Example
$\text{Start at }\frac{4}{3} \text{ and go up } \frac{3}{2}$

Let's assume that we're at the pitch $\frac{4}{3}$ (F, if our "base" is C) and we want to go up by $\frac{3}{2}$ (a "perfect fifth"). Since we want to ascend, we need to multiply:

$$
\frac{4}{3} \times \frac{3}{2} = \frac{12}{6}
$$

Then we need to reduce our new ratio to make it as simple as possible, as well as bring it into the octave.

$$
\frac{12}{6} = \frac{12/6}{6/6} = \frac{2}{1}
$$

The greatest common factor (GCF) of 12 and 6 was 6, so I factored that out. Then we're left with $\frac{2}{1}$ which is already good.

### Descending
When we have a pitch and we want to descend by a given interval also expressed as a ratio, we want to _divide_ the ratios. Recall that dividing fractions is the same thing as multiplying by the reciprocal.

#### Example
Start at $\frac{16}{9}$ and go down $\frac{3}{2}$.

Since we're descending, we need to divide, which is the same as multiplying by the reciprocal:

$$
\frac{16}{9} \div \frac{3}{2} = \frac{16}{9} \times \frac{2}{3} = \frac{32}{27}
$$

Then we check to see if we need to reduce our ratio. The GCF of 32 and 27 is 1 so there's nothing to do with reducing. Now we check to see if it's in the interval 1 to 2. Since $32/27 = 1.18518518519$ it's already in an octave so we're done. This means that if we start at the pitch $\frac{16}{9}$ and go down $\frac{3}{2}$, we get the pitch $\frac{32}{27}$.


### Proof: the Greek enharmonic tetrachord is $\frac{4}{3}$ (a perfect fouth)
The intervals that make up the Greek enharmonic tetrachord are 28/27, 36/35 and 5/4. Since we need to add the ratios together in "interval-space", we need to multiply. So, let's start with the first two:

$$
\frac{28}{27} \times \frac{36}{35} = \frac{1008}{945}
$$

Now we need to reduce our result. Before I start dealing with octaves, I'm going to figure out what the common factors are, then choose the biggest one. The factors of 945 are: 1, 3, 5, 7, 9, 15, 21, 27, 35, 45, 63, 105, 135, 189, 315, 945. The factors of 1008 are: 1, 2, 3, 4, 6, 7, 8, 9, 12, 14, 16, 18, 21, 24, 28, 36, 42, 48, 56, 63, 72, 84, 112, 126, 144, 168, 252, 336, 504, 1008. So the common factors are 1, 3, 7, 9, 21, 63. So I'll reduce both the numerator and denominator by a factor of 63, the largest common factor:

$$
\frac{1008/63}{945/63} = \frac{16}{15}
$$

Since $\frac{16}{15}$ is already between 1 and 2, there's nothing more to do. Let's keep going: go up 5/4 (the last interval in our tetrachord) from 16/15. I'm going multiply ("go up") and reduce in one equation here to show my thinking:

$$
\frac{16}{15} \times \frac{5}{4} = \frac{80}{60} = \frac{8}{6} = \frac{8/2}{6/2} = \frac{4}{3}
$$

So we can see that when we ascend all of the intervals of the Greek enharmonic tetrachord, we get a $\frac{4}{3}$ (i.e. a perfect fourth).

## Inverting Intervals
To get the inverse of an interval, simply take the reciprocal and bring into an octave. Let's say we want to get the inverse of the harmonic seventh, $\frac{7}{4}$. To do that, we literally invert the ratio and bring into an octave:

$$
\frac{4}{7} = \frac{4\times 2}{7} = \frac{8}{7}
$$

Since $\frac{4}{7}$ was not in the interval between 1 and 2, I had to either divide the denominator by 2 or multiply the numerator by 2. Since dividing the denominator would give me a decimal number, I decided to multiply to multiply the numerator by two (go up an octave) which gave me a reduced ratio in the interval I needed.
