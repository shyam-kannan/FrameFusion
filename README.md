# FrameFusion-
An AI-powered video frame enhancer and summarizer using machine learning and computer vision

# FrameFusion

**FrameFusion** is an AI-powered video processing tool that enhances video frames using super-resolution techniques and provides automatic video summarization based on scene changes. It allows users to upload a video, processes it frame-by-frame, and delivers a summary video with enhanced quality.

## Key Features:
- **Frame Enhancement**: Uses ESRGAN (Enhanced Super-Resolution GAN) to upscale and improve the quality of video frames.
- **Video Summarization**: Automatically summarizes long videos by detecting key scenes using frame difference analysis.
- **Customizable Summary Length**: Users can define the length of the summarized video.

---

## Technologies Used:
- **Python**: Core programming language for the project.
- **OpenCV**: For video processing and frame extraction.
- **PyTorch**: For running the ESRGAN model for frame enhancement.
- **Flask**: Backend web framework for serving the API and handling video uploads.
- **MoviePy**: For handling video creation from processed frames.
- **React.js**: (Optional) Frontend for uploading videos and viewing the output (future version).

---

## Installation and Setup

### Prerequisites:
Ensure you have **Python 3.8+** installed. Install **pip** if you don't have it yet.

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/FrameFusion.git
   cd FrameFusion

2. **Set up a virtual environment (optional but recommended**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3. **Install dependencies: Run the following command to install the required libraries**:
    ```bash
    pip install -r requirements.txt
4. **Download the ESRGAN Model: Download the pre-trained ESRGAN model from this GitHub repository (https://github.com/xinntao/ESRGAN). Place the model in the app/models directory.**


This will ensure that the commands for setting up the virtual environment and installing dependencies are displayed in code blocks just like the example you showed, making it clear for users on GitHub. 

Let me know if this works for you!

