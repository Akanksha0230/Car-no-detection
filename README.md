# Car Number Plate Detection Project

This Python-based project uses OpenCV to detect car number plates in real time through your system's camera. The application automatically identifies license plates using the Haar Cascade Classifier and allows you to capture and save detected plate images with a single key press.

### **Features:**

- # Real-Time Number Plate Detection:
When you run the program, it activates your webcam and starts detecting number plates in live video feed using the Haar Cascade model.
- # Automatic Plate Highlighting:
Detected plates are highlighted with a green rectangle, and the label “Number Plate” appears above the detection box for clear visibility.
- # Live Camera Interface:
The camera feed is displayed on screen, and any detected number plate is shown in a separate preview window (Region of Interest - ROI).
- # Save Detected Plates:
Press the ‘s’ key to save the detected number plate image. The image will be stored automatically inside the plates/ directory with a unique name.

### **Prerequisites:**

Before you begin, ensure you have the following installed:

- Anaconda or Miniconda
- Python 3.9

### **Setup Instructions:**

1. Create a Conda Environment:
   - Run the following command to create a new Conda environment named `venv` with Python 3.10:
     ```
     conda create -p ./venv python=3.9 -y

     ```

2. Activate the Environment:
   - Activate the newly created environment with:
     ```
     conda activate ./venv
     ```

3. Install Requirements:
   - Install the necessary dependencies using pip:
     ```
     pip install -r requirements.txt
     ```

4. Run the Application:
   - Start the application by running:
     ```
     python number_plate.py
     ```

### **Usage:**

Once the application is running, The webcam will open, and the live detection window will appear. Hold a vehicle number plate in front of the camera — it will be detected automatically. Press ‘s’ to save the detected plate image. 
              

The system uses Haar Cascade Classifier, a pre-trained XML model, to detect rectangular regions resembling number plates. Each detected region is extracted as an ROI (Region of Interest) and displayed separately. The application continuously scans the live feed until manually stopped.



