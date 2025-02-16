# CodeCollab AI

CodeCollab AI is a collaborative coding platform powered by AI, enabling seamless real-time code editing and communication among team members. It integrates Google Gemini AI for intelligent code suggestions and enhancements.

## Features
- **Real-time Collaboration**: Multiple users can edit code simultaneously.
- **AI-Powered Assistance**: Google Gemini AI provides intelligent code suggestions.
- **JWT Authentication**: Secure user sessions with JWT-based authentication.
- **Redis Caching**: Optimized performance with Redis session caching.
- **MERN Stack**: Built with MongoDB, Express, React, and Node.js.
- **Code Versioning**: Track and manage changes efficiently.
- **Integrated Chat**: Communicate with team members while coding.
- **WebContainers**: Run Node.js environments directly in the browser for an instant coding experience.
- **Syntax Highlighting & Linting**: Enhanced code readability and error detection.
- **Live Debugging**: Identify and fix issues in real time.

## Tech Stack
- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JWT
- **Caching**: Redis
- **AI Integration**: Google Gemini AI
- **Runtime**: WebContainers

## Installation
1. Clone the repository:
 
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables in a `.env` file:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   REDIS_URL=your_redis_url
   GOOGLE_GEMINI_API_KEY=your_api_key
   ```
4. Start the backend server:
   ```sh
   npm start
   ```
5. Start the frontend:
   ```sh
   npm run dev
   ```

## Usage
1. Sign up or log in using your credentials.
2. Create or join a coding session.
3. Collaborate with team members in real time.
4. Utilize AI-powered suggestions for code enhancement.

## Contributing
Contributions are welcome! Feel free to open issues and submit pull requests.

