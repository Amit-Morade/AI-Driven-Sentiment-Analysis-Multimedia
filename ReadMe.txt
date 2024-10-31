
# README.txt

## Project Setup and Execution Guide

This README file is designed to guide anyone, including those with no prior knowledge of the project, to successfully set up and run the entire project. Follow the detailed steps and procedures below to ensure a smooth experience.

---

### Hardware and Software Requirements:

- **Hardware:**
  - Processor: Intel Core i5 or equivalent, minimum 2 GHz (or faster)
  - RAM: 8 GB (16 GB recommended)
  - Storage: 2 GB free space for software and dependencies
  - Graphics Card: Dedicated GPU recommended for deep learning tasks

- **Software:**
  - [Python 3.8 or higher](https://www.python.org/downloads/): Required for backend programming and machine learning libraries.
  - [Node.js](https://nodejs.org/): Required for frontend package management and builds.
  - [Git](https://git-scm.com/): Essential for cloning the project repository.
  - [FFmpeg](https://ffmpeg.org/download.html): Required for handling multimedia processing.
  - [CUDA Toolkit (Optional)](https://developer.nvidia.com/cuda-toolkit): Recommended for GPU-accelerated model execution.
  - Python Libraries: Install all required Python libraries using the `requirements.txt` file.

---

### Contributors:

This project was a collaborative effort, and each team member played a crucial role:

- **Rohit Shelke:**
  - Focused on backend development, integrating machine learning models for emotion recognition and processing multimedia files for video and audio inputs.

- **Amit Morade:**
  - Led the frontend development, implementing interactive visualizations using D3.js and Material-UI, and designed the user interface for file upload and text input.

Both students collaborated on testing, integration, and optimization of the project to ensure a seamless user experience.

---

### Project Overview:

This project is a comprehensive web application designed for emotion recognition and sentiment analysis. Combining machine learning, data visualization, and multimedia processing, the application enables users to analyze audio, video, and textual inputs. Users can upload files or input text and view interactive visualizations that reveal the emotional tone and sentiment distribution.

---

### Instructions for Setup and Execution:

1. **Backend Setup**
   - Clone the repository:
     ```
     git clone https://github.com/RohitShelke10/multimedia-sentiment-analyzer.git
     ```
   - Navigate to the backend directory:
     ```
     cd backend
     ```
   - (Optional) Set up a virtual environment:
     ```
     python -m venv env
     source env/bin/activate  # Linux/Mac
     env\Scripts\activate     # Windows
     ```
   - Install required Python dependencies:
     ```
     pip install -r requirements.txt
     ```
   - Start the FastAPI server:
     ```
     fastapi dev main.py
     ```

2. **Frontend Setup**
   - Navigate to the frontend directory:
     ```
     cd frontend
     ```
   - Install frontend dependencies:
     ```
     npm install
     ```
   - Start the React development server:
     ```
     npm start
     ```

3. **Running the Application**
   - Ensure both backend and frontend servers are running.
   - Open a browser and navigate to `http://localhost:3000`.
   - Upload a media file (audio/video) or enter text to analyze emotion and sentiment. The results will display as interactive visualizations, including bar graphs, line plots, and pie charts.

---

By following these instructions, anyone should be able to successfully set up and run the project. If you encounter any issues or have questions, feel free to contact [provide contact information].

Thank you for using our project!
