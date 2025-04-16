# Flow and Diffusion Models
### Sampling and Generation Relevance:
For any object in general, there is no single correct representation, rather we have a set of all possible representations for a specific object/entity i.e. our data. This data distribution can also be looked at as a probability distribution, which is often reperesented by p_data which contains random variables (x_1,.....,x_n)
We make an assumption that, upon sampling a random variable x~p_data, we generate a image of the desired object
Hence we can summarise our generation task as the following:
Converting a distribution p_init into samples from p_data
## Flow Models
## Diffusion Models
### SDE(Stochastic Diffrential Equations):
X_t is a random variable for every 0 ≤ t ≤ 1
X : [0,1] → ℝ^d,  t ↦ X_t is a random trajectory for every draw of X
Note: Simulating this equation multiple times will lead to different trajectories as SDE's are designed to be random
These equations are constructed via Brownian Motion(A stochastic trajectory where X_0=0 and trajectory is continuous, increments have a Gaussian distribution with variance increasing linearly in time)
