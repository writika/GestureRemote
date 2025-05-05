# GestureRemote
Train a model to develop a smart TV feature that recognizes five user gestures via webcam: thumbs up (increase volume), thumbs down (decrease volume), left swipe (rewind 10 seconds), right swipe (fast forward 10 seconds), and stop (pause). 

I experimented with extracting feature vectors from video frames with both CNN-RNN and 3D convolutions for detailed analysis. Implemented transfer learning in CNN layers and optimize RNNs with GRU for efficient video processing and classification. I used custom data generator and made it memory efficient. Used kera's fit.generator() method to train the models with video batches and ensured that generator yielded data batches efficiently. I used chroma db as vector store and semantic search pipeline to retrieve relevant embeddings. 



