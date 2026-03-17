<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RAG Assistant for BI Engineering</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 40px;
            background-color: #f9f9f9;
            color: #333;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        .container {
            background: #fff;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.05);
        }
        ul {
            margin-left: 20px;
        }
        code {
            background: #eee;
            padding: 5px 8px;
            border-radius: 5px;
        }
        .section {
            margin-bottom: 30px;
        }
    </style>
</head>
<body>

<div class="container">

    <h1>🧠 RAG Assistant for BI Engineering</h1>

    <p>
        A <strong>Retrieval-Augmented Generation (RAG) Assistant</strong> designed to support daily work as a BI Engineer by enabling fast and accurate retrieval of internal knowledge.
    </p>

    <div class="section">
        <h2>🚀 Overview</h2>
        <p>This assistant helps retrieve:</p>
        <ul>
            <li>📊 Data sources (datasets)</li>
            <li>👥 Contacts (people & emails)</li>
            <li>🧾 SQL queries</li>
            <li>📁 Work-related documentation</li>
        </ul>
    </div>

    <div class="section">
        <h2>🏗️ Architecture</h2>
        <p>
            User Question → Retriever → Context → Prompt → LLM → Answer
        </p>
        <ul>
            <li>Load internal documents</li>
            <li>Split into smaller chunks</li>
            <li>Convert text into embeddings</li>
            <li>Store in vector database</li>
            <li>Retrieve relevant information</li>
            <li>Generate answer using LLM</li>
        </ul>
    </div>

    <div class="section">
        <h2>📂 Project Structure</h2>
        <ul>
            <li><code>knowledge-base/</code> → Internal text files</li>
            <li><code>vector_db/</code> → Vector database</li>
            <li><code>app</code> → Main application</li>
            <li><code>.env</code> → API key configuration</li>
        </ul>
    </div>

    <div class="section">
        <h2>⚙️ Setup</h2>
        <p>Install required dependencies and configure your environment variables.</p>
        <p>Add your API key inside:</p>
        <code>.env</code>
    </div>

    <div class="section">
        <h2>📥 Data Preparation</h2>
        <p>
            Add your internal knowledge files into the <code>knowledge-base/</code> folder.
        </p>
        <p>Supported format:</p>
        <ul>
            <li>.txt files (UTF-8)</li>
        </ul>
    </div>

    <div class="section">
        <h2>🧠 How It Works</h2>
        <ul>
            <li>Documents are processed and indexed</li>
            <li>Relevant data is retrieved based on the question</li>
            <li>LLM generates a context-based answer</li>
            <li>If no answer is found → "I don't know"</li>
        </ul>
    </div>

    <div class="section">
        <h2>🖥️ User Interface</h2>
        <p>
            The system provides a simple interface where users can:
        </p>
        <ul>
            <li>Enter a question</li>
            <li>Receive a clear and concise answer</li>
        </ul>
    </div>

    <div class="section">
        <h2>✨ Features</h2>
        <ul>
            <li>🔍 Smart document retrieval</li>
            <li>⚡ Fast semantic search</li>
            <li>🧠 Context-aware answers</li>
            <li>🔒 Reduced hallucination</li>
            <li>💾 Persistent knowledge storage</li>
        </ul>
    </div>

    <div class="section">
        <h2>📌 Example Use Cases</h2>
        <ul>
            <li>What datasets do I use for analysis?</li>
            <li>Give me a SQL query for reporting</li>
            <li>Find a colleague's email</li>
            <li>Retrieve system connection details</li>
        </ul>
    </div>

    <div class="section">
        <h2>🧩 Future Improvements</h2>
        <ul>
            <li>Support PDF and Excel files</li>
            <li>Add OCR for images</li>
            <li>Implement authentication</li>
            <li>Deploy as a standalone desktop app</li>
            <li>Support offline local LLM</li>
        </ul>
    </div>

    <div class="section">
        <h2>👩‍💻 Author</h2>
        <p>
            <strong>Maram Al-Sharqawe</strong><br>
            BI Engineer | Data Scientist | AI & Cybersecurity Enthusiast
        </p>
    </div>

    <div class="section">
        <h2>⭐ Notes</h2>
        <p>
            This project is designed to improve productivity and knowledge retrieval in real-world BI environments.
        </p>
    </div>

</div>

</body>
</html>
