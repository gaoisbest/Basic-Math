# Basic-Math
- Calculus
- Probability statistics
- Linear algebra
- Convex theory

# Calculus
- Differential
    - `f′(x_0) = (f(x)-f(x_0)) / (x−x_0) ==> f(x)≈f(x_0)+f′(x_0)(x−x_0)`
    - In geometry it is **slope**
    - **Taylor series** is extension of derivative that **approximate the function with polynomial instead of linear**
    - **Newton's method** to solve `f(x) = 0`
    ```
    Setting f(x)=0 ==> 0=f(x_0)+f′(x_0)(x−x_0) ==> f′(x_0)(x−x_0)=−f(x_0) ==> x−x_0=−f(x_0)/f′(x_0) ==> x=x_0−f(x_0)/f′(x_0)
    ```
- Integral
    - In geometry it is **area**

- Newton-Leibniz formula
```
 ∫ a_b f(x)dx = F(b)−F(a)
```

# Probability statistics
- Discrete and Continuous variable
    - The probability of specific value is **zero**. For example, the weather forecast says that it will rain afternoon, the probability that raining at 13:05 is zero
- [Parameter estimation](https://medium.com/@amatsukawa/maximum-likelihood-maximum-a-priori-and-bayesian-parameter-estimation-d99a23a0519f)
    - **Maximum likelihood**
        - Principle: maximizes the likelihood of the observed data
        - `θ^* = argmax p(D; θ)`
        - Solution: let partial derivative of `ln` of likelihood function to the parameter = 0
    - **Maximum a posteriori**
        - Incorporate **prior distribution** of the parameter `p(θ)`
        - Posteriori: `p(θ|D)`
        - **Bayes rule**: `p(θ|D) = (p(D|θ) * p(θ)) / p(D)`, i.e., **posterior = likelihood * prior / evidence**
        - `θ^* = argmax p(θ|D) = argmax (p(D|θ) * p(θ)) / p(D) = argmax p(D|θ) * p(θ)`
    - **Bayesian estimation**
        - Principle: take into account all possible posterior values of `θ`, fully calculates (or approximates) the posterior distribution p(θ|D)

# Linear algebra
- **Basis** is a group of vectors in linear space, any vectors can be represented by the linear combination of these vectors

# Convex theory
- Lagrange duality
    - Dual function is convex function
    - 
