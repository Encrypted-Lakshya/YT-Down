# YouTube Downloader

A modern web application for downloading YouTube videos, audio, and playlists.

## Features

- Download individual videos in multiple quality options
- Download audio tracks in various bitrates
- Download entire playlists (video or audio)
- Beautiful, responsive UI with animated background elements
- Custom download path support

## Setup Instructions

### Backend Setup

1. Navigate to the backend directory:
```bash
cd backend
```

2. Install Python dependencies:
```bash
pip install -r requirements.txt
```

3. Start the FastAPI server:
```bash
python api.py
```

The backend API will run on `http://localhost:8000`

### Frontend Setup

1. Install Node.js dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

The frontend will run on `http://localhost:5173`

## Usage

1. Select the type of content you want to download (Video, Audio, Playlist Videos, or Playlist Audio)
2. Enter the YouTube URL
3. Select your desired quality
4. Optionally specify a custom download path
5. Click the download button

Downloads will be saved to your Downloads folder by default.

## Tech Stack

- **Frontend**: React, TypeScript, Tailwind CSS, Vite
- **Backend**: Python, FastAPI, pytubefix
- **Icons**: Lucide React
