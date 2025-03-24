Gather Town WebSocket Mute Zone
🔇 Automatically mutes users when they enter a specific zone in Gather Town using WebSockets

📌 Overview
This project uses the Gather Town WebSocket API to monitor player movements and automatically mute/unmute them when they enter/exit a predefined private space in a Gather Town environment.

🛠 Tech Stack
Node.js

WebSocket API

Gather Town API

🔧 Installation & Setup
1️⃣ Prerequisites
Ensure you have the following installed:

Node.js (v14+ recommended)

A Gather Town API Key (Get it from your Gather Town admin panel)

2️⃣ Clone the Repository
sh
Copy
Edit
git clone https://github.com/your-username/gather-town-mute-zone.git
cd gather-town-mute-zone
3️⃣ Install Dependencies
sh
Copy
Edit
npm install
4️⃣ Configure Environment Variables
Create a .env file in the root directory and add:

ini
Copy
Edit
GATHER_TOWN_API_KEY=your_api_key
SPACE_ID=your_space_id
5️⃣ Start the Server
sh
Copy
Edit
node server.js
🚀 How It Works
WebSocket Connection: Establishes a WebSocket connection with Gather Town.

Detects Player Movements: Monitors players' positions in real-time.

Applies Mute Logic: Automatically mutes/unmutes users based on their position in a predefined private space.
