# A law of large numbers

Neural networks are enormously valuable tools in tasks related to classification and automation. As
a result or their practical strength, a significant interest in the development of our understanding of
neural networks from a mathematical standpoint has evolved. In contribution to this understanding
Sirignano and Spiliopoulos [1] analyze the asymptotic behaviour of a single-layer neural network,
and prove that under suitable scaling the empirical distribution of its parameters converges to the
solution of a nonlinear partial differential equation. Their result can be seen as a law of large numbers
for the empirical distribution of the parameters of a single-layer neural network. The code in this sample aims to provide empirical evidence to support their theory.

The final report for this project can be found: 
https://drive.google.com/file/d/1BHAUK4oiP9n_4ObmjTaZ9ChM2BEuz6we/view?usp=sharing

The MNIST_Experiments file can be used to obtain the results pertaining to a neural network trained on MNIST data, while the Simulated_Dataset file pertains to a neural network trained on simulated data.

References:

[1] J. Sirignano and K. Spiliopoulos. Mean field analysis of neural networks: A law of large numbers,
05 2018. URL https://arxiv.org/pdf/1805.01053.pdf.
