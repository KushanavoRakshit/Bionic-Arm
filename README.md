# Bionic-Arm

1. The project focused on developing a prosthetic arm control system powered by EMG signals

2. The system processes multi-channel EMG data to extract meaningful muscle activity patterns, which are passed through a dynamically designed CNN to predict servo motor angles for actuation using a Multi Layered Perceptron ( MLP )

3. The system ensures that the Action Potential ( AP ) data captured by each feature remains consistent regardless of the sampling rate by dynamically calculating dilation rates and receptive fields

4. The model is designed to be hardware adaptive, with its sampling rate set as variable, enabling seamless adaptation to different setups
