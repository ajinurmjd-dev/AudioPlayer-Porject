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
🚀 How to Run
1. Clone this repository:
git clone [HERE](https://github.com/ajinurmjd-dev/AudioPlayer-Porject.git)

2. Navigate to the project folder:
cd AudioPlayer-Porject

3. Run the application:
python main.pyw

    *(Using `.pyw` will run the app without the terminal window).*

---

## 📂 Project Structure

*   `main.pyw`: The main entry point and UI logic.
*   `audio_engine.py`: The core audio engine handling VLC and metadata extraction.
*   `smart_shuffle.py`: The logic for the Tetris-Bag shuffling algorithm.
*   `player_settings.json`: Stores your last opened folder (auto-generated).

---

## 🖼️ Preview

*(Pro tip: Lu bisa screenshot aplikasi lu, upload ke folder 'assets' di GitHub, terus panggil gambarnya di sini)*

| Player Interface | Custom Equalizer |
| :---: | :---: |
| ![Player](https://via.placeholder.com/400x250?text=Adaptive+UI+Preview) | ![Equalizer](https://via.placeholder.com/400x250?text=10-Band+EQ+Preview) |

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

**Made with ❤️ for the Audiophile Community.**
