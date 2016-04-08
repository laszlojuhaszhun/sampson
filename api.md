# Bernoulli

**Extends Binomial**

The Binomial Distribution is a discrete probability distribution
with parameters n = _number of trials_ and p = _probability of success_.
See: [Bernoulli Distribution](https://en.wikipedia.org/wiki/Bernoulli_distribution)

## cdf

Calculate the probability of k or less in B(1, p).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability getting a value of k or less from B(1,p).

## constructor

Generate a new Bernoulli object.

**Parameters**

-   `p` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of success.

Returns **** 

## pdf

Calculate the probability of exaclty k in B(1, p).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of k happening in B(1,p).

## random

Generate a random value from B(1, p).

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The random value from B(1,p).

## sample

Generate an array of k random values from B(1, p).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number of values to generate.

Returns **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** An array of random values from B(1,p).

## cdf

Calculate the probability of k or less in B(1, p).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.
-   `p` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of success.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability getting a value of k or less from B(1,p).

## pmf

Calculate the probability of exaclty k in B(1, p).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.
-   `p` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of success.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of k happening in B(1,p).

## random

Generate a random value from B(1, p).

**Parameters**

-   `p` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of success.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The random value from B(1,p).

# Binomial

The Binomial Distribution is a discrete probability distribution
with parameters n = _number of trials_ and p = _probability of success_.
See: [Binomial Distribution](https://en.wikipedia.org/wiki/Binomial_distribution)

## cdf

Calculate the probability of k or less in B(n, p).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability getting a value of k or less from B(n,p).

## constructor

Generate a new Binomial object.

**Parameters**

-   `p` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of success.
-   `n` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** number of trials.

Returns **** 

## pdf

Calculate the probability of exaclty k in B(n, p).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of k happening in B(n,p).

## random

Generate a random value from B(n, p).

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The random value from B(n,p).

## sample

Generate an array of k random values from B(n, p).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number of values to generate.

Returns **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** An array of random values from B(n,p).

## cdf

Calculate the probability of k or less in B(n, p).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.
-   `p` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of success.
-   `n` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** number of trials.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability getting a value of k or less from B(n,p).

## kurtosis

Get the kurtosis.

**Parameters**

-   `p` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of success.
-   `n` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** number of trials.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The kurtosis of B(n,p).

## mean

Get the mean.

**Parameters**

-   `p` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of success.
-   `n` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** number of trials.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The mean of B(n,p).

## pmf

Calculate the probability of exaclty k in B(n, p).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.
-   `p` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of success.
-   `n` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** number of trials.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of k happening in B(n,p).

## random

Generate a random value from B(n, p).

**Parameters**

-   `p` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of success.
-   `n` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** number of trials.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The random value from B(n,p).

## relativeStdDev

Get the relative standard deviation.

**Parameters**

-   `p` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of success.
-   `n` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** number of trials.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The relative standard deviation of B(n,p).

## sample

Generate an array of k random values from B(n, p).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number of values to generate.
-   `p` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of success.
-   `n` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** number of trials.

Returns **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** An array of random values from B(n,p).

## skewness

Get the skewness.

**Parameters**

-   `p` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of success.
-   `n` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** number of trials.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The skewness of B(n,p).

## stdDev

Get the standard deviation.

**Parameters**

-   `p` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of success.
-   `n` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** number of trials.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The standard deviation of B(n,p).

## variance

Get the variance.

**Parameters**

-   `p` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of success.
-   `n` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** number of trials.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The variance of B(n,p).

# Exponential

The Exponential Distribution is a continuous probability distribution
with parameters r = _rate_.
See: [Exponential Distribution](https://en.wikipedia.org/wiki/Exponential_distribution)

## cdf

Calculate the probability of getting x or less from Exponential(mu).

**Parameters**

-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of getting x or less from Exponential(mu).

## constructor

Generate a new Exponential object.

**Parameters**

-   `mu` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The scale.

Returns **** 

## pdf

Calculate the probability of exaclty x in Exponential(mu).

**Parameters**

-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of x happening in Exponential(mu).

## random

Generate a random value from Exponential(mu).

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The random value from Exponential(mu).

## sample

Generate an array of k random values from Exponential(mu).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number of values to generate.

Returns **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** An array of random values from Exponential(mu).

## cdf

Calculate the probability of getting x or less Exponential(mu).

**Parameters**

-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.
-   `mu` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The scale.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of getting x or less from Exponential(mu).

## pdf

Calculate the probability of exaclty x in Exponential(mu).

**Parameters**

-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.
-   `mu` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The scale.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of x happening in Exponential(mu).

## random

Generate a random value from Exponential(mu).

**Parameters**

-   `mu` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The scale.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The random value from Exponential(mu).

## sample

Generate an array of k random values from Exponential(mu).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number of values to generate.
-   `mu` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The scale.

Returns **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** An array of random values from Exponential(mu).

# Normal

The Normal Distribution is a continuous probability distribution
with parameters mu = _mean_ and sigma = _standard deviation_.
See: [Normal Distribution](https://en.wikipedia.org/wiki/Normal)

## cdf

Calculate the probability of getting x or less from N(mu, sigma).

**Parameters**

-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of getting x or less from N(mu, sigma).

## constructor

Generate a new Normal object.

**Parameters**

-   `mu` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The mean.
-   `sigma` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The standard deviation.

Returns **** 

## pdf

Calculate the probability of exaclty x in N(mu, sigma).

**Parameters**

-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of x happening in N(mu, sigma).

## random

Generate a random value from N(mu, sigma).

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The random value from N(mu, sigma).

## sample

Generate an array of k random values from N(mu, sigma).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number of values to generate.

Returns **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** An array of random values from N(mu, sigma).

## cdf

Calculate the probability of getting x or less from N(mu, sigma).

**Parameters**

-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.
-   `mu` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The mean.
-   `sigma` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The standard deviation.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of getting x or less from N(mu, sigma).

## pdf

Calculate the probability of exaclty x in N(mu, sigma).

**Parameters**

-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.
-   `mu` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The mean.
-   `sigma` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The standard deviation.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of x happening in N(mu, sigma).

## random

Generate a random value from N(mu, sigma).

**Parameters**

-   `mu` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The mean.
-   `sigma` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The standard deviation.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The random value from N(mu, sigma).

## sample

Generate an array of k random values from N(mu, sigma).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number of values to generate.
-   `mu` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The mean.
-   `sigma` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The standard deviation.

Returns **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** An array of random values from N(mu, sigma).

# ChiSquared

The Chi-Squared Distribution is a continuous probability distribution
with parameters df = degrees of freedom\*.
See: [Chi-Squared Distribution](https://en.wikipedia.org/wiki/Chi-squared_distribution)

## cdf

Calculate the probability of getting x or less from ChiSquared(df).

**Parameters**

-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of getting x or less from ChiSquared(df).

## constructor

Generate a new ChiSquared object.

**Parameters**

-   `df` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The degrees of freedom.

Returns **** 

## pdf

Calculate the probability of exaclty x in ChiSquared(df).

**Parameters**

-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of x happening in ChiSquared(df).

## random

Generate a random value from ChiSquared(df).

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The random value from ChiSquared(df).

## sample

Generate an array of k random values from ChiSquared(df).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number of values to generate.

Returns **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** An array of random values from ChiSquared(df).

## cdf

Calculate the probability of getting x or less ChiSquared(df).

**Parameters**

-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.
-   `df` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The degrees of freedom.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of getting x or less from ChiSquared(df).

## pdf

Calculate the probability of exaclty x in ChiSquared(df).

**Parameters**

-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.
-   `df` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The degrees of freedom.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of x happening in ChiSquared(df).

## random

Generate a random value from ChiSquared(df).

**Parameters**

-   `df` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The degrees of freedom.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The random value from ChiSquared(df).

## sample

Generate an array of k random values from ChiSquared(df).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number of values to generate.
-   `df` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The degrees of freedom.

Returns **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** An array of random values from ChiSquared(df).

# StudentsT

The Chi-Squared Distribution is a continuous probability distribution
with parameters df = degrees of freedom\*.
See: [Student's t-Distribution](https://en.wikipedia.org/wiki/Student%27s_t-distribution)

## cdf

Calculate the probability of getting x or less from StudentsT(df).

**Parameters**

-   `t` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of getting x or less from StudentsT(df).

## constructor

Generate a new StudentsT object.

**Parameters**

-   `df` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The degrees of freedom.

Returns **** 

## pdf

Calculate the probability of exaclty x in StudentsT(df).

**Parameters**

-   `t` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of x happening in StudentsT(df).

## random

Generate a random value from StudentsT(df).

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The random value from StudentsT(df).

## sample

Generate an array of k random values from StudentsT(df).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number of values to generate.

Returns **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** An array of random values from StudentsT(df).

## cdf

Calculate the probability of getting x or less StudentsT(df).

**Parameters**

-   `t` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.
-   `df` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The degrees of freedom.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of getting x or less from StudentsT(df).

## pdf

Calculate the probability of exaclty x in StudentsT(df).

**Parameters**

-   `t` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.
-   `df` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The degrees of freedom.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of x happening in StudentsT(df).

## random

Generate a random value from StudentsT(df).

**Parameters**

-   `df` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The degrees of freedom.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The random value from StudentsT(df).

## sample

Generate an array of k random values from StudentsT(df).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number of values to generate.
-   `df` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The degrees of freedom.

Returns **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** An array of random values from StudentsT(df).

# Gamma

The Gamma Distribution is a continuous probability distribution
with parameters a = _shape_ and b = _rate_.
See: [Gamma Distribution](https://en.wikipedia.org/wiki/Gamma_distribution)

## cdf

Calculate the probability of getting x or less from Gamma(a, b).

**Parameters**

-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of getting x or less from Gamma(a, b).

## constructor

Generate a new Gamma object.

**Parameters**

-   `a` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The shape.
-   `a` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The rate.
-   `b` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** 

Returns **** 

## pdf

Calculate the probability of exaclty x in Gamma(a, b).

**Parameters**

-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of x happening in Gamma(a, b).

## random

Generate a random value from Gamma(a, b).

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The random value from Gamma(a, b).

## sample

Generate an array of k random values from Gamma(a, b).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number of values to generate.

Returns **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** An array of random values from Gamma(a, b).

## cdf

Calculate the probability of getting x or less Gamma(a, b).

**Parameters**

-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.
-   `a` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The shape.
-   `a` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The rate.
-   `b` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** 

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of getting x or less from Gamma(a, b).

## pdf

Calculate the probability of exaclty x in Gamma(a, b).

**Parameters**

-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The value to predict.
-   `a` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The shape.
-   `a` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The rate.
-   `b` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** 

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The probability of x happening in Gamma(a, b).

## random

Generate a random value from Gamma(a, b).

**Parameters**

-   `a` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The shape.
-   `a` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The rate.
-   `b` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** 

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The random value from  Gamma(a, b).

## sample

Generate an array of k random values from Gamma(a, b).

**Parameters**

-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number of values to generate.
-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** 
-   `a` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The shape.
-   `a` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The rate.
-   `b` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** 

Returns **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** An array of random values from Gamma(a, b).

# choose

Choose k elements from a set of n elements.
See: [Binomial Coefficient](https://en.wikipedia.org/wiki/Binomial_coefficient)

**Parameters**

-   `n` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number of elements to choose from.
-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number of elements to choose.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** A binomial coefficient or NaN if n &lt; k.

# Sample

The sample class is the base for all of our sample based calculations.
These methods can be directly accessed on the class or renerated via
a class instance. You'll need a Sample object for the ttest function.

## constructor

Generate a new Sample object.

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The sample data.

Returns **** 

## correlation

Get the correlation.
[See](https://en.wikipedia.org/wiki/Correlation_and_dependence).

**Parameters**

-   `y` **Sample** A Sample object.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The correlation.

## covariance

Get the covariance.
[See](https://en.wikipedia.org/wiki/Covariance).

**Parameters**

-   `y` **Sample** A Sample object.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The covariance.

## correlation

Get the correlation.
[See](https://en.wikipedia.org/wiki/Correlation_and_dependence).

**Parameters**

-   `x` **Sample** \-A Sample object.
-   `y` **Sample** \-A Sample object.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The correlation.

## covariance

Get the covariance.
[See](https://en.wikipedia.org/wiki/Covariance).

**Parameters**

-   `x` **Sample** \-A Sample object.
-   `y` **Sample** \-A Sample object.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The covariance.

## kurtosis

Get the kurtosis.
[See](https://en.wikipedia.org/wiki/Kurtosis).

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The sample data.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The kurtosis.

## meanDev

Get the sum of the absolute deviations from the mean.
[See](https://en.wikipedia.org/wiki/Deviation_(statistics)#Unsigned_or_absolute_deviation).

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The sample data.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The mean deviation.

## quartiles

Get the .25, .5, .75 quantiles of the data.
The .5 quantile is the median. Together they are the quartiles.
[See](https://en.wikipedia.org/wiki/Quartile).

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The sample data.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The quartiles.

## relativeStdDev

Get the relative standard deviation or coefficient of variation.
[See](https://en.wikipedia.org/wiki/Coefficient_of_variation).

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The sample data.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The relative standard deviation.

## rootMeanSqrd

Get the root mean square.
[See](https://en.wikipedia.org/wiki/Root_mean_square).

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The sample data.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The root mean square.

## skewness

Get the skewness.
[See](https://en.wikipedia.org/wiki/Skewness).

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The sample data.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The skewness.

## sqrdMeanDev

Get the sum of the squared deviations from the mean.
[See](https://en.wikipedia.org/wiki/Squared_deviations_from_the_mean).

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The sample data.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The squared deviations from the mean or NaN.

## stdDev

Get the standard deviation.
[See](https://en.wikipedia.org/wiki/Standard_deviation).

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The sample data.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The standard deviation.

## stdMeanDev

Get the standard deviation of the mean.
[See](https://en.wikipedia.org/wiki/Standard_error#Standard_error_of_the_mean).

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The sample data.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The standard deviation of the mean.

## variance

Get the sample variance.
[See](https://en.wikipedia.org/wiki/Variance#Population_variance_and_sample_variance).

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The sample data.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The sample variance or NaN.

# error

A useful function. Gets used in the Normal distribution cdf.
It's the probability of a random variable with
normal distribution of mean 0 and variance 1/2 falling in the range [-x, x].
See: [Error](https://en.wikipedia.org/wiki/Error_function#)

**Parameters**

-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The numbers to average.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The error value.

# factorial

n! is the product of all positive integers less than or equal to n.
[See](https://en.wikipedia.org/wiki/Factorial)

**Parameters**

-   `n` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** n!, or 1 if n == 0, or Inifinity if n > ~170, or NaN if n &lt; 0.

# gamma

The gamma function is a useful general function. It's (n - 1)!.
[See](https://en.wikipedia.org/wiki/Gamma_function)

**Parameters**

-   `n` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** An approximation of (n-1)! or Infinity if n is a negative integer.

# lngamma

The log-gamma function is a useful general function.
It can handle much larger numbers because it grows much slower compared to the gamma function.
It's (n - 1)! and is used by the gamma function for n > 100.
[See](https://en.wikipedia.org/wiki/Gamma_function#The_log-gamma_function)

**Parameters**

-   `n` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** An approximation of ln(n-1)! or NaN if n &lt; 0.

# lower

The regularized lower incomplete gamma function
[See](https://en.wikipedia.org/wiki/Incomplete_gamma_function#Lower_incomplete_Gamma_function)

**Parameters**

-   `n` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** An approximation of (n-1)! or Infinity if n is a negative integer.

# mean

Averages a list of elements. Uses our internal sum function.
See: [Mean](https://en.wikipedia.org/wiki/Mean)

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The numbers to average.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The mean or NaN if x is the empty set.

# median

Finds the central most value for a list of numbers.
If the list is even, and has no single center, the two
inner-most values are averaged.
Uses our internal selection function.
See: [Median](https://en.wikipedia.org/wiki/Median)

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The numbers.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The median or NaN if x is the empty set.

# mode

Finds the most frequent values of a list of numbers.
It always returns an array.
The result may contain one or more values.
See: [Mode](https://en.wikipedia.org/wiki/Mode)

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The numbers.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The mode or NaN if x is the empty set.

# percentile

Finds the element of a list of numbers at a certain percentile ordered smallest to largest.
Uses the internal select function.
See: [List Ranking](https://en.wikipedia.org/wiki/List_ranking)

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The numbers.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The element at the xth percentile or NaN if x is the empty set.

# quantile

Finds the nth largest element of a list of numbers.
Accepts both a single quantile and an array of quantiles.
See: [List Ranking](https://en.wikipedia.org/wiki/List_ranking)

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The numbers.
-   `quantiles` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** A list of quantiles to compute.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The computed quantiles respective to quantiles provided or NaN if x is the empty set.

# range

Finds the difference between the largest and smallest values.
See: [Range](https://en.wikipedia.org/wiki/Range_(statistics))

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The numbers.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The range or NaN if x is the empty set.

# select

Efficiently finds the kth largest element in a array.
See: [Selection](https://en.wikipedia.org/wiki/Selection_algorithm)

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The numbers.
-   `k` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The element to select.
-   `begin` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)=** The starting index.
-   `end` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)=** The ending index.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The kth largest element or NaN if x is the empty set.

# std

A measure that is used to quantify the amount of variation of a set of data values.
See: [Standard Deviation](https://en.wikipedia.org/wiki/Standard_deviation)

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The numbers.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The standard deviation or 0 if x is the empty set.

# stirling

Efficiently appoximates ln(n!). Similar to the gamma function, but can be faster and more accurate.
See: [Stirling's Approximation](https://en.wikipedia.org/wiki/Stirling%27s_approximation)

**Parameters**

-   `n` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** An approximation on ln(n!).

# sum

Adds a list of elements together.
Uses the [Kahan summation algorithm](https://en.wikipedia.org/wiki/Kahan_summation_algorithm)
to compensate for floating-point error.
See: [Summation](https://en.wikipedia.org/wiki/Summation)

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The numbers.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The sum or 0 if x is the empty set.

# sumNthPowerDev

A really useful function. Takes a set of observations and returns the sum of
the difference of each observation and the mean of the set raised to the nth power.
Can be used to find the absolute value of the difference for functions like MeanDeviation,
or by default, the signed values for functions like Variance and SquaredMeanDeviation.

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The numbers.
-   `n` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number to raise to.
-   `absolute` **[boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)=** Use absolute value of difference. (optional, default `false`)

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The sum of (x-mu)^n or NaN if x is the empty set.

# ttest

Computes Student's T-Test for the provided samples.
If only one sample is provided, a one-sample t-test is computed on the sample mean vs x.
If two samples are provided, a two-sample t-test is computed on the difference between the sample means and x.
See: [Student's T-Test](https://en.wikipedia.org/wiki/Student%27s_t-test)

**Parameters**

-   `sample` **Sample** The sample to test
-   `other` **Sample=** An optional sample to compare with a two sample test.
-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)=** The mean or difference to test. (optional, default `0`)

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The t-statistic or NaN if the sample is the empty set.

# variance

A measure that is used to quantify the amount of variation of a set of data values from their mean value.
See: [Variance](https://en.wikipedia.org/wiki/Variance)

**Parameters**

-   `x` **[Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array).&lt;[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)>** The numbers.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The variance or NaN if x is the empty set.

# zscore

The signed number of deviations an observed value is above the mean.
See: [Standard Score](https://en.wikipedia.org/wiki/Standard_score)

**Parameters**

-   `x` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The number.
-   `mu` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The mean.
-   `std` **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The standard deviation.

Returns **[number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)** The zscore.