# AI-Powered Application Platform

A modern web application that leverages Spring AI and React to provide multiple AI-powered features including chat interactions, image generation, and recipe creation.

## Features

- 💬 **AI Chat Interface**: Engage in conversations with AI using OpenAI's models
- 🎨 **Image Generation**: Create custom images with adjustable parameters
- 🍳 **Recipe Creator**: Generate recipes based on available ingredients and dietary preferences

## Project Structure

The project consists of two main components:

- `spring-ai-demo-react/`: React-based user interface
- `SpringAiDemo/`: Spring Boot application with AI integration

## Prerequisites

- Java 21
- Node.js 18+ and npm
- OpenAI API key

## Quick Start

1. Clone the repository:

   ```bash
   git clone https://github.com/kalpit00/AI-Image-Generator.git
   ```

2. Set up the backend:

   ```bash
   cd SpringAiDemo
   # Set your OpenAI API key in application.properties
   ./mvnw spring-boot:run
   ```

3. Set up the frontend:

   ```bash
   cd spring-ai-demo-react
   npm install
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Environment Variables

Backend:

- `OPENAI_API_KEY`: Your OpenAI API key

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
