# AI Application Frontend

A modern React-based frontend for interacting with AI services. This application provides an intuitive interface for chat interactions, image generation, and recipe creation.

## Features

- 🎯 **Interactive Chat**: Real-time conversations with AI
- 🖼️ **Image Generation Interface**: User-friendly controls for AI image creation
- 📝 **Recipe Generator**: Form-based interface for recipe creation
- 🎨 **Modern UI**: Clean and responsive design
- ⚡ **Real-time Updates**: Instant AI responses

## Tech Stack

- React 18
- Modern JavaScript (ES6+)
- CSS3 with modern styling
- Fetch API for backend communication

## Getting Started

1. Install dependencies:

   ```bash
   npm install
   ```

2. Start the development server:

   ```bash
   npm start
   ```

3. Build for production:
   ```bash
   npm run build
   ```

## Available Scripts

- `npm start`: Runs the app in development mode
- `npm test`: Launches the test runner
- `npm run build`: Builds the app for production
- `npm run eject`: Ejects from Create React App

## Project Structure

```
src/
  ├── components/     # React components
  ├── styles/        # CSS styles
  ├── services/      # API service calls
  ├── utils/         # Utility functions
  └── App.js         # Main application component
```

## Development

### Code Style

- Follow React best practices
- Use functional components with hooks
- Implement proper error handling
- Maintain clean and documented code

### API Integration

The frontend communicates with the Spring Boot backend through RESTful endpoints:

- `/ask-ai`: Chat interactions
- `/generate-image`: Image generation
- `/recipe-creator`: Recipe creation
