# Mental Health Chatbot

**English** | [Español](README.es.md)

## Main features

1. **Dataset loading**: The chatbot starts by loading a dataset containing examples of mental health conversations. This dataset is used to train the chatbot's artificial intelligence model.

2. **Tokenization**: The chatbot processes the dataset text by splitting it into individual tokens, such as words. This is a crucial step in natural language processing.

3. **Model creation**: The chatbot uses a neural network model to understand and answer questions. The model is created and configured during this stage.

4. **Model training**: Once the model has been created, it is trained using the dataset. During this process, the model learns to associate certain word patterns with specific responses.

5. **Model saving**: Once trained, the model is saved for future use. This means it does not need to be retrained every time the chatbot is used, saving time and computing resources. The saved model can also be shared and reused, supporting reproducibility and collaboration.

6. **Model validation (optional)**: Validation uses test data to evaluate the model's performance and ensure that it can make accurate predictions on new data.

7. **Chat deployment**: Once the model is loaded, it is used to interact with the user and generate an appropriate response to each input.

### Installation

#### Prerequisites
- Python 3.10.11
- pip

#### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/Fernandolopez2171/mental-health-chatbot.git
   cd mental-health-chatbot
   ```

2. Install the backend dependencies:
   ```sh
   pip install -r requirements.txt
   ```

### Usage

#### Main scripts
1. Run the AI training:
   ```sh
   python training.py
   ```

2. Test the chatbot in the console:
   ```sh
   python chat.py
   ```

#### Optional
Validate the model with test data:
   ```sh
   python validate.py
   ```

#### API deployment
To use the chatbot as an API, run:
   ```sh
   python app.py
   ```

[Versión en español](Readme.md)
