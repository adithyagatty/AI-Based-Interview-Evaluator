# AI-Based Interview Evaluator: An Emotion and Confidence Classifier

This project is an AI-based interview evaluator that uses natural language processing (NLP) and machine learning to classify emotions and confidence levels in interview responses.

## Features

- Classifies emotions and confidence levels in text responses.
- Provides feedback based on the classified emotions and confidence levels.
- Uses a pre-trained model for NLP tasks.

## Setup Instructions

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd ai-evaluator
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Download NLTK data packages:
    ```python
    import nltk
    nltk.download('popular')
    ```

4. Place the pre-trained model (`modelchat.h5`), intents file (`intents.json`), and pickle files (`textschat.pkl`, `labelschat.pkl`) in the project directory.

## Running the Application

1. Start the Flask application:
    ```sh
    python app.py
    ```

2. Open your web browser and go to `http://127.0.0.1:5000/` to interact with the chatbot.

## Project Structure

- `app.py`: Main application file that sets up the Flask server and handles chatbot responses.
- `intents.json`: JSON file containing the intents and responses for the chatbot.
- `modelchat.h5`: Pre-trained model file for NLP tasks.
- `textschat.pkl` and `labelschat.pkl`: Pickle files containing the vocabulary and labels for the model.
- `templates/`: Directory containing HTML templates for the web interface.
- `static/`: Directory containing static files (CSS, JS, images).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
