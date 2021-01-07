# Deep-Fish

As I'm learning all about deep learning, my method is implementing a paper/architecture at a time. Variational Auto-encoders were one of the math-heavy ones that took me a minute to understand the reasoning behind. Feels great to then learn it and implement it.

Use the notebook called `vae.ipynb`. If you don't want to train the model yourself, there is a function in the bottom of the notebook for loading the saved parameters.

I also made a little script that generates an animation of the fish "swimming" by transitioning between input-values to the encoder. You can see the animation in `vid.mp4`.

## Dataset

Download it here: https://storage.cloud.google.com/quickdraw_dataset/full/numpy_bitmap/fish.npy

And save it in: `data/full_numpy_bitmap_fish.npy`
