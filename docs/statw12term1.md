# StatW12Term1

## W12 Continuous Random Variables ADITYA

## Definition

## ➢ When outcomes for random event are numerical, but cannot be counted and are infinitely

## divisible, we have continuous random variables.

## ➢ A continuous random variable is one that has possible values that form an interval along the

```text
real number line. In other words, a continuous random variable can assume any value over
```

## an interval or intervals.

## Probability density function \(pdf\)

```text
➢ Every continuous random variable X has a curve associated with it.
➢ The probability distribution curve of a continuous random variable is also called its
probability density function. It is denoted by f (x)
P(X ∈ [a, b]) = P(a ≤ X ≤ b) is area under curve between a and b
```

## Properties of pdf

1. The area under the probability distribution curve of a continuous random variable between

    any two points is between 0 and 1.

2. Total area under the probability distribution curve of a continuous random variable is always

```text
➢ The area under the graph of the probability density function between points a and b is the
same regardless of whether the endpoints a and b are themselves included:
P(a ≤ X ≤ b) = P(a < X < b)
➢ The probability density curve of a random variable X is a curve that never goes below the x−
axis
```

## Example

```text
➢ Figure below is a probability density function for the random variable that represents the
time (in minutes) it takes a repairer to service a television. The numbers in the regions
represent the areas of those regions.
```

What is the probability that the repairer takes

1. Less than 20 =0.
2. Less than 40 =0.
3. More than 50 =0.
4. Between 40 and 70 minutes to complete a repair? =0.

## Cumulative distribution function

* For a continuous random variable X
* Since the probability that a continuous random variable X assumes a single value is always

    zero, we have

## Expectation and Variance

```text
➢ Expected value: E(X) = R x f (x)dx.
➢ Variance: Var(X) = R (x − E(X))2 f (x)dx
```

## Continuous Random Variables-Uniform distribution

**Introduction** ➢ A random variable is said to be uniformly distributed over the interval \[0, 1\] if its probability density function is given by

## Uniform distribution U\(a, b\)

```text
➢ A continuous random variable has a uniform distribution, denoted X ∼ U(a, b),
probability density function is:
```

## Graph of pdf of a Uniform distribution U\(2, 4\) and U\(−2, 2\)

## Standard uniform distribution

```text
➢ A random variable has the standard uniform distribution with minimum 0 and maximum 1 if
its probability density function is given by
```

The standard uniform distribution plays an important role in random variate generation. ➢ Verify f \(x\) is a pdff ➔\(x\) ≥ 0, for 0 &lt; x &lt; 1 ➔

## Graph of pdf of a Standard uniform distribution U\(0, 1\)

## Cumulative distribution of Uniform distribution

```text
➢ For X ∼ U(a, b)
```

## Cumulative distribution of Uniform distribution

o When x &lt; a F\(x\) = 0 o When x &gt; b F\(x\) =

o a &lt; x &lt; b The slope of the line between and is \(𝑏−^1 𝑎\).

## Cumulative distribution of standard uniform distribution

```text
➢ For X ∼ U(0, 1)
```

## Expectation of X ∼ U\(a, b\)

```text
➢ X ∼ U(a, b);
```

```text
➢
```

## Variance of X ∼ U\(a, b\)

```text
➢ X ∼ U(a, b);
```

### ➢

```text
➢
```

## Example: Computing probabilities given distribution

```text
➢ Suppose that X is a uniform random variable over the interval (0, 1). Find
```

1. P\(X &gt; 1/3\) = 2/
2. P\(X ≤ 0.7\) = 0.
3. P\(0.3 &lt; X ≤ 0.9\) = 0.
4. P\(0.2 ≤ X &lt; 0.8\) = 0.

## Example: Application-question

```text
➢ You are to meet a friend at 2 p.m. However, while you are always exactly on time, your friend
is always late and indeed will arrive at the meeting place at a time uniformly distributed
between 2 and 3 p.m. Find the probability that you will have to wait
```

1. At least 30 minutes
   1. Less than 15 minutes
   2. Between 10 and 35 minutes
   3. Less than 45 minutes

**Example: Application-solution** ➢ Let X denote the amount of time you will have to wait. X ∼ U\(0, 60\)

1. At least 30 minutes =P\(X ≥ 30\) = 30/60 = 1/
2. Less than 15 minutes =P\(X &lt; 15\) = 15/60 = 1/
3. Between 10 and 35 minutes= P\(10 ≤ X ≤ 35\) = 25/60 = 5/
4. Less than 45 minutes = P\(X &lt; 45\) = 45/60 = 3/

## Continuous Random Variables-Continuous distributions

## Non Uniform distribution

## Example

```text
➢ Suppose that the number of minutes of playing time of a certain college basketball player in a
randomly chosen game has the following density curve.
```

**Questions** Find the probability that the player plays 1.

```text
▪ Over 20 minutes
▪ 2. Less than 25 minutes
▪ 3. Between 15 and 35 minutes
▪ 4. More than 35 minutes
```

## Solution

Let X be amount of playing time in minutes. Find the probability that the player plays

1. Over 20 minutes =P\(X &gt; 20\) = 0.5 + 0.25 = 0.
2. Less than 25 minutes=P\(X &lt; 25\) = 0.25 + 0.25 = 0.
3. Between 15 and 35 minutes=P\(15 ≤ X ≤ 35\) = 0.125 + 0.5 + 0.125 = 0.
4. More than 35 minutes=P\(X &gt; 35\) = 0.

## Triangular distribution

```text
➢ It is now 2 p.m., and Joan is planning on studying for her statistics test until 6 p.m., when she
will have to go out to dinner. However, she knows that she will probably have interruptions
and thinks that the amount of time she will actually spend studying in the next 4 hours is a
random variable whose probability density curve is as follows:
```

## Questions

1. What is the height of the curve at the value 2?
2. What is the probability she will study more than 3 hrs?
3. What is the probability she will study between 1 and 3 hrs?

## Solution

1. What is the height of the curve at the value 2? =1/2unit
2. What is the probability she will study more than 3 hrs? =1/
3. What is the probability she will study between 1 and 3 hrs? =3/

## Exponential distribution

## ➢ A continuous random variable whose probability density function is given, for

## some λ &gt; 0, by

```text
is said to be an exponential random variable (or, more simply, is said to be exponentially
distributed) with parameter λ.
```

## Graph of pdf for different values of λ

## cdf of Exponential distribution

F\(a\) = P\(X ≤ a\)

## Graph of cdf for different values of λ

## Expectation and variance of exponential distribution

X ∼ exp\(λ\)

```text
➢
➢
➢
```

```text
Thus, the mean of the exponential is the reciprocal of its parameter λ, and the variance is the
mean squared.
```

## Application

In practice, the exponential distribution often arises as the distribution of the amount of time until some specific event occurs.

➢ Suppose that the length of a phone call in minutes is an exponential random variable with parameter λ = 0.1. If someone arrives immediately ahead of you at a public telephone booth, find the probability that you will have to wait a more than 10 minutes b between 10 and 20 minutes. Solution Let X denote the length of the call made by the person in the booth. X ∼ exp\(0.5\) a more than 10 minutes = P\(X &gt; 10\) =𝑒−^1 ≈ 0. b between 10 and 20 minutes= P\(10 &lt; X &lt; 20\) = F\(20\) − F\(10\) =𝑒−^1 − 𝑒−^2 ≈ 0.

NOTES BY- ADITYA DHAR DWIVEDI

