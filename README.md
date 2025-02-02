# Emotional Support AI Chatbot

## Overview
The **Emotional Support AI Chatbot** is designed to assist users by offering emotional support. It interacts with users through greetings, detects their emotional state based on text input, provides emotional keywords, suggests self-care tips, and offers a friendly end to the conversation. This chatbot is currently focused on offering basic emotional support with room for future enhancements.

## Features
- **Greetings**: The chatbot welcomes users and initiates the conversation with a friendly message.
- **Emotion Detection**: It detects the user's emotional state based on their input.
- **Emotion Keywords**: Identifies and provides keywords associated with emotions like happiness, sadness, and anxiety.
- **Self-care Tips**: Suggests self-care tips based on the detected emotion to help users manage their feelings.
- **End of Conversation**: Gracefully ends the conversation with a friendly message.
- **Voice search**: Allows users to interact with the chatbot using voice commands.

## Chatbot Interface
<img width="306" alt="image" src="https://github.com/user-attachments/assets/48fccebb-f3a0-4f37-9ded-ed4e2452fe52" />

## Demo

Watch the demo of the Emotional Support AI Chatbot in action:
[https://drive.google.com/file/d/15hme9zrYCSd3aBmASgGYh6VyEIkAh9Fo/view?usp=sharing](https://www.kapwing.com/videos/678cc1c0ca054d75b0e0f193)

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

## How It Works:
- **User Interaction**: The user communicates with the chatbot through text or voice input.
- **Emotion Detection**: The chatbot analyzes the user's input to detect the emotion behind it.
- **Response Generation**: Based on the detected emotion, the chatbot provides relevant self-care tips or responses.
- **End of Conversation**: The user can end the conversation at any time by saying "goodbye" or similar phrases.
- **Voice Input**: The chatbot also supports voice search for users who prefer speaking over typing.

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
