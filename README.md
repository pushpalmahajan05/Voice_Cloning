# Voice Cloning Project

## Overview
The Voice Cloning project aims to create a digital version of a speaker's voice using deep learning. With just a few seconds of recorded speech, the system can generate realistic speech in the target voice from any given text. This project integrates various deep learning models to achieve high-quality speech synthesis.

### Workflow
1. Input: A few seconds of recorded speech from a target speaker.
2. Processing: The system encodes the voice, converts text to a mel-spectrogram, and synthesizes audio from the spectrogram.
3. Output: Generated speech in the original speaker’s voice.

### Project Components
- Speaker Encoder: Extracts a unique embedding from a short speech sample.
- Tacotron: Converts input text into a mel-spectrogram representation.
- WaveRNN: Synthesizes a high-quality waveform from the mel-spectrogram.

## Project Timeline & Progress
The project is divided into multiple phases, and several tasks have been completed while the overall project remains in progress.

### 1. Foundation Phase (Completed ✅)
- ✅ Understanding RNN, LSTM, and GRU
- ✅ Exploring Sequence-to-Sequence (Seq2Seq) Models
- ✅ Learning Word Embeddings (word2vec, skip-gram, CBOW)
- ✅ Exploring WaveRNN

### 2. Speaker-to-Vec Representation & PCA Analysis (Completed ✅)
- ✅ Dataset and Data Loader Creation
- ✅ Speaker Encoder Development
- ✅ PCA Plot Visualization

### 3. Text-to-Speech Conversion Phase (Ongoing 🔄)
- 🔄 Tacotron Model Development (In Progress)
- 🔄 Tacotron-WaveRNN Integration (Pending)

### 4. Final Project Implementation (Pending ⏳)
- ⏳ Combining all components into a seamless voice cloning pipeline

## Current Status & Future Work
The project is progressing well, with foundational and speaker representation tasks completed. The next steps involve finalizing Tacotron, integrating it with WaveRNN, and building the end-to-end voice cloning system.

Stay tuned for updates as the project continues to evolve!

