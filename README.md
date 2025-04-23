# Software Development Chatbot

An AI-powered chatbot designed to assist software developers by providing intelligent responses to development-related queries. Built using Node.js and integrates with OpenAI's API to deliver contextual and relevant answers.

![chatwin1](https://github.com/user-attachments/assets/da824047-4f86-4ee9-8696-9c477d2d4285)

## Technologies Used

- **Backend**: Node.js, Express.js
- **Frontend**: HTML, CSS, JavaScript
- **AI Integration**: OpenAI API

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine.
- An OpenAI API key.

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/milantony05/software-dev-chatbot.git
   cd software-dev-chatbot
   ```


2. **Install dependencies**:
   ```bash
   npm install
   ```


3. **Configure OpenAI API**:
   - Create a `.env` file in the root directory.
   - Add your OpenAI API key:
     ```env
     OPENAI_API_KEY=your-api-key-here
     ```

4. **Start the server**:
   ```bash
   node server.js
   ```


5. **Access the application**:
   - Open your browser and navigate to `http://localhost:3000`.

## Usage

Once the server is running:

1. Navigate to `http://localhost:3000` in your browser.
2. Enter your software development-related queries in the chat interface.
3. Receive intelligent responses powered by OpenAI.

## License

This project is licensed under the [Apache-2.0 License](LICENSE).
