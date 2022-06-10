# Caption

A caption is an option on caps and floors. Since we can view cap as a call option and floor as a put option, caption can be modeled by compounding option techniques.

There are four basic types: call option on cap, put option on cap, call option on floor, and put option on floor. Here we only explain how to value European or American call option on cap in details. Other three cases can be done in a similar way.

Let’s consider how to value a European call option on cap. The payoff of this option at time T is defined as follows:
  max (cap(f(T)-R, 0)
  
The American caption can be valued by the binomial tree techniques. The tree can be built up to T. At each node the tree, the corresponding cap can be valued by closed form solution derived the above. Then the caption can be valued in the same way as the ordinary American option.

References:

https://finpricing.com/lib/EqBarrier.html

https://zenodo.org/record/6561073/files/Caption.pdf

https://zenodo.org/record/6561073#.YpDwZagpDq4
