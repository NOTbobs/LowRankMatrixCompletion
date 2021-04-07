# LowRankMatrixCompletion
Attempt at implementing Low Rank Matrix Completion using NN?

### To use:

Clone/Download the notebook and run. 

Notes: 
- Training is slow since training relies on standard SGD. Did not bother using VMAP to do at least batching. 
- Although the program is written in Jax/Numpy, you can probably port this over into Pytorch, I am unsure how you would do this with Keras alone
