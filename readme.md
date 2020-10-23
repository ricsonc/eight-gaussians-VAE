If you've been keeping up with the generative models literature lately, you'll probably have seen quite a few figures showing how well {X} model can fit the "8 gaussians" toy dataset. But I've never seen anyone try to fit a simple VAE to them, so I figured I'd try it out myself.

There doesn't seem to be a single commonly agreed upon spec for how far the gaussians should be (equiv. what their variance is), so I just chose something which seemed to work. Then I more or less copied in some VAE tutorial code and hacked everything together until it worked. The resulting plot shows the dataset points in red and the sampled points in blue.
