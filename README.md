# Car Number Plate Detection Project

This Streamlit-based web app allows users to search for products directly from the Myntra website and view detailed information in a tabular format. It also provides a powerful analysis tool to compare products based on price, ratings, and reviews using interactive charts and plots.

### **Features:**

- # Live Product Search on Myntra: 
Users can enter a product name, and the app fetches real-time results directly from the Myntra website, displaying product details in a clean tabular format.
- # Detailed Product Table View:
 Extracted data includes product name, price, rating, and review count—presented neatly in an interactive table within the Streamlit interface.
- # One-Click Comparative Analysis:
A dedicated “Generate Analysis” page allows users to visualize comparisons of selected products based on price, ratings, and review counts.
- # Insightful Visual Charts:
Automatically generated bar charts and plots provide a clear visual understanding of product comparisons to aid better decision-making.

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