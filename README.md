# 🎵 Smart Shuffle Player - Audiophile Edition

A sleek, modern, and high-fidelity FLAC audio player built with Python. Inspired by the aesthetics of Apple Music, designed for the audiophile who demands control and visual elegance.

---

## 🌟 Features

*   **🔊 High-Fidelity Audio**: Powered by the VLC engine to support lossless FLAC playback with crystal clear quality.
*   **🎨 Adaptive UI**: The player's background color dynamically changes to match the dominant colors of the current track's album art.
*   **🎛️ 10-Band Studio Equalizer**: A dedicated graphic equalizer window for real-time manual tuning (+12dB to -12dB).
*   **🧠 Smart Shuffle (Tetris Bag)**: An advanced shuffling algorithm that guarantees you won't hear the same track twice until the entire bag is empty.
*   **⏩ Precision Seeking**: A smooth progress bar that allows you to drag and jump to any part of the song instantly.
*   **💾 Auto-Load Memory**: Automatically remembers and loads your last opened music folder upon startup.
*   **🖥️ DPI Awareness**: Crisp and sharp UI that scales perfectly across multiple monitors (4K, Laptop, or External displays).

---

## 🛠️ Requirements

Before running the player, make sure you have the following installed:

1.  **VLC Media Player**: [Download VLC](https://www.videolan.org/vlc/) (The engine depends on the VLC 64-bit installation).
2.  **Python 3.x**
3.  **Required Libraries**:
    ```bash
    pip install customtkinter pillow python-vlc mutagen
