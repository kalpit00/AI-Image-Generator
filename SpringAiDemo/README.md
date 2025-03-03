# AI Application Backend

A Spring Boot application that integrates with OpenAI's services to provide AI capabilities through RESTful APIs. Built with Spring AI, this backend serves as the intelligence layer for chat interactions, image generation, and recipe creation.

## Features

- 🤖 **OpenAI Integration**: Direct integration with OpenAI's GPT and DALL-E models
- 🔄 **RESTful APIs**: Clean API endpoints for all AI functionalities
- 🛠️ **Configurable**: Easy configuration through application properties
- 📊 **Scalable Architecture**: Built on Spring Boot's robust framework
- 🔐 **Security Ready**: Prepared for API key management and security measures

## Tech Stack

- Java 21
- Spring Boot 3.3
- Spring AI 1.0.0-M1
- Maven

## Prerequisites

- JDK 21
- Maven
- OpenAI API key

## Getting Started

1. Configure OpenAI API key:
   Create `application.properties` in `src/main/resources/`:

   ```properties
   spring.ai.openai.api-key=your-api-key-here
   ```

2. Build the project:

   ```bash
   ./mvnw clean install
   ```

3. Run the application:
   ```bash
   ./mvnw spring-boot:run
   ```

## API Endpoints

### Chat API

```http
GET /ask-ai?prompt=your-prompt-here
```

### Image Generation API

```http
GET /generate-image
Parameters:
- prompt (required): Image description
- quality (optional): Image quality (default: "hd")
- n (optional): Number of images (default: 1)
- width (optional): Image width (default: 1024)
- height (optional): Image height (default: 1024)
```

### Recipe Creator API

```http
GET /recipe-creator
Parameters:
- ingredients (required): Available ingredients
- cuisine (optional): Preferred cuisine (default: "any")
- dietaryRestriction (optional): Dietary restrictions
```

## Project Structure

```
src/
  ├── main/
  │   ├── java/
  │   │   └── com/ai/SpringAiDemo/
  │   │       ├── controllers/    # REST controllers
  │   │       ├── services/       # Business logic
  │   │       └── config/         # Configuration classes
  │   └── resources/
  │       └── application.properties
  └── test/                       # Test classes
```

## Configuration

The application can be configured through `application.properties`:

```properties
# Server Configuration
server.port=8080

# OpenAI Configuration
spring.ai.openai.api-key=your-api-key
spring.ai.openai.model=gpt-4
```

## Development

### Building

```bash
./mvnw clean install
```

### Testing

```bash
./mvnw test
```

### Running Locally

```bash
./mvnw spring-boot:run
```

## Contributing

Please read the main project README for contribution guidelines.
