# REAL-TIME-COLLABORATIVE-DOCUMENT-EDITOR
"COMPANY": CODTECH IT SOLUTION 
"NAME": SAKSHI PRAKASHRAO BERAD 
"INTERN ID": CT04DK226 
"DOMAIN":FULL STACK WEB DEVELOPMENT 
"DURATION": 4 WEEKS 
"MENTOR": NEELA SANTHOSH KUMAR

## Real-Time Collaborative Document Editor
A modern real-time collaborative document editor built with React.js, Node.js, Socket.IO, and MongoDB. Supports rich text editing and syncing across multiple users instantly.

## 🧩 Features
Real-time document editing
Rich text formatting using Quill.js
MongoDB for document storage
WebSockets (Socket.IO) for real-time collaboration
Easy to use and responsive interface

##  Project Structure
collab-doc-editor/
│
├── client/          # React.js frontend
│   └── src/
│       ├── components/
│       ├── App.js
│       ├── index.js
│       └── style.css
│
├── server/          # Node.js backend
│   ├── Document.js
│   └── index.js
│
├── README.md
## Technology use:
Frontend: React.js, Quill.js
Backend: Node.js, Express.js, Socket.IO
Database: MongoDB
## Create Folder Structure
bash
mkdir collab-doc-editor
cd collab-doc-editor
npx create-react-app client
mkdir server
cd server
npm init -y
npm install express mongoose cors socket.io
cd client
npm install react-router-dom quill socket.io-client uuid

## 🚀 How to Run the Project Locally
## 1. Clone the Repository
bash
git clone https://github.com/your-username/collab-doc-editor.git
cd collab-doc-editor
## 2. Install Backend Dependencies
bash
cd server
npm install
## 3. Start the Backend Server
bash
npm start
Make sure MongoDB is running locally on port 27017.
4. Install Frontend Dependencies
bash
cd ../client
npm install
5. Start the Frontend React App
bash
npm start
Then open: http://localhost:3000

## Screenshot:
![image](https://github.com/user-attachments/assets/93671abc-7098-437a-a34f-d6e25cea7770)
