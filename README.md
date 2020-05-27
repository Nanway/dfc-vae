# dfc-vae
I turned my friends into dogs and made computer generated images of them with this deep feature consistent variational autoencoder. In the repo I've attached some images of dog people as well as computer generated images and averages of faces. 

I trained the model in PyTorch and reimplemented this paper: https://arxiv.org/abs/1610.00291

My training images came from:
- Dogs with parts dataset: https://people.eecs.berkeley.edu/~kanazawa/
- FairFace dataset: https://arxiv.org/abs/1908.04913
- My own images of dogs and friends. I made sure to run them through the same dataset as the above one. 

The results can be seen in the Jupyter Notebook. Overall it was a fun project and the results were okay-ish, it was enough to dip my toes in this in preparation for my thesis. There were heaps of repos online that helped me with implementation that I'd like to give some credit to:
- https://github.com/svenrdz/DFC-VAE
- https://github.com/svenrdz/DFC-VAE/blob/master/main.py
