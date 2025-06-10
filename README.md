YouTube-Video-Downloader

A simple Python application for downloading YouTube videos in the highest available resolution using the pytube library. Users can input a YouTube URL via the command line and select a destination folder using a tkinter file dialog. The tool fetches the best MP4 stream and downloads it directly to the chosen location, making video saving quick and convenient. Ideal for personal use and beginner Python learners exploring GUI integration and video processing.

Features

- Download videos from YouTube in MP4 format.
- Automatically selects the highest available resolution.
- GUI folder selection using `tkinter`.
- Simple CLI input for YouTube video URL.

Requirements

- Python 3.x
- `pytube`
- `tkinter` (usually comes pre-installed with Python)


How to Use

1. Run the script:

python youtube_downloader.py

2. Enter a valid YouTube video URL when prompted.

3. A folder selection dialog will appear — choose the directory to save the video.

4. The video will be downloaded to the selected location.




Project Structure


youtube_downloader.py   # Main script
README.md               # Project documentation



License
This project is for educational and personal use. Feel free to modify and improve it.




