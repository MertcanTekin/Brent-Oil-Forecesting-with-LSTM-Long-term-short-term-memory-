# Brent-Oil-Forecesting-with-LSTM-Long-term-short-term-memory-

What is LSTM?


Long Short-Term Memory (LSTM) is a type of recurrent neural network (RNN) architecture designed to overcome 
some of the limitations of traditional RNNs in capturing and learning long-term dependencies in sequential data.

LSTMs address the vanishing gradient problem by introducing a more complex memory cell structure with three gates: input gate, forget gate, and output gate. 
These gates regulate the flow of information into and out of the memory cell, allowing the network to selectively remember or forget information. 
The architecture includes a memory cell that can maintain information over long sequences, making LSTMs well-suited for tasks involving sequential data, such as speech recognition, 
natural language processing, and time series prediction.

Cell State (Memory Cell): This is the internal memory that can store information over long sequences.
Input Gate: Controls the flow of information into the cell state. It decides which information to store in the cell state.
Forget Gate: Determines what information from the cell state should be discarded or forgotten.
Output Gate: Decides what the next hidden state should be based on the cell state and input.



