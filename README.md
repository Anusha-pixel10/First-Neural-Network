Tested it twice! Once with 784 -> 128 -> 10 neurons with 128 in the hidden layer with 500 iterations, while in the second time around, it was 784 -> 10 -> 10 with 1000 iterations.
The first one had an accuracy of roughly 88%, while the second amounted to 91%.
Emphasizes training time over complexity for smaller networks. Learned quite a bit
Encountered way too many errors. 
  - Broke all my labels to 0 during normalization and type casting to integers; ended up with a 0% accuracy.
  - Exploded my softmax in the beginning.
  - Had 11% accuracy on the first test run.
Managed to work around it though :D
