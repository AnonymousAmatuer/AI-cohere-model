<!DOCTYPE html>
<html>
<head>
    <title>AI Chatbot - README</title>
</head>
<body>
    <h1>📖 <b>AI Chatbot</b></h1>
    <p>Welcome to the AI Chatbot project! This application is built using the <b>Cohere</b> API for natural language processing, enabling advanced conversational capabilities.</p>

    <h2>🚀 <b>Features</b></h2>
    <ul>
        <li>Intelligent and context-aware responses.</li>
        <li>Seamless integration with Cohere's API.</li>
        <li>User-friendly interface for smooth interaction.</li>
        <li>Highly customizable and extensible.</li>
    </ul>

    <h2>📂 <b>Project Structure</b></h2>
    <pre>
    ├── chatbot.py         <!-- Main application file -->
    ├── config.py          <!-- Configuration settings -->
    ├── requirements.txt   <!-- Dependencies -->
    ├── README.html        <!-- This README file -->
    └── dist/              <!-- Compiled executable (if using PyInstaller) -->
    </pre>

    <h2>⚙️ <b>Setup Instructions</b></h2>
    <p>Follow these steps to set up and run the chatbot locally:</p>
    <ol>
        <li><b>Clone the Repository:</b>
            <pre>git clone https://github.com/your-repo-name/ai-chatbot.git</pre>
        </li>
        <li><b>Navigate to the Project Directory:</b>
            <pre>cd ai-chatbot</pre>
        </li>
        <li><b>Install Dependencies:</b>
            <pre>pip install -r requirements.txt</pre>
        </li>
        <li><b>Set Up Environment Variables:</b>
            <p>Create a <code>.env</code> file in the project directory and add your Cohere API key:</p>
            <pre>
COHERE_API_KEY=your-cohere-api-key
            </pre>
        </li>
        <li><b>Run the Chatbot:</b>
            <pre>python chatbot.py</pre>
        </li>
    </ol>

    <h2>📜 <b>Usage</b></h2>
    <p>Once the chatbot is running, you can interact with it through the terminal or GUI interface. Start typing your queries and get responses in real-time!</p>

    <h2>💻 <b>Building an Executable</b></h2>
    <p>To create a standalone executable:</p>
    <ol>
        <li><b>Install PyInstaller:</b>
            <pre>pip install pyinstaller</pre>
        </li>
        <li><b>Run PyInstaller:</b>
            <pre>pyinstaller --onefile chatbot.py</pre>
        </li>
        <li><b>Locate the Executable:</b>
            <p>The `.exe` file will be in the <code>dist</code> folder.</p>
        </li>
    </ol>

    <h2>🔒 <b>Security Notes</b></h2>
    <ul>
        <li>Ensure your <b>Cohere API key</b> is not hardcoded in the application.</li>
        <li>Use <b>environment variables</b> or secret management tools to secure sensitive information.</li>
        <li>If distributing the app, obfuscate the code to protect credentials.</li>
    </ul>

    <h2>🛠️ <b>Customization</b></h2>
    <p>You can easily modify the chatbot’s behavior by:</p>
    <ul>
        <li>Editing the prompt structure in <code>chatbot.py</code>.</li>
        <li>Adjusting API parameters for Cohere's endpoints.</li>
        <li>Integrating additional functionality (e.g., GUI, database support).</li>
    </ul>

    <h2>📜 <b>License</b></h2>
    <p>This project is licensed under the <b>MIT License</b>. See the <code>LICENSE</code> file for details.</p>

    <p>Happy Coding! 🎉</p>
</body>
</html>
