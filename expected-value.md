# Expected Value

In probability theory, the expected value of a random variable is a key aspect of its probability distribution.  The expected value of a probability distribution is also known as the **expectation**, **mathematical expectation**, **mean**, **average**, or **first moment**.

## Definition

### Finite case

let x is a random variable with finite possible values $$x_i $$:

![](.gitbook/assets/image%20%281%29.png)

### Absolutely continuous case

 If![X](https://wikimedia.org/api/rest_v1/media/math/render/svg/68baa052181f707c662844a465bfeeb135e82bab) is a random variable whose cumulative distribution function admits a density![f\(x\)](https://wikimedia.org/api/rest_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074), then the expected value is defined as the following Lebesgue integral, if the integral exists:

![](.gitbook/assets/image%20%282%29.png)



## Basic properties

###  **Linearity of expectation:**

 for any random variables ![X](https://wikimedia.org/api/rest_v1/media/math/render/svg/68baa052181f707c662844a465bfeeb135e82bab) and ![Y](https://wikimedia.org/api/rest_v1/media/math/render/svg/961d67d6b454b4df2301ac571808a3538b3a6d3f), and a constant ![a](https://wikimedia.org/api/rest_v1/media/math/render/svg/ffd2487510aa438433a2579450ab2b3d557e5edc)**:**

![](.gitbook/assets/image%20%283%29.png)

###  **Non-multiplicativity:**

In general, the expected value is not multiplicative, i.e. ![{\displaystyle \operatorname {E} \[XY\]}](https://wikimedia.org/api/rest_v1/media/math/render/svg/612af0bbf256874e0b0551305574be507f9ff805) is not necessarily equal to ![{\displaystyle \operatorname {E} \[X\]\cdot \operatorname {E} \[Y\]}](https://wikimedia.org/api/rest_v1/media/math/render/svg/c52e5f76c5aad37aeeaf32d355681263e92aad24). If ![X](https://wikimedia.org/api/rest_v1/media/math/render/svg/68baa052181f707c662844a465bfeeb135e82bab) and ![Y](https://wikimedia.org/api/rest_v1/media/math/render/svg/961d67d6b454b4df2301ac571808a3538b3a6d3f) are independent, then one can show that ![{\displaystyle \operatorname {E} \[XY\]=\operatorname {E} \[X\]\operatorname {E} \[Y\]}](https://wikimedia.org/api/rest_v1/media/math/render/svg/5cfc97e307911d3230962dd68be6a5c3dcaed71a).

