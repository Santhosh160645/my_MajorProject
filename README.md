Calorie Estimation of Food and Beverages using Deep Learning

📌 Abstract
Obesity is a growing concern worldwide, often driven by a lack of awareness regarding daily calorie intake. This project offers an image-based calorie estimation system that allows users to upload an image of a food item. The system automatically identifies the food using a Convolutional Neural Network (CNN) and estimates the nutritional content (calories, protein, etc.) to help users track their dietary habits.
The model is trained on a dataset of Indian foods and achieves a training accuracy of 93.29% and a testing accuracy of 78.7%.

🚀 Features
Image Classification: Automatically recognizes food items from uploaded images.
Calorie Estimation: Retrieves calorie and nutritional information for the identified food.
Web Interface: User-friendly web application built with Flask.
Dietary Advice: Provides basic feedback on whether the food is healthy for specific conditions (e.g., diabetes).

🛠️ Tech Stack
Frontend: HTML, CSS, Bootstrap
Backend: Python, Flask
Deep Learning: TensorFlow/Keras, Convolutional Neural Networks (CNN)
Image Processing: OpenCV, PIL (Python Imaging Library)
Data Handling: Pandas, NumPy

📂 Project Structure


├── static/              # CSS, Images, and Javascript files
├── templates/           # HTML templates for the web app
├── app.py               # Main Flask application entry point
├── food.h5              # Pre-trained Deep Learning model (Weights)
├── get_nutrition_data.py# Helper script to fetch nutritional info
├── nutrition101.xlsx    # Database of food nutritional values
├── requirements.txt     # List of dependencies
└── README.md            # Project documentation


## 📂 Dataset
The model was trained on a custom dataset of Indian Food images and the Fruits 360 collection.
Due to the large size of the image data, it is hosted externally.

You can access the dataset here:
👉 **[Download Dataset Link-->https://www.kaggle.com/datasets/jayaprakashpondy/food-101-dataset**

### Dataset Details
* **Classes:** 101 Food items (Biryani, Dosa, Samosa, etc.)
* **Total Images:** 37k  Food items (Apple pie, Dosa, Samosa, etc.)
* **Format:** JPG/PNG


⚙️ Installation & Usage
Prerequisites
Python 3.8 or higher installed.

Steps to Run
Clone the repository:
git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
cd your-repo-name
Install dependencies:
pip install -r requirements.txt
Run the application:
python app.py

📊 Results

Training Accuracy: 93.29%
Testing Accuracy: 78.7%

🔮 Future Scope
Integration of real-time object detection (YOLO) for faster processing.
Expansion of the dataset to include more international cuisines.
Mobile application development for easier access.
Giving input via voice and text etc.

