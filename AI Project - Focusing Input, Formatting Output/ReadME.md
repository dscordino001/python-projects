Using this input training data: (see also csv attached):

1. A system is looking for pattern in a 1.5 second sample (n.b., beware of scale!) from both channels. Assume input array is 6x1 to a 2 layer neural network, each layer of 10 nodes, that results in these possible choices: Channel 1 is trending up but Channel 2 is trending down in the next sample, Channel 1 and 2 are trending up in the next sample, Channel 2 is trending up but Channel 1 is trending down in the next sample,, and both are trending down in the next sample. (Note also: this is what QUANT software does to make money in the market.) The goal is that given any 1.5 second sample in the future of both channels, I can predict the next sample to trade on that prediction.
2. Describe and show math functions (with an example from data) that could be used to fit the data into the input array.
3. Describe and show math functions (with an example from data) that would take the output from the neural network and fit it to the output results. Define the output array too.