# CricPix-Classifier
CricPix-Classifier, a Cricketer Image Classification app, is a Flask web application for Image Recognition using a machine learning model selected with GridSearch CV that has been trained to recognize Cricket Players. The application uses a combination of raw and wavelet transformed image features to make predictions. The model was trained using Scikit-learn, OpenCV, and PyWavelets libraries.

# Installation

Clone the repository and navigate to the root folder:
```terminal
git clone https://github.com/yourusername/yourproject.git
cd yourproject
```

Create a virtual environment: 
```terminal
python3 -m venv venv
```

Activate the virtual environment:  
On Windows:  
```terminal
venv\Scripts\activate
```

On Linux or macOS:
```terminal
source venv/bin/activate
```

Install the dependencies: 
```terminal
pip install -r requirements.txt
```

# Usage
To run the application, navigate to the root folder and execute the following command:  
```terminal
python app.py
```
Then, open a web browser and go to http://localhost:5000/.
Upload an image and the application will predict the face in the image using the pre-trained machine learning model.

# Files
* app.py: This is the Flask web application that serves as the main entry point of the program. It uses the machine learning model to predict the face in an uploaded image.

* main.py: This is the Python script that trains the machine learning model using Scikit-learn, OpenCV, and PyWavelets libraries.

* model.pkl: This is the pre-trained machine learning model.

* class_dictionary.json: This is the dictionary that maps the predicted class to a human-readable label.

* dataset: This directory contain the data used for training the model.

* static/image.png: This is the image which I used in my application.

* templates/index.html: This is the HTML template that defines the layout of the web application.

* test_images: This is the directory which contain test datasets for the classification.

* data_acquisition/web_scraping.py: This is the python code which I used for web scrapping images from Google.

# License
This project is protected by the MIT License. See the LICENSE file for more details.

# Credits
* This project was created by Utsav Acharya.
* The face recognition model was trained webscrapping Google Images.
* The Haar Cascade classifiers used for face and eye detection were trained by OpenCV.
* The PyWavelets library was used for wavelet transform.
* The Flask web framework was used to create the web application.

 



