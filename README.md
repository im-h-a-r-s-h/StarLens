<a id="readme-top"></a>

# About The Project

## StarLens

StarLens is an AI-powered celebrity recognition system. Using a machine learning model, it identifies and classifies images of celebrities. This project provides a platform where users can upload images, and the system will predict which celebrity is in the image.

![Screenshot_23-11-2024_195331_127 0 0 1](https://github.com/user-attachments/assets/2c4091a0-4627-4094-ad98-fdba3a5f0679)

### Features

* Celebrity image classification using a trained machine learning model.
* A simple web-based interface for image uploads.
* Powered by Python, machine learning algorithms, and web interface by HTML, CSS, JS.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Usage
1. Upload an image via the web interface.
2. The application will process the image and display the predicted celebrity name.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Technologies
1. Python: Core programming language for model and server.
2. Numpy and OpenCV for data cleaning.
3. Matplotlib & Seaborn for data visualization.
4. Sklearn for model building.
5. Visual Studio Code.
6. Python Flask for HTTP server.
7. HTML/CSS/JavaScript for UI.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Installation

1. Train the model file (sports_celebrity_classification.ipynb).
2. Copy the trained model to the artifacts folder inside the server.
3. Run the server:
   ```sh
   python server/app.py
   ```
4. Navigate to http://127.0.0.1:5000 to access the application.
   
<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Folder Structure

```
StarLens/
  ├── model/ #Jupyter model
      ├── dataset/ # contain images
      ├── sports_celebrity_classification.ipynb
      ├── requirements.txt
  ├── UI/
      ├── app.html
      ├── app.css
      ├── app.js
      ├── images
  ├── server/ # Python backend code
      ├── server.py # Main entry point for the server
      ├── artifacts #copy your Trained model here
          ├── class_dictionary.json
          ├── saved_model.pkl
```
<p align="right">(<a href="#readme-top">back to top</a>)</p>
