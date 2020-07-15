# Novel Music Generation with Recurrent Neural Networks

Neural Networks allow us to learn the different intricacies and details that underly a certain processes. From basic representations of a deep network to
convolutional networks to recurrent networks, we are able to learn features that define a certain object or process. Significant research has been done to generate music
using recurrent networks and this project explores possibilities and experiments regarding such discoveries.

## Motivation

This project draws heavy inspiration from this [article](https://medium.com/@alexissa122/generating-original-classical-music-with-an-lstm-neural-network-and-attention-abf03f9ddcb4)
and [this](https://towardsdatascience.com/how-to-generate-music-using-a-lstm-neural-network-in-keras-68786834d4c5). Some of the code represented here are built on top of the
code found in the previously mentioned articles. However, instead of only training notes, chords, and rest-durations, I will also train durations and use them as learned offsets
when writing to midi files. This allows for the network to also understand the style of pacing and note durations that can define a genre of music. The project will also focus on
Long Short-Term Memory (LSTM) architecture of Recurrent Neural Networks (RNN) -- more information on this can be found in Andrej Karpathy's very informational and simple 
[blog](http://karpathy.github.io/2015/05/21/rnn-effectiveness/). Some models will contain Bidirectional architectures as well as Attention architectures as well.
