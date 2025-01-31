# Movie Dialogs Chatbot with Seq2Seq and GPT-2

This repository contains code for building a chatbot that generates responses using a Seq2Seq model with attention mechanism for dialog management and a GPT-2 model for generating varied responses based on user input questions.

## Dataset

The Cornell Movie-Dialogs Corpus is used in this project. It contains a collection of conversations from movie scripts.

### Downloading the Dataset

The Cornell Movie-Dialogs Corpus can be downloaded [here](https://drive.google.com/file/d/1zWqB64cdGXrleiWmLlij5inP3t1Rxgwl/view?usp=sharing).

## Models Used

- **Seq2Seq Model with Attention:** Utilizes LSTM layers with attention mechanism to predict responses based on input dialogs.
- **GPT-2 Model:** Generates diverse responses to user input questions.

## Requirements

- Python 3.x
- TensorFlow 2.x
- Transformers library (for GPT-2)
- Convokit
- Other dependencies (specified in `requirements.txt`)

## Usage

1. **Setup Environment:**
   - Clone the repository and navigate to the project directory.
   - Set up a virtual environment and install dependencies using `pip install -r requirements.txt`.

2. **Training:**
   - Run the `train.py` script to train the Seq2Seq model with the Cornell Movie-Dialogs Corpus.

3. **Generating Responses:**
   - Use the `generate_responses.py` script to interact with the chatbot.
   - Example: `python generate_responses.py`

4. **Adjusting Models:**
   - Explore different hyperparameters for both Seq2Seq and GPT-2 models in their respective scripts (`train.py`, `generate_responses.py`).

## Example Output

![Example Output](example_output.png)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- The Cornell Movie-Dialogs Corpus
- OpenAI for the GPT-2 model
- Convokit library for corpus management

## Authors

- Ruthvik Reddy Anugu(https://github.com/ruthvik-reddy138)

