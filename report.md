## My approach:
1. My network architecture is: 2 convolutional, 2 pooling, 3 fully connected layers. I also want to try less layers to compare results
2. I store weights, loss and accuracy at every epoch, to compare results and choose the best option, e.g.:
    - at epoch 8 there is the smallest loss and good validation accuracy
    - highest validation accuracy is at epoch 20
4. I also back up my weights on filesystem just in case


## Challenges:
1. Data normalization is important, I had bad results when I skipped it
2. Expected to see more visible overfit after 30 epochs, but it looks not too bad


## TODO (if I have time):
1. Try larger batch size
2. Try the simplest possible architecture (1 convolutional layer + fully connected, no pooling), compare results
