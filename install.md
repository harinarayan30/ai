Installation Guide

Follow these steps to set up and run the AI Multi-Modal Interaction System locally.

🖥️ Prerequisites

Make sure you have the following installed:

Node.js (v20 or above)
npm or yarn
MongoDB (local or cloud)
Git
📥 1. Clone the Repository
git clone https://github.com/harinarayan30/ai-interaction-system-clean.git
cd ai-interaction-system-clean
📦 2. Install Dependencies
🔹 Frontend Setup
cd frontend
npm install
🔹 Backend Setup
cd ../backend
npm install
🔐 3. Environment Variables

Create a .env file inside the backend folder:

OPENAI_API_KEY=your_openai_api_key
MONGO_URI=your_mongodb_connection_string

⚠️ Do not share this file publicly.

▶️ 4. Run the Application
Start Backend
cd backend
node server.js
Start Frontend
cd frontend
npm run dev
🌐 5. Access the Application
Frontend: http://localhost:5173
Backend: http://localhost:5000
🧪 Optional: Test APIs

You can test backend APIs using tools like Postman.

❗ Troubleshooting
Ensure correct Node.js version (recommended v20 LTS)

Delete node_modules and reinstall if errors occur:

rm -rf node_modules package-lock.json
npm install
Check .env variables are correctly set
