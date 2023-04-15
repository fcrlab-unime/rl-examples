# CartPole

This environment corresponds to the version of the cart-pole problem described by Barto, Sutton, and Anderson in “[*Neuronlike Adaptive Elements That Can Solve Difficult Learning Control Problem*](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6313077&isnumber=6313056)”. 

> A. G. Barto, R. S. Sutton and C. W. Anderson, "Neuronlike adaptive elements that can solve difficult learning control problems," in IEEE Transactions on Systems, Man, and Cybernetics, vol. SMC-13, no. 5, pp. 834-846, Sept.-Oct. 1983, doi: 10.1109/TSMC.1983.6313077.
> Abstract: It is shown how a system consisting of two neuronlike adaptive elements can solve a difficult learning control problem. The task is to balance a pole that is hinged to a movable cart by applying forces to the cart's base. It is argued that the learning problems faced by adaptive elements that are components of adaptive networks are at least as difficult as this version of the pole-balancing problem. The learning system consists of a single associative search element (ASE) and a single adaptive critic element (ACE). In the course of learning to balance the pole, the ASE constructs associations between input and output by searching under the influence of reinforcement feedback, and the ACE constructs a more informative evaluation function than reinforcement feedback alone can provide. The differences between this approach and other attempts to solve problems using neurolike elements are discussed, as is the relation of this work to classical and instrumental conditioning in animal learning studies and its possible implications for research in the neurosciences.


## Environment Description
A pole is attached by an un-actuated joint to a cart, which moves along a frictionless track. The pendulum is placed upright on the cart and the goal is to balance the pole by applying forces in the left and right direction on the cart.
<p align="center">
    <img 
         src="https://images.ctfassets.net/xjan103pcp94/4hLHnMXJN2EwwAXq2yYx9v/41b16121290d6c46b6b85492a572a4cf/cartPoleRemade.png"
         width="60%" 
         height="60%" 
    />
</p>

## How to get it
This environment is part of the Classic Control environments. The unique dependencies for this set of environments can be installed via:
```bash
pip install gymnasium[classic-control]
```

## Examples
- Zhiqing Xiao resolved the cart pole problem by applying a fixed deterministic policy.