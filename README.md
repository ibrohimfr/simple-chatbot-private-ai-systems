# Minimal Chatbot

A very simple, lightweight, and full-screen chatbot application. This project provides a single-page chat interface that connects to an AI language model (Google Gemini by default) via a basic Node.js backend. 

### Features
- **Full-Screen UI**: A clean, distraction-free chat interface.
- **Markdown Support**: Correctly renders AI responses formatted in Markdown (bold text, code snippets, lists, etc.) using `marked.js`.
- **Lightweight Backend**: Built on Node.js and Express to securely handle API keys.
- **Easy Setup**: Minimal dependencies and easy-to-understand code.

---

## Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine.
- An API Key from Google Gemini (or the LLM provider you choose to use).

## Setup & Installation

1. **Clone or Download the Repository**
   Make sure all files are placed in a folder (you should see `package.json`, `server.js`, and the `public` folder).

2. **Install Dependencies**
   Open your terminal in the project directory and run:
   ```bash
   npm install
   ```

3. **Configure Environment Variables**
   - Create a new file named `.env` in the root of your project directory.
   - You can copy the contents of `.env.example` as a starting point.
   - Add your API key to the `.env` file:
     ```env
     GEMINI_API_KEY="your_actual_api_key_here"
     ```
   *(Note: Never share or commit your `.env` file!)*

## Running the App

Start the backend server by running:
```bash
npm start
```
By default, the server will run on `http://localhost:3000`. 
Open your web browser and navigate to that address to start chatting!

## Project Structure

- `server.js`: The Express backend that serves the HTML UI and securely talks to the AI model.
- `public/index.html`: The fully-contained frontend (HTML, CSS, logic) for the chat interface.
- `package.json`: Contains project metadata and dependencies.
- `.env.example`: A template for environment variables.
"# simple-chatbot-private-ai-systems" 
