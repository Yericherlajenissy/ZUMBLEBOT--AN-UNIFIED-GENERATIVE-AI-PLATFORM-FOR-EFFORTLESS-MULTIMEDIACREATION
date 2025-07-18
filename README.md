# ZUMBLEBOT - AN UNIFIED GENERATIVE AI PLATFORM FOR EFFORTLESS MULTIMEDIA CREATION

## 🚀 Steps to Execute the Project

### 1️⃣ Clone the Repository

```bash
git clone <your-repo-url>
cd <your-project-folder>
```

---

### 2️⃣ Set Up the Environment

Create a virtual environment to manage dependencies:

```bash
# For Windows
python -m venv venv
venv\Scripts\activate

# For Linux/Mac
python3 -m venv venv
source venv/bin/activate
```

---

### 3️⃣ Install Required Libraries

Use the provided `requirements.txt` to install all dependencies (Flask, Transformers, Torch, Diffusers, OpenCV, etc.)

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Run the Flask Backend

Start the backend server which handles the API calls for text, image, music, and video generation.

```bash
# From your project directory
python app.py
```

This will start the Flask server on `http://127.0.0.1:5000/`.

---

### 5️⃣ Access the Frontend

* Open your browser and navigate to `http://127.0.0.1:5000/`.
* Use the dark-themed UI to input your text prompts and choose your output type (text, image, music, video).

---

### 6️⃣ For Video Generation

* ZumbleBot uses Google Colab to handle GPU-intensive video generation with AnimateDiff.
* When you request a video, it automatically redirects you to a Colab notebook pre-configured for text-to-video processing. Run the cells to generate and download your video.

---

### ✅ Done!

You can now:

* Generate **text** using Qwen2.5-1.5B-Instruct.
* Generate **images** using Stable Diffusion v1.5.
* Generate **music** using MusicGen-Small.
* Generate **videos** using AnimateDiff via Google Colab.

