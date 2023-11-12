# JukeBoxAI-TWTA
Fixed code for training (fine-tuning) and sampling an AI generative model for audio with OpenAIs jukebox with Google Colab

To ensure that these notebooks run properly make sure that you have selected a GPU and are running the notebook with the High Ram setting enabled.

instructions:

To train a new model you must first create a folder in your Google Drive containing the WAV files of all the audio you wish to train on.

Follow the instructions in the FineTuning notebook to begin training. I recommend initially training to around 8k steps before sampling to check if the model is training correctly.

Once the model is sufficently trained use the Sampling notebook to begin generating audio with your model.
