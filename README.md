This version elevates the professional tone, adds visual structure with badges, and emphasizes the technical sophistication of the project. It also incorporates a more secure way to handle your Gemini API key, which is a standard practice for the AI projects you're building.

-----

# 🎨 AI Virtual Painter: The Pictionary of the Future

[](https://www.python.org/)
[](https://mediapipe.dev/)
[](https://ai.google.dev/)
[](https://opensource.org/licenses/MIT)

**AI Virtual Painter** is an immersive, gesture-controlled drawing application. By leveraging high-performance computer vision and generative AI, it allows users to "paint" in 3D space using hand gestures. Once your masterpiece is complete, the **Google Gemini AI** engine analyzes the canvas to guess the drawing—bringing a futuristic twist to the classic game of Pictionary.

-----

## 🚀 Core Features

  * **🖐️ Real-Time Gesture Recognition:** Powered by **OpenCV** and **MediaPipe**, the system tracks 21 hand landmarks with ultra-low latency.
  * **🧠 Intelligent Guessing:** Integrated with **Google Gemini Pro Vision** to interpret complex hand-drawn sketches and provide real-time feedback.
  * **🛡️ Futuristic HUD:** A sci-fi inspired user interface featuring scanner lines, hexagonal overlays, and dynamic UI elements.
  * **🛠️ Multi-Tool Canvas:** Seamlessly switch between brushes and erasers using specialized hand "Selection Mode."
  * **🎯 Adaptive Prompting:** Built-in challenge system that generates random prompts to test your drawing skills.

-----

## 🛠️ Technical Stack

| Component | Technology |
| :--- | :--- |
| **Language** | Python 3.8+ |
| **Computer Vision** | OpenCV, MediaPipe |
| **Generative AI** | Google Gemini API |
| **Automation** | PyAutoGUI |
| **Math/Logic** | NumPy |

-----

## 📥 Installation

1.  **Clone the Repository:**

    ```bash
    git clone https://github.com/soumyadoshii/ai-virtual-painter.git
    cd ai-virtual-painter
    ```

2.  **Set Up a Virtual Environment (Recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3.  **Install Dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

-----

## 🎮 How to Play

### 1\. Launch the Game

```bash
python final.py
```

### 2\. Control Logic

  * **Drawing Mode:** Raise only your **Index Finger**. Move it to paint on the digital canvas.
  * **Selection Mode:** Raise both **Index and Middle Fingers**. Hover over the top menu to select colors or the eraser.
  * **Submit (Guessing):** Press **'S'** to send your drawing to the Gemini AI.
  * **New Challenge:** Press **'N'** to generate a new drawing prompt.
  * **Exit:** Press **'Q'** to safely close the application.

-----

## 📂 Project Structure

```text
├── final.py            # Primary AI Guessing Game (Full UI)
├── main.py             # Sandbox Drawing Mode (No AI)
├── HandTracking.py     # Custom MediaPipe logic wrapper
├── requirements.txt    # Project dependencies
├── Header/             # UI Assets & Toolbar overlays
├── screenshots/        # Saved captures and output logs
└── test_scripts/       # Experimental UI and feature tests (test1.py to test5.py)
```

-----

## 🔑 Configuration & Security

To enable the AI guessing feature, you must provide a Google Generative AI API Key.

> **Tip:** Instead of hardcoding your key, it is best practice to use an environment variable or a `.env` file.

```python
# In final.py
genai.configure(api_key="YOUR_ACTUAL_API_KEY")
```

-----

## 🤝 Credits

  * **Developer:** [Soumya Doshi](https://www.google.com/search?q=https://github.com/soumyadoshii)
  * **Hand Tracking:** [MediaPipe Hands](https://www.google.com/search?q=https://google.github.io/mediapipe/solutions/hands.html)
  * **Vision Engine:** [Google Gemini](https://ai.google.dev/)

-----

Would you like me to help you draft a `.gitignore` file so those `__pycache__` folders don't clutter your GitHub?
