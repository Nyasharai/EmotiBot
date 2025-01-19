# Emotional Support AI Chatbot

## Overview
The **Emotional Support AI Chatbot** is designed to assist users by offering emotional support. It interacts with users through greetings, detects their emotional state based on text input, provides emotional keywords, suggests self-care tips, and offers a friendly end to the conversation. This chatbot is currently focused on offering basic emotional support with room for future enhancements.

## Features
- **Greetings**: The chatbot welcomes users and initiates the conversation with a friendly message.
- **Emotion Detection**: It detects the user's emotional state based on their input.
- **Emotion Keywords**: Identifies and provides keywords associated with emotions like happiness, sadness, and anxiety.
- **Self-care Tips**: Suggests self-care tips based on the detected emotion to help users manage their feelings.
- **End of Conversation**: Gracefully ends the conversation with a friendly message.

## Technologies Used
- **Node.js**: Used for backend development.
- **Dialogflow**: Used for the natural language processing and intent recognition.
- **JavaScript**: Used for chatbot logic and interaction.
- **JSON**: Used for storing intents and entities for easy modifications and scalability.

## Installation

1. Clone the repository to your local machine.
    ```bash
    git clone https://github.com/Nyasharai/EmotibotAI.git
    ```

2. Navigate to the project folder.
    ```bash
    cd EmotibotAI
    ```

3. Install the required dependencies.
    ```bash
    npm install
    ```

4. Run the chatbot application.
    ```bash
    npm start
    ```

## Usage
Once the application is running, you can interact with the chatbot by typing your emotions. It will provide appropriate responses based on the detected emotion and give suggestions for self-care. The chatbot will offer a friendly greeting at the start and gracefully close the conversation at the end.

### Sample Interactions:
- **User:** "I feel sad."
- **Bot:** "I'm sorry you're feeling sad. Here's a self-care tip: Try talking to a friend or doing something creative like drawing."

- **User:** "I'm happy today!"
- **Bot:** "That's wonderful to hear! Keep enjoying your day and take time to appreciate your happiness."

## Future Enhancements
- Add support for more complex emotional analysis.
- Implement multi-turn conversations for continuous emotional support.
- Integrate additional self-care resources and guides.
- Implement a personalized user experience based on past interactions.

## License
This project is licensed under the MIT License.
