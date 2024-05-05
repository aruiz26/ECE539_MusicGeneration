# ECE539-Project
### Long Short-Term Memory Network for Music Generation
### Abstract
We propose a neural network that can be trained on MIDI data to generate new segments of music. The program parses MIDI files for note value and duration and tokenizes them. This data is used to train a long short-term memory (LSTM) model to predict the next set of notes based on a given input sequence. The model can then output the generated predictions which can be listened to as a MIDI file.
