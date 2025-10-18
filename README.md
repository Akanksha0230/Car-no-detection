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

Once the application is running, open your web browser and navigate to `http://127.0.0.1:8000/` to access the app interface. You can start searching the products, and the app will respond based on your input. It gives the anaylis of the products and shows the results in the form of interactive charts and plots. We can easily know the price, rating and reviews of products in short time. 