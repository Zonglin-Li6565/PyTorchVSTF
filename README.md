# PyTorchVSTF
Compare PyTorch and Tensorflow performance on MNIST

# Run
 - `pytorch.py` for running pytorch 10000 iteration with batch size 64
 - `tf.py` for running tensorflow 10000 iterations with batch size 64
# Result
Tensorflow is slightly faster than PyTorch
 - Tensorflow: 34.17089223861694 seconds
 - PyTorch: 44.29865097999573 seconds
   - CPU usage on PyTorch is much higher than Tensorflow, possibly due to the run time autograd
