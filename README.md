# CSE 5914 Capstone Project - Cocktail Order Chatbot

An interactive and user-friendly web application designed to assist users in ordering cocktails and tracking various details. Powered by a Rasa NLU backend and a React frontend.

## Running the Application

### Launching the React Frontend  
In the project directory, start the React app:  
`npm start`

### Starting the Rasa Server
Navigate to rasa_model directory:  
`cd rasa_model`  
Run the action server:  
`rasa run actions`  
Start the Rasa server:  
`rasa run --enable-api --cors "*"`

