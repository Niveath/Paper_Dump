# Residual Neural Networks
This paper solves the problem of vanishing gradients faced while building deep neural networks. 

The paper introduces the concept of skip connections, wherein the output of a particular layer is summed with the output of a layer before it. 

These skip connections present a new path for the gradient to flow and hence prevents vanishing gradients. They also make sure that the deeper layers of a network work atleast as well as the layers before it.