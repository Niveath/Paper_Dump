#Relational Neural Network
	The paper addresses the problem of answering relational question in a visual question answering model. It uses a "relational network" to achieve this goal.
	The images are first passed through a CNN based architecture and now each pair of pixels are passed through a neural network, one pair at a time. 
	Passing the pairs one-by-one, makes these neural networks highly data-efficient and also prevents over fitting. 