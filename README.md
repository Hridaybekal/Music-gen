# Music-gen
A GenAI model to generate Music.
Project Overview
Music Generation Using RNN is a generative AI project focused on creating novel music compositions automatically. By leveraging Recurrent Neural Networks (RNNs), specifically Long Short-Term Memory (LSTM) or Gated Recurrent Unit (GRU) architectures, this project learns musical styles, structures, and elements from large datasets of music files. The trained model generates new music pieces that reflect the learned patterns and styles, producing coherent sequences of musical notes.

Features
Data Processing: MIDI files are processed and encoded into sequences that represent musical notes and their characteristics.
Model Architecture: RNNs, particularly LSTMs or GRUs, are used to model and predict sequences of notes based on learned patterns.
Music Generation: The model generates new sequences of notes, which are then converted back into MIDI format for playback.
Frontend Interface: A web-based interface allows users to interact with the model, input parameters, and listen to the generated music.
Technology Stack
Python: Used for data processing, model training, and generation.
pretty_midi: A Python library for handling MIDI data, converting between MIDI files and note sequences.
HTML/CSS: Used to create a user-friendly frontend interface.
JavaScript: Adds interactivity to the web interface, allowing users to customize the music generation process.

Dependencies
Python 3.7+
pretty_midi
NumPy
