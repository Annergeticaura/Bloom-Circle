<h1>Bloom Circle</h1>
    <p>
        Welcome to <strong>Bloom Circle</strong>, a Flask-based chat application with multiple community rooms.
        This app allows users to join specific rooms and engage in discussions. The application is designed with
        a clean UI, community-focused chat rooms, and real-time communication.
    </p>

    <h2>Features</h2>
    <ul>
        <li><strong>Community Rooms:</strong> Predefined rooms that users can join by simply clicking on the room name.</li>
        <li><strong>Real-Time Chat:</strong> Send and receive messages in real-time using Flask and SocketIO.</li>
        <li><strong>Interactive UI:</strong> A friendly interface designed with custom styles and animations.</li>
    </ul>

    <h2>Tech Stack</h2>
    <ul>
        <li><strong>Backend:</strong> Flask, Flask-SocketIO</li>
        <li><strong>Frontend:</strong> HTML, CSS (with animations), Bootstrap</li>
        <li><strong>Real-Time Communication:</strong> SocketIO</li>
    </ul>

    <h2>Setup Instructions</h2>
    <ol>
        <li>
            <p><strong>Clone the repository:</strong></p>
            <pre><code>git clone https://github.com/yourusername/bloom-circle.git
cd bloom-circle
            </code></pre>
        </li>
        <li>
            <p><strong>Create a virtual environment (recommended):</strong></p>
            <pre><code>python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
            </code></pre>
        </li>
        <li>
            <p><strong>Install the required packages:</strong></p>
            <pre><code>pip install -r requirements.txt
            </code></pre>
        </li>
        <li>
            <p><strong>Run the Flask application:</strong></p>
            <pre><code>flask run --host=0.0.0.0 --port=5000
            </code></pre>
            <p>The <code>--host=0.0.0.0</code> option allows the app to be accessible to other devices on the same network.</p>
        </li>
        <li>
            <p><strong>Access the app:</strong></p>
            <p>Open a browser and navigate to <code>http://&lt;your-local-ip&gt;:5000</code> to view the app.</p>
        </li>
    </ol>

    <h2>Usage</h2>
    <ol>
        <li>On the home page, enter a username and select a room by either typing its name or clicking on one of the room options from the community list.</li>
        <li>Engage in conversations and see messages update in real-time.</li>
        <li>Explore the different rooms and connect with others!</li>
    </ol>

    <h2>Project Structure</h2>
    <pre><code>bloom-circle/
│
├── static/
│   ├── css/
│   │   └── style.css    # Custom styles for the application
│   
├── templates/
│   ├── base.html        # Base template
│   ├── home.html        # Home page template
│   └── room.html        # Room-specific chat page
├── app.py               # Main Flask application
└── README.md            # Project documentation
    </code></pre>

    <h2>Screenshots</h2>
    <p><em>(Optional: Add screenshots of your UI to give a quick preview of the application.)</em></p>

    <h2>Contributing</h2>
    <ol>
        <li>Fork the project.</li>
        <li>Create your feature branch (<code>git checkout -b feature/awesome-feature</code>).</li>
        <li>Commit your changes (<code>git commit -m 'Add some awesome feature'</code>).</li>
        <li>Push to the branch (<code>git push origin feature/awesome-feature</code>).</li>
        <li>Open a pull request.</li>
    </ol>

    <h2>License</h2>
    <p>This project is licensed under the MIT License. See the <code>LICENSE</code> file for details.</p>

    <h2>Acknowledgments</h2>
    <ul>
        <li>Thanks to the Flask and SocketIO communities for their excellent libraries and support.</li>
        <li>Special shoutout to anyone who provided feedback or contributed to the project!</li>
    </ul>
