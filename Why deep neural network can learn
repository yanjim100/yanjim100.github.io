
A question which came up from time to time was why deep learning can learn.

Deep learning is essentially using linear approxmiation to approximate any complex functions. 
If you use ReLu as activation function, essentially Relu is a linear function (with a certain application 
input value boundary, i.e., x > 0).  It's nonlinear only because the linearity breaks at x=0.

Now if you imagine a deep network with many layers of linear functions and Relu activation function. the net
result is still linear function if you look at a very small region.  If any small neighborhood region is small enough, 
the net effect of the deep neural network is still only a linear function.  the behavior is linear, i.e., if the input change
a tiny bit, the output correspondingly changes a tiny bit in a linear way.  This is called piecewise linear

So, deep neural network is essentially using piecewise linear functions to approximate very very complex target functions.

As long as you divide the input neighborhood small enough, you can use a linear function to approximate it. 
Of course, you will need many, many different linear functions to approximate a complex target function, with each
linear function operating within its own small neighborhood.

