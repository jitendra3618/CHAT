<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Multiuser Chat App - README</title>
</head>
<body>

<h1>Multiuser Chat App</h1>

<p>A real-time chat application that allows multiple users to chat simultaneously, including group chat functionality. The application is built using HTML, CSS, JavaScript, MongoDB, Express.js, Node.js, and Socket.io. CORS (Cross-Origin Resource Sharing) is also implemented to handle cross-origin requests.</p>


![Screenshot (70)](https://github.com/jitendra3618/CHAT-APP/assets/137607500/af722b9b-4091-42d3-a583-35e9d67677e4)

<h2>Features</h2>

<ul>
  <li>Real-time messaging: Instantly chat with multiple users.</li>
  <li>Group chat: Create and join group conversations.</li>
  <li>User authentication: Register and log in to access the chat features.</li>
  <li>Persistent data: Messages are stored in a MongoDB database for future reference.</li>
  <li>Responsive design: The chat interface is designed to work seamlessly across devices.</li>
</ul>

<h2>Tech Stack</h2>

<ul>
  <li><strong>Frontend</strong>: HTML, CSS, JavaScript</li>
  <li><strong>Backend</strong>: Node.js, Express.js</li>
  <li><strong>Database</strong>: MongoDB (Mongoose ORM)</li>
  <li><strong>Real-time communication</strong>: Socket.io</li>
  <li><strong>Cross-Origin Resource Sharing</strong>: CORS</li>
</ul>

<h2>Installation</h2>

<ol>
  <li>Clone the repository:</li>
</ol>

<pre><code>git clone https://github.com/your-username/multiuser-chat-app.git
cd multiuser-chat-app
</code></pre>

<ol start="2">
  <li>Install dependencies:</li>
</ol>

<pre><code>npm install
</code></pre>

<ol start="3">
  <li>Set up MongoDB:</li>
</ol>

<p>- Ensure MongoDB is installed and running on your system.<br>
- Update the MongoDB URI in <code>config/config.js</code>.</p>

<ol start="4">
  <li>Start the server:</li>
</ol>

<pre><code>npm index.js
</code></pre>

<p>5. Access the application in your browser at <code>http://localhost:3000</code>.</p>

<h2>Usage</h2>

<ol>
  <li>Register a new account or log in if you already have one.</li>
  <li>Start chatting with other users or create/join group chats.</li>
</ol>

<h2>Directory Structure</h2>

<pre>
multiuser-chat-app/
│
├── config/
│   ├── config.js        # Configuration file (MongoDB URI, etc.)
│
├── public/
│   ├── css/
│   │   └── styles.css   # CSS styles for the frontend
│   ├── js/
│   │   └── script.js    # JavaScript for client-side functionality
│   └── index.html       # Main HTML file
│
├── routes/
│   └── chat.js          # Route for chat functionality
│
├── models/
│   └── user.js          # User model for MongoDB
│
├── package.json         # Node.js dependencies and scripts
├── server.js            # Express.js server setup
└── README.md            # Project README file
</pre>

<h2>Dependencies</h2>

<ul>
  <li>Express.js: Fast, unopinionated, minimalist web framework for Node.js.</li>
  <li>Socket.io: Real-time, bidirectional communication library.</li>
  <li>Mongoose: MongoDB object modeling for Node.js.</li>
  <li>CORS: Cross-Origin Resource Sharing middleware for Express.js.</li>
</ul>

<h2>Contributing</h2>

<p>Contributions are welcome! If you'd like to improve this project, please fork the repository and submit a pull request with your changes.</p>

<h2>License</h2>

<p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>

![Screenshot (70)](https://github.com/jitendra3618/CHAT-APP/assets/137607500/4d6c03ce-43fe-4505-889c-50584545e0a2)


</body>
</html>
