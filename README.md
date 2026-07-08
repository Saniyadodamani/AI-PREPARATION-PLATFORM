# AI Preparation Platform

An AI-powered interview preparation platform that helps students prepare for software engineering interviews through DSA practice, theory modules, system design resources, progress tracking, and AI-assisted learning.

## Features

- DSA question practice
- AI-assisted learning
- Theory preparation
- System Design preparation
- User authentication
- Progress tracking dashboard
- Responsive user interface

## Tech Stack

### Frontend
- React.js
- Vite
- CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### AI
- Groq API

## Installation

### Clone the repository

```bash
git clone https://github.com/Saniyadodamani/AI-PREPARATION-PLATFORM.git
```

### Install dependencies

```bash
npm install
cd client
npm install
cd ../server
npm install
```

### Create environment file

Create a `server/.env` file.

Example:

```env
MONGO_URI=your_mongodb_connection_string
GROQ_API_KEY=your_groq_api_key
PORT=5000
FRONTEND_URL=http://localhost:5173
```

### Run the project

Backend

```bash
cd server
npm start
```

Frontend

```bash
cd client
npm run dev
```

## Folder Structure

```
client/
server/
README.md
package.json
```

## Future Improvements

- Company-wise interview questions
- Mock interview support
- Analytics dashboard
- AI feedback on coding solutions
- Performance reports
