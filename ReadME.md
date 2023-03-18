# Rule-Based Chatbot

This is a simple rule-based chatbot project implemented in Python. The chatbot uses a JSON file that contains a list of intents with associated patterns and responses. The chatbot matches user input with the defined patterns to select an appropriate response.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Python 3.x
- Required Python packages (can be installed using pip):
    - numpy
    - nltk
    - Tensorflow

### Installing

1. Clone the repository or download the source code.
2. Install the required packages using pip: 
    - pip install numpy
    - pip install nltk
    - pip install Tensorflow

### Customization

To customize the bot's responses, you can modify the Data.json file in the project directory. This file contains a list of predefined intents, each with a set of patterns and responses.

To add a new intent, simply add a new object to the intents list in the JSON file. The object should have the following structure:

{
    "tag": "<intent_tag>",
    "patterns": ["<pattern_1>", "<pattern_2>", ...],
    "responses": ["<response_1>", "<response_2>", ...]
}

Replace <intent_tag> with a unique identifier for your intent, <pattern_1> and <pattern_2> with example phrases that the user might input to trigger the intent, and <response_1> and <response_2> with the bot's possible responses to the input.