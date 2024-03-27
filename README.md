# speech_to_text
In this tutorial, we will walk through the process of converting audio files to text using **Whisper**, an open-source tool developed by OpenAI. Whisper utilizes advanced machine learning models to transcribe audio files accurately. 

## Step 1: Installation

First, we need to install Whisper and its dependencies. Execute the following command in your terminal or command prompt:

```bash
!pip install git+https://github.com/openai/whisper.git
```

This command installs Whisper directly from its GitHub repository.

## Step 2: Install FFmpeg

FFmpeg is a multimedia framework that can decode, encode, transcode, mux, demux, stream, filter, and play almost anything that humans and machines have created. We need FFmpeg to handle audio files effectively. Install FFmpeg by running the following command:

```bash
!sudo apt update && sudo apt install ffmpeg
```

This command updates the package list and installs FFmpeg on your system.

## Step 3: Transcribe Audio

Now that we have Whisper installed and FFmpeg set up, we can transcribe our audio file. Here's the command to transcribe an audio file named `Recording.m4a` using the large model provided by Whisper:

```bash
!whisper "/path/to/Recording.m4a" --model large
```

Replace `"/path/to/Recording.m4a"` with the actual path to your audio file. The `--model large` flag specifies the model size to be used for transcription. You can choose different model sizes based on your requirements.

## Conclusion

Congratulations! You have successfully transcribed an audio file into text using Whisper. Feel free to explore more features and options provided by Whisper for advanced audio processing tasks.

For more information and detailed documentation, visit the [Whisper GitHub repository](https://github.com/openai/whisper). Happy transcribing! 🎶📝
