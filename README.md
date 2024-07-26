# chatbot-app-lab
This code creates a chatbot that uses Facebook’s Blenderbot model and Hugging Face’s Python library, Transformer. Lab from IBM's Building Gen AI-powered Applications course ( Interface not my design.)

In order to run it, you'll first need to install Flask in your terminal:

```
python3.11 -m pip install flask
python3.11 -m pip install flask_cors
```

You'll also need to install Hugging Face's Transformer library: 

```
python3.11 -m pip install transformers torch
```

To run the app, type `flask run` in the terminal. By default, Flask hosts the server at http://127.0.0.1:5000/. You can access it by visiting http://127.0.0.1:5000/ or http://localhost:5000/ in your web browser.


You can stop running the app by typing `Ctrl + C`. 
