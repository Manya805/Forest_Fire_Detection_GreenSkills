# 🔥 Forest Fire Detection - Green Skills Project
This project is designed to predict forest fires from images using a Convolutional Neural Network (CNN) model, deployed with a user-friendly Streamlit web interface.

📁 Project Structure
![image](https://github.com/user-attachments/assets/84d16baf-a70f-4c95-8137-3a266af499b1)

🔍 Project Overview
    Goal: Automatically detect whether an image shows a forest fire or not.
    
    Model: CNN using TensorFlow and Keras.
    
    Deployment: Streamlit Web App.
        Use case: Early detection of forest fires can help in faster responses and reduce environmental damage.

🧠 Model Details
    ImageDataGenerator is used for data augmentation.
    
    The CNN model includes layers like:
    
    Conv2D, MaxPooling2D, Flatten, Dense, Dropout
    
    Final model is saved as fire_detection_model.h5

🚀 How to Run Locally
1. Clone the Repository
   
    git clone https://github.com/Manya805/Forest_Fire_Detection_GreenSkills.git
   
    cd Forest_Fire_Detection_GreenSkills
   
3. Set Up Virtual Environment (Recommended)
   
    python -m venv venv
   
    venv\Scripts\activate    # For Windows
   
    # Or use `source venv/bin/activate` for Linux/Mac
   
5. Install Requirements
   
    pip install -r requirements.txt
   
    ✅ Make sure tensorflow, streamlit, numpy, Pillow are installed successfully.

7. Run the App Locally
   
    streamlit run app.py
   
    After launching, open the local URL (e.g. http://localhost:8501) in your browser.

🌐 Try It Online

    You can access the deployed version here:
    
    👉 [Forest Fire Detection Web App](https://forestfiredetectiongreenskills-ejl8iwbggmxsthvxgq7uqk.streamlit.app) 

🖼️ Using the App

    Upload an image (ideally of a forest environment).
    
    Click Detect Fire.
    
    Get the result: Forest Fire or No Forest Fire.

📦 Requirements
    1. tensorflow>=2.19.0
    2. streamlit
    3. numpy
    4. Pillow
      ⚠️ If pip is not recognized, ensure Python is correctly added to your system PATH and pip is installed: python -m ensurepip --upgrade

❓ Common Issues
1. ⚠️ Import "tensorflow.keras.*" could not be resolved
    This is a Pylance warning in VS Code.
    If your code runs successfully, you can ignore this warning.
    Ensure your interpreter is set correctly to the virtual environment:
    Go to Command Palette (Ctrl + Shift + P) → Python: Select Interpreter → choose .venv

2. ❌ pip not recognized
   Open terminal and run:
   python -m ensurepip
   python -m pip install --upgrade pip

🙌 Acknowledgments
    TensorFlow
    Keras
    Streamlit
    Dataset sourced from open repositories or custom curated (not uploaded to GitHub due to size)
[Kaggle Dataset Link](https://www.kaggle.com/datasets/abdelghaniaaba/wildfire-prediction-dataset?resource=download)

📬 Contact
Made with 💡 by Manya Asrani
Feel free to connect or suggest improvements via GitHub!
