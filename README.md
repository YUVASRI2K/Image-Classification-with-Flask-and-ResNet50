# Image-Classification-with-Flask-and-ResNet50
This Flask app allows users to upload an image and get predictions using a pre-trained ResNet50 model:

Setup:

Flask: Handles web requests.
ResNet50: A deep learning model for image classification.
Routes:

GET /: Displays an upload form (HTML template).
POST /: Handles image uploads, processes the image, and returns the model’s prediction.
Workflow:

Upload an image.
Save and preprocess the image.
Use ResNet50 to predict the image class.
Show the prediction result on the same page.
The app combines machine learning and web development to classify images and display results easily.
