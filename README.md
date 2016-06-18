# stacked_denoising_autoencoders

Trying the reproduce the results from (http://jmlr.org/papers/volume11/vincent10a/vincent10a.pdf)
    
    Stacked Denoising Autoencoders: Learning Useful Representations in a Deep Network with a Local Denoising Criterion
*Requirements*:
- lasagne
- nolearn

The big issue for me is that I am not able to reproduce the filters the authors obtain: 
- They get blob/edge detectors
- I get some random crap

Turns out that sample size is the issue: Going from 50000 to 500000 results in the desired filters.

See also [this thread](https://www.reddit.com/r/MachineLearning/comments/3z7gcf/stacked_denoising_autoencoders_cannot_reproduce/)

