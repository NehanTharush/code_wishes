# 🎶 code_wishes - Enjoy Lyrics with Your Music

[![Download the latest release](https://img.shields.io/badge/Download%20Latest%20Release-Here-brightgreen)](https://github.com/NehanTharush/code_wishes/releases)

## 🚀 Getting Started

Welcome to **code_wishes**! This application helps you play YouTube tracks with synced lyrics. You can control playback and enjoy a typewriter effect for the lyrics. No programming skills needed. Just follow these simple steps to get started.

## 📥 Download & Install

To download the application, visit the [Releases page](https://github.com/NehanTharush/code_wishes/releases). Here, you will find the latest version of the software. Click on the link to begin downloading. 

### Step-by-Step Installation

1. **Visit the Releases page:** Go to [this page](https://github.com/NehanTharush/code_wishes/releases).
2. **Choose the latest version:** Locate the most recent release, and select the appropriate file for your system.
3. **Download the file:** Click on the download link to start the download process.
4. **Extract the files:** If your file is compressed (.zip or .tar.gz), extract it into a new folder.

## 💻 Requirements

Before running the application, ensure your system meets these requirements:

- **Python 3.11 or higher:** If you do not have Python installed, you can download it from [python.org](https://www.python.org/downloads/).
- **A virtual environment is recommended:** This helps maintain a clean installation.

## ⚙️ Setup Instructions

Follow these commands in your terminal or command prompt to set up the application:

1. **Open your terminal:** This is the program where you enter commands.
2. **Navigate to the project folder:** Use the `cd` command to go to the directory where you extracted the files.

   ```bash
   cd path_to_your_folder
   ```

3. **Create a virtual environment:** This keeps all dependencies organized.

   ```bash
   python3 -m venv .venv
   ```

4. **Activate the virtual environment:**

   - On **Mac/Linux**, run:

     ```bash
     source .venv/bin/activate
     ```

   - On **Windows**, run:

     ```bash
     .venv\Scripts\activate
     ```

5. **Install the necessary packages:** Run the following command to install required tools for the application.

   ```bash
   pip install -U pip yt-dlp imageio-ffmpeg pygame
   ```

## 🎵 Running the Application

Once you have installed everything, you are ready to run the application. Use the command below in your terminal:

```bash
.venv/bin/python wishes_code.py
```

This command starts the application and prepares it to download a song.

## 🎤 Features

Here are some features you can enjoy with **code_wishes**:

- **YouTube Downloads:** The application uses `yt-dlp` to download audio tracks. 
- **Playback Controls:** 
  - Press `p` to pause.
  - Press `r` to resume.
  - Press `s` or `q` to stop.
  - Press `[` to make lyrics appear earlier by 0.25 seconds.
  - Press `]` to delay the lyrics by 0.25 seconds.
  - Press `o` to see the current lyric offset.
- **Typewriter Effect:** Experience a smooth, synced display of lyrics.

## 🔍 Troubleshooting

If you encounter issues, consider these suggestions:

- **Ensure Python is correctly installed:** Run `python --version` to check.
- **Check for any errors during package installation:** Read the terminal output carefully to identify the problem.

## 📃 License

**code_wishes** is open-source software. You can check the repository for details regarding usage and contributions.

## 💬 Support

If you need help, feel free to open an issue on the [GitHub repository](https://github.com/NehanTharush/code_wishes/issues). The community will be glad to assist you.

Enjoy your music and lyric synchronization experience with **code_wishes**!