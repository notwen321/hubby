# Hubby - YouTube Downloader

A web application for downloading YouTube videos and managing downloads with a user-friendly interface.

## Project Structure

The project is organized into two main components:

### Backend
- Python-based server using Flask
- Handles video downloading and processing
- Core functionality in `simple_yt_downloader.py` and `browser_downloader.py`

### Frontend
- HTML/CSS interface
- Templates for user interaction
- Static assets for styling and client-side functionality

## Setup Instructions

### Prerequisites
- Python 3.6+
- pip (Python package manager)

### Installation

1. Clone the repository
   ```
   git clone https://github.com/notwen321/hubby.git
   cd hubby
   ```

2. Install backend dependencies
   ```
   cd Backend
   pip install -r requirements.txt
   ```

3. Run the application
   ```
   python run.py
   ```
   
   Alternatively, you can use the batch file:
   ```
   run_web_downloader.bat
   ```

4. Access the web interface by opening a browser and navigating to:
   ```
   http://localhost:5000
   ```

## Features

- Download YouTube videos in various formats and quality options
- Simple, intuitive web interface
- Support for downloading complete playlists
- Browser integration for easy downloads
