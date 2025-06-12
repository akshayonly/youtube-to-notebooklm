# YouTube Transcript Extractors for LLMs

Automatically extract, clean, and compile transcripts from **YouTube playlists** into a single `.txt` file — ideal for tools like **NotebookLM**, GPT-based summarizers, or your own LLM pipelines.

---

## Features

- Process entire YouTube playlists, not just individual videos
- Fetch transcripts using YouTube's auto or manual captions
- Clean noisy annotations like `[Music]`, `[Laughter]`, etc.
- Output a single `.txt` file organized by video title
- Great for AI ingestion: NotebookLM, vector stores, or summarization

---

## Installation

```bash
pip install youtube-transcript-api yt-dlp pandas
```
---

## Clone the repository
```bash
git clone https://github.com/akshayonly/youtube-to-notebooklm.git
cd youtube-to-notebooklm
```
---
