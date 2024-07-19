# Voice Assistant Chatbot

This project is a Voice Assistant Chatbot that leverages the power of OpenAI's GPT model and IBM Watson's Text-to-Speech and Speech-to-Text services. The chatbot provides users with a conversational interface to interact with AI, offering functionalities such as answering questions, performing tasks, and providing information.

## Features

- **Voice Interaction**: Users can speak to the chatbot using their microphone, and the chatbot will respond using IBM Watson's Text-to-Speech.
- **Text Interaction**: Users can also type their queries, and the chatbot will respond with text.
- **Light/Dark Mode**: A toggle switch allows users to switch between light and dark modes for a comfortable viewing experience.
- **Voice Selection**: Users can choose from a variety of voices provided by IBM Watson for the chatbot's responses.

## Demo
[Youtube](https://youtube.com/cyberfantics)

## Technologies Used

- **OpenAI GPT**: For generating responses to user queries.
- **IBM Watson**: For Text-to-Speech and Speech-to-Text capabilities.
- **HTML, CSS, JavaScript**: For building the front-end interface.
- **Bootstrap**: For responsive and mobile-friendly design.
- **jQuery**: For handling DOM manipulations and AJAX requests.

## Getting Started

### Prerequisites

- Python installed on your machine.
- IBM Watson API credentials.
- OpenAI API key.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/cyberfantics/chatbot-with-voice-and-openai.git
    cd chatbot-with-voice-and-openai
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Set up your environment variables:

    Create a `.env` file in the root of the project and add your IBM Watson and OpenAI API credentials:

    ```env
    IBM_API_KEY=your_ibm_api_key
    IBM_URL=your_ibm_url
    OPENAI_API_KEY=your_openai_api_key
    ```

4. Run the project:

    ```bash
    docker build . -t chatbot-with-voice-and-openai
    docker run -p 8000:8000 chatbot-with-voice-and-openai
    ```

5. Open your browser and navigate to `http://localhost:8000`.

## Usage

1. **Toggle Light/Dark Mode**: Use the switch at the top to toggle between light and dark modes.
2. **Choose a Voice**: Select a voice from the dropdown menu to change the voice of the chatbot's responses.
3. **Interact with the Chatbot**: Type your message in the input box or click the microphone icon to speak to the chatbot.

## File Structure

```plaintext
.
├── public
│   ├── index.html
│   ├── css
│   │   └── style.css
│   ├── js
│   │   └── script.js
├── src
│   ├── app.js
│   ├── routes
│   │   └── index.js
├── .env
├── package.json
├── README.md
```

## Developer
Syed Mansoor ul Hassan Bukhari
