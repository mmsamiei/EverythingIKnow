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

### Law of the unconscious statistician:

The expected value of a measurable function of![X](https://wikimedia.org/api/rest_v1/media/math/render/svg/68baa052181f707c662844a465bfeeb135e82bab), ![g\(X\)](https://wikimedia.org/api/rest_v1/media/math/render/svg/b1fa9025e0f6127a028b801736123f552f7286fe), ![X](https://wikimedia.org/api/rest_v1/media/math/render/svg/68baa052181f707c662844a465bfeeb135e82bab) has a probability density function ![f\(x\)](https://wikimedia.org/api/rest_v1/media/math/render/svg/202945cce41ecebb6f643f31d119c514bec7a074), is given by the inner product of ![f](https://wikimedia.org/api/rest_v1/media/math/render/svg/132e57acb643253e7810ee9702d9581f159a1c61) and ![g](https://wikimedia.org/api/rest_v1/media/math/render/svg/d3556280e66fe2c0d0140df20935a6f057381d77):

![](https://wikimedia.org/api/rest_v1/media/math/render/svg/a417b7efdd5329bcd40b2efd4b8ed5bd3b031e52)



