# AI Chat Assistant

A modern, real-time chat application powered by OpenAI's GPT-3.5 API. Built with React (Vite), Node.js, and styled with Tailwind CSS.


## Features

- 🎯 Real-time chat interface
- 🎨 Modern and responsive UI with Tailwind CSS
- 🤖 Powered by OpenAI's GPT-3.5 API
- ⚡ Fast and efficient with Vite
- 🔄 Automatic message scrolling
- 💬 Beautiful chat bubbles with user/AI indicators
- 🌈 Loading animations and transitions

## Tech Stack

- **Frontend:**
  - React (Vite)
  - Tailwind CSS
  - Heroicons
  - Headless UI

- **Backend:**
  - Node.js
  - Express
  - OpenAI API
  - CORS
  - Dotenv

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- OpenAI API key

### Installation

1. Clone the repository:
```bash
git clone https://github.com/IsabelaBaseggio/ai-chatbot-assistant.git
cd /ai-chatbot-assistant
```

2. Install Frontend Dependencies:
```bash
cd frontend
yarn
```

3. Install Backend Dependencies:
```bash
cd ../backend
yarn
```

4. Configure Environment Variables:
   - In the backend directory, create a `.env` file:
```bash
PORT=3000
OPENAI_API_KEY=your_openai_api_key_here
```

### Running the Application

1. Start the Backend Server:
```bash
cd backend
yarn dev
```
The server will start on http://localhost:3000

2. Start the Frontend Development Server:
```bash
cd frontend
yarn dev
```
The frontend will be available at http://localhost:5173

## Usage

1. Open your browser and navigate to http://localhost:5173
2. Start chatting with the AI assistant by typing your message in the input field
3. Press Enter or click the send button to send your message
4. The AI will respond with relevant information based on your input

## Project Structure

```
ai-chatbot-assistant/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Chat.jsx
│   │   │   └── ChatMessage.jsx
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
│
└── backend/
    ├── server.js
    ├── package.json
    └── .env
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- OpenAI for providing the GPT-3.5 API
- Tailwind CSS for the awesome styling utilities
- The React and Vite teams for the excellent development experience
