# ReelNotes 🎬📝

A modern desktop application that automatically transcribes audio from video content into clean, readable notes. Built with Tauri for performance and security.

## ✨ Features

- **Multi-Platform Support**: Download audio from YouTube, Facebook, and Instagram
- **AI-Powered Transcription**: Whisper speech-to-text for accurate transcriptions  
- **Batch Processing**: Handle multiple URLs simultaneously
- **Clean Output**: Timestamp-free, readable text format
- **Native Performance**: Rust backend ensures fast and efficient processing
- **Simple Interface**: Paste URLs and get transcripts with one click

## 🛠️ Tech Stack

**Frontend**: Vanilla TypeScript, HTML, CSS  
**Backend**: Rust, Tauri Framework  
**AI/Processing**: Python, Whisper, yt-dlp  
**Package Manager**: npm

## 🚀 Getting Started

### Prerequisites

- **Rust** 1.91.0+
- **Node.js** 22.14.0+ 
- **Python** 3.12.0+
- **System dependencies** for yt-dlp and Whisper
   
## Project Structure
```
reelnotes/
├── src/                 # Frontend (TypeScript, HTML, CSS)
├── src-tauri/          # Backend (Rust)
│   ├── src/main.rs     # Application entry point
│   └── Cargo.toml      # Rust dependencies
└── package.json        # Frontend dependencies
```

## Contributing
This is a personal project focused on learning Tauri and Rust while creating a practical transcription tool.
