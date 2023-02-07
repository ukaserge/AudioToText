Example Notebook

This example transcribes the audio of a video file (low-res so it can be uploaded fast) to its source language (Spanish) in TXT and VTT formats and then translates the generated transcripts to English using DeepL API.

## Input

**task**: `Transcribe`

**audio_file**: `Whisper-Example.3gp` ([Original YouTube video](https://www.youtube.com/watch?v=JuMEmF-2FsA))

**language:** `Auto-Detect` (Spanish)

**use_model**: `large-v2`

## Output

**output_formats**: `txt,vtt`

audio_transcription/Whisper-Example.txt
audio_transcription/Whisper-Example.vtt

**deepl_target_language**: `English (British)`

audio_transcription/Whisper-Example_English (British).txt
audio_transcription/Whisper-Example_English (British).vtt