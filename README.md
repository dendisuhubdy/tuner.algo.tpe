# Algorithms for Hyper-Parameter Optimization

By James Bergstra, Remi Bardenet, Yoshua Bengio, Balazs Kegl

Several recent advances to the state of the art in image classification benchmarks
have come from better configurations of existing techniques rather than novel approaches
to feature learning. Traditionally, hyper-parameter optimization has been
the job of humans because they can be very efficient in regimes where only a few
trials are possible. Presently, computer clusters and GPU processors make it possible
to run more trials and we show that algorithmic approaches can find better
results. We present hyper-parameter optimization results on tasks of training neural
networks and deep belief networks (DBNs). We optimize hyper-parameters
using random search and two new greedy sequential methods based on the expected
improvement criterion. Random search has been shown to be sufficiently
efficient for learning neural networks for several datasets, but we show it is unreliable
for training DBNs. The sequential algorithms are applied to the most difficult
DBN learning problems from [1] and find significantly better results than the best
previously reported. This work contributes novel techniques for making response
surface models P(y|x) in which many elements of hyper-parameter assignment
(x) are known to be irrelevant given particular values of other elements.


Implementation: Copyright by the Dendi Suhubdy, 2018
