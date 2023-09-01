# Cog WhisperX with Diarization

Cog implementation of [WhisperX](https://github.com/m-bain/whisperX), a library that adds batch processing on top of whisper (and also faster-whisper), leading to very fast audio transcription. This implementation also enables diarization as parameter.

To start, first you need to install [cog](https://github.com/replicate/cog#prerequisites). Refer to [Replicate documentation](https://replicate.com/docs/guides/push-a-model) for how to push your model to Replicate.

You also need to find your [HuggingFace token](https://huggingface.co/settings/tokens) and replace the placeholder under `setup` function in [predict.py](https://github.com/Techming/cog-whisperx-diarization/blob/main/predict.py) file.
