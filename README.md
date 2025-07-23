# NPTEL Helper AI – Chrome Extension

## 🔍 Overview

**NPTEL Helper AI** is a Chrome extension built to enhance the learning experience on the NPTEL platform. It integrates an AI-powered chatbot and bookmarking features directly into the NPTEL website. The chatbot intelligently assists with quiz questions, programming assignments, and other relevant content, while filtering out unrelated queries.

---

## 🛠️ Technologies Used

- **Frontend**: HTML, CSS, JavaScript  
- **Browser Integration**: Chrome Extension API  
- **Data Persistence**: Local Storage API  
- **AI Backend**: Gemini AI API

---

## ✨ Key Features

### 💬 AI Chatbot

1. **Toggle Chatbot Button**  
   - Enables or disables the chatbot on any NPTEL page.
   - UI includes a message input area, image attachment support, and a send button.

2. **Draggable Interface**  
   - The chatbot window is fully movable, allowing flexible positioning on the page.

3. **Multi-Modal Input Support**  
   - Accepts both text and image inputs, including combined queries.

4. **Context-Aware Responses**  
   - Only responds to relevant NPTEL-related queries; unrelated questions are ignored.

5. **Persistent Chat History**  
   - Chat history is stored per webpage using Local Storage.
   - History is retained even when the chatbox is closed and reopened.

6. **Additional Chatbox Tools**  
   - **AI Help Button**: Analyzes current page content to provide specific help.
     - On quiz pages, it offers solution assistance.
     - On programming assignment pages, it provides explanations, code suggestions, and algorithms.
   - **Delete History**: Clears chat history for the current page.
   - **Close Button**: Hides the chatbot from view.

---

### 🔖 Bookmarking System

7. **Bookmark Button (Programming Assignment Pages Only)**  
   - Saves the page as a bookmark.
   - If already bookmarked, displays an "Existing Bookmark" label.

8. **Bookmark Viewer (Popup)**  
   - Accessed by clicking the extension icon in Chrome.
   - Displays a list of all saved bookmarks with the following controls:
     - **Play Button**: Opens the bookmarked page.
     - **Delete Button**: Removes the selected bookmark.
     - **AI Help Button**: Automatically loads the page, opens the chatbot, and offers relevant AI assistance.

---

## 🚀 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Nptel-Chrome-Extension-Ai-Helper.git
2. Open Chrome and go to `chrome://extensions/`.
3. Enable "Developer Mode" (toggle at the top-right corner).
4. Click "Load unpacked" and select the cloned repository folder.
5. The extension is now installed and ready to use.

## Usage
- Navigate to an NPTEL webpage.
- Click the chatbot toggle button to interact with the AI assistant.
- Use the AI Help button for webpage-based assistance.
- Bookmark programming assignment pages and manage bookmarks from the extension popup.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Demo Video :

https://drive.google.com/file/d/1znDCr5wz8tGWT19-wcll6YLgu5rbxdbW/view?usp=sharing

https://github.com/user-attachments/assets/0c2c688e-b8a7-4854-8155-0967f972c0e8

## Output

![Chatbot](https://github.com/user-attachments/assets/6b48edac-2bac-42c7-82bc-c2924e524c82)

![Chatbot with Response](https://github.com/user-attachments/assets/128f91df-c5ed-4582-9fcf-2dd8dee1ec50)

![ChatBot view](https://github.com/user-attachments/assets/40ea2ec5-b785-44a7-a308-d66a9b38e557)

![Bookmark Popup](https://github.com/user-attachments/assets/bbe868c9-1619-40f3-a1df-e189c47ec28b)

![Bookmark and Chatbot Button](https://github.com/user-attachments/assets/aa6b16c1-f142-4f0a-92fa-5f6c20637af8)

