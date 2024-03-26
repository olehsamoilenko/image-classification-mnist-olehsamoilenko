## My approach:
1. My network architecture is: 2 convolutional, 2 pooling, 3 fully connected layers. I also want to try less layers to compare results
2. I store loss and accuracy at every epoch, to compare results and choose the best option
4. I also back up my weights on filesystem just in case


## Challenges:
1. Data normalization is important, I had bad results when I skipped it
2. Expected to see more visible overfit after 30 epochs, but it looks not too bad
3. [v.1] Correct train and test data split already brings better results (98.7%)
3. [v.2] More channels for convolutional layer bring yet better results (99.1%)


## TODO (if I have time):
1. ~~Try larger batch size~~
2. Try the simplest possible architecture (1 convolutional layer + fully connected, no pooling), compare results
3. Discover dropout, batch normalization
