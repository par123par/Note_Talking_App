# Note-Taking App

A simple note-taking app built with React, Node.js, Express, and MongoDB.

## Setup

1. Install Node.js and MongoDB.
2. Clone the repo.
3. Install dependencies:
   - Frontend: `cd client && npm install`
   - Backend: `cd server && npm install`
4. Set up MongoDB Atlas and add `MONGODB_URI` to a `.env` file in the `server` folder.
5. Run the app:
   - Backend: `cd server && npm start`
   - Frontend: `cd client && npm start`

## Deployment

Deploy on Render:
- Push to GitHub.
- Create a Web Service on Render, connect to the repo.
- Set `MONGODB_URI` in Render’s environment variables.
- Set build command: `cd client && npm install && npm run build && cd ../server && npm install`
- Set start command: `node server/server.js`#   N o t e _ T a l k i n g _ A p p  
 