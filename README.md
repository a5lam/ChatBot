# ChatBot

ChatbotIn is a Python project with source code, in which I have used a deep learning techniques. The chatbot will be trained on the dataset which contains categories (intents), pattern and responses. I have used a special recurrent neural network (LSTM) to classify which category the user’s message belongs to and then we will give a random response from the list of responses.


## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install tensorflow, keras, pickle and nltk.

```terminal
pip install tensorflow, keras, pickle, nltk
```


## Usage

1. First, train the model using the command in the terminal:
   python train_chatbot.py

2. If you don’t see any error during training, you have successfully created the model. Then to run the app, run the second file.
   python chatgui.py
   
  
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
