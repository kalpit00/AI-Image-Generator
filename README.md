# AI-Powered Application Platform

A modern web application that leverages Spring AI and React to provide multiple AI-powered features including chat interactions, image generation, and recipe creation.

## Features

- 💬 **AI Chat Interface**: Engage in conversations with AI using OpenAI's models
- 🎨 **Image Generation**: Create custom images with adjustable parameters
- 🍳 **Recipe Creator**: Generate recipes based on available ingredients and dietary preferences

## Project Structure

The project consists of two main components:

- `frontend/`: React-based user interface
- `backend/`: Spring Boot application with AI integration

## Prerequisites

- Java 21
- Node.js 18+ and npm
- OpenAI API key

## Quick Start

1. Clone the repository:

   ```bash
   git clone [your-repo-url]
   ```

2. Set up the backend:

   ```bash
   cd backend
   # Set your OpenAI API key in application.properties
   ./mvnw spring-boot:run
   ```

3. Set up the frontend:

   ```bash
   cd frontend
   npm install
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Environment Variables

Backend:

- `OPENAI_API_KEY`: Your OpenAI API key

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
