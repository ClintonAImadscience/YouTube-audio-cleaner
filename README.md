# YouTube-audio-cleaner
A Google Colab app that downloads and cleans YouTube audio for AI voice cloning workflows.

# 🎙️ YouTube Audio Cleaner for Voice Cloning

This Google Colab app helps red teamers, AI researchers, and developers convert YouTube videos into **clean, high-quality `.wav` audio files** for use in **voice cloning pipelines**. It automates the entire preprocessing workflow—from download to enhancement to export.

---

## 🚀 Features

- ✅ Download best-quality audio from YouTube using `yt-dlp`
- ✅ Automatically selects best resample rate (16kHz–96kHz) based on input quality
- ✅ Trims silence and normalizes volume with `ffmpeg`
- ✅ Outputs metadata-rich filenames
- ✅ Auto-uploads cleaned `.wav` files to your Google Drive
- ✅ Skips broken links and long-running jobs with timeouts
- ✅ Beginner-friendly comments and structure for learning

---

## 🔗 Run in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/YouTube-Audio-Cleaner.ipynb)

---

## 📂 Output Example

After processing, you’ll get `.wav` files like:

