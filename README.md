
# PetAI Chat Assistant

PetAI Chat Assistant is a React-based frontend for interacting with a RAG (Retrieval-Augmented Generation) chatbot. It allows users to ask questions and get intelligent responses from the AI assistant in real-time.

## Live Demo
[[PetAI Chat Assistant]](https://petai.ama24.my/)

---

## Features

- **Real-time Chat**: Send messages and receive AI responses instantly.
- **Conversation History**: Scrollable chat with all previous messages.
- **Loading Indicator**: Shows when the AI is processing a response.
- **Responsive Design**: Works on desktop and mobile devices.
- **Configurable API**: Easily set backend URL in `config.js`.

---

## Tech Stack

- **Frontend**: React, Axios
- **Styling**: CSS
- **API**: Connects to RAG Chat backend (FastAPI)

---

## Installation

Clone the repository:

```bash
git clone https://github.com/amaaljuffry/rag-frontend.git
cd rag-frontend
````

Install dependencies:

```bash
npm install
```

Start development server:

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) to view in the browser.

---

## Configuration

Set your backend API URL in `config.js`:

```javascript
export const API_URL = "https://your-backend-url.com/api/chat";
```

---

## Usage

1. Type your question in the input box.
2. Press **Send** or hit **Enter**.
3. The AI assistant will respond in real-time.

---

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## License

MIT License
