<h1>🧠 RAG Assistant for BI Engineering</h1>

<p>
A <b>Retrieval-Augmented Generation (RAG) Assistant</b> designed to support my daily work as a BI Engineer by enabling fast and accurate retrieval of internal knowledge.
</p>

<hr>

<h2>🚀 Overview</h2>
<ul>
  <li>📊 Data sources (datasets)</li>
  <li>👥 Contacts (people & emails)</li>
  <li>🧾 SQL queries</li>
  <li>📁 Work-related documentation</li>
</ul>

<hr>

<h2>🏗️ Architecture</h2>
<p>
User Question → Retriever → Context → Prompt → LLM → Answer
</p>

<ul>
  <li>Load internal documents</li>
  <li>Split into chunks</li>
  <li>Generate embeddings</li>
  <li>Store in vector database</li>
  <li>Retrieve relevant information</li>
  <li>Generate answer using LLM</li>
</ul>

<hr>

<h2>📂 Project Structure</h2>
<ul>
  <li><code>knowledge-base/</code> → Internal text files</li>
  <li><code>vector_db/</code> → Vector database</li>
  <li><code>app</code> → Main application</li>
  <li><code>.env</code> → API key configuration</li>
</ul>

<hr>

<h2>⚙️ Setup</h2>
<p>Install dependencies and configure your environment variables.</p>

<p><b>Environment Variable:</b></p>
<pre>
OPENAI_API_KEY=your_api_key_here
</pre>

<hr>

<h2>📥 Data Preparation</h2>
<p>Add your internal files into:</p>
<code>knowledge-base/</code>

<p>Supported format:</p>
<ul>
  <li>.txt files (UTF-8)</li>
</ul>

<hr>

<h2>🧠 How It Works</h2>
<ul>
  <li>Documents are processed and indexed</li>
  <li>Relevant data is retrieved based on the question</li>
  <li>LLM generates a context-based answer</li>
  <li>If no answer is found → <b>"I don't know"</b></li>
</ul>

<hr>

<h2>🖥️ User Interface</h2>
<ul>
  <li>Enter a question</li>
  <li>Receive a clear and concise answer</li>
</ul>

<hr>

<h2>✨ Features</h2>
<ul>
  <li>🔍 Smart retrieval</li>
  <li>⚡ Fast semantic search</li>
  <li>🧠 Context-aware answers</li>
  <li>🔒 Reduced hallucination</li>
  <li>💾 Persistent knowledge storage</li>
</ul>

<hr>

<h2>📌 Example Use Cases</h2>
<ul>
  <li>What datasets do I use for analysis?</li>
  <li>Give me a SQL query for reporting</li>
  <li>Find a colleague's email</li>
  <li>Retrieve system connection details</li>
</ul>

<hr>

<h2>🧩 Future Improvements</h2>
<ul>
  <li>Support PDF and Excel files</li>
  <li>Add OCR for images</li>
  <li>Authentication</li>
  <li>Deploy as desktop app</li>
  <li>Offline local LLM</li>
</ul>

<hr>

<h2>👩‍💻 Author</h2>
<p>
<b>Maram Al-Sharqawe</b><br>
BI Engineer | Data Scientist | AI & Cybersecurity Enthusiast
</p>

<hr>

<h2>⭐ Notes</h2>
<p>
This project improves productivity and knowledge retrieval in real BI environments.
</p>
