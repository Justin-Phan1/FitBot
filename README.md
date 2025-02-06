# FitBot
This project is essentially a "chatbot" that provides users with information regarding to fitness. Unfortunately due to subscriptions and poor support for deploying 
Flask projects on hosting services, I was unable to successfully host my project on the web. 

## Project Description 
This project is a deep learning model created using PyTorch in Python. It also utilizes the NLTK (Natural Language Toolkit) and NumPy libraries in Python. The project's frontend is 
created with React.js and Flask in order to allow users to interact with an interface. 

## Installation + Usage

1. Open a terminal 
2. Run the command ``` git clone https://github.com/Justin-Phan1/FitBot```
3. Navigate to the project folder
4. Run the ```train.py``` script to train the model. *Note. You should see a "data.pth" file pop up in the project*
5. In the project's root folder run ```python -m backend.server``` to start the Flask server
6. Navigate to the frontend folder using ```cd frontend```
7. Install dependencies using ```npm install```
8. Run the react app using ```npm start```
9. Open a browser and search http://localhost:3000, if the site doesn't automatically open
10. Ask away!
