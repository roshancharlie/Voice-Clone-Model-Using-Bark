# Voice Cloning Model Using Bark , Pytorch and Python

# Description
The code implements a voice cloning system using the Bark library. It includes functionality for training a custom tokenizer model, extracting semantic vectors from audio using the HuBERT model, encoding audio using the Bark model, and synthesizing speech based on text prompts using the trained models. The system allows users to generate custom voices by training the tokenizer, encoding audio, and performing text-to-speech synthesis.

# Major Libraries Used Here
The major libraries used as dependencies in the provided code are:
1. Bark: A voice cloning library used for training and synthesizing custom voices.
2. Hugging Face Transformers: A popular library for natural language processing (NLP) tasks, used here for generating text prompts.
3. Torchaudio: A PyTorch-based library for audio processing, used for loading and manipulating audio files.
4. Torch: The deep learning framework used for training and running the models.
5. Numpy: A library for numerical computing, used for array operations and data manipulation.
6. fairseq: A sequence modeling toolkit used for loading and using the HuBERT model.
7. PyTorch: The deep learning framework used for training and running the models.
8. scipy: A library for scientific and technical computing, used for saving the synthesized audio as a WAV file.

# How to Use The Model
To use the model, follow these steps:
1. Start by ensuring you have an audio file in the .wav format. Specify the file path of the audio in the `audio_filepath` variable at the beginning of the "Audio Encoding and Saving Prompts" section.
2. Next, define the text you want to synthesize in the `text_prompt` variable. This text will be spoken in the cloned voice.
3. Run all the code cells from start to finish. Make sure you have all the necessary libraries installed, and that the code executes without any errors.
4. Once the code execution is complete, you will have an audio file synthesized in the cloned voice. The audio will be saved as "audio.mp4" in the same directory.
5. You can play the synthesized audio file using any media player or audio processing software to listen to the cloned voice.

# How to Evaluate The Model
After the code has executed and the audio file has been generated, you can play the audio file using a media player or audio processing software. Listen to the audio and assess its quality, similarity to the desired voice, and overall performance.

