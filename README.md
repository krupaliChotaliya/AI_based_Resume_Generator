# AI-Powered Resume Builder

This is a **web application** that allows users to generate professional resumes simply by providing a prompt. Users can modify the generated resume details and download the final version to their system.

## Features

* Generate a complete resume using AI by entering a prompt.
* Edit and customize the generated details as needed.
* Download the final resume in a preferred format.
* Fast and user-friendly interface.

## Tech Stack

* **Backend**: Spring Boot (for REST API development)
* **AI Integration**: Spring AI with Ollama DeepSeek R1
* **Frontend**: HTML, CSS, JavaScript

## How It Works

1. The user enters a prompt describing their skills, experience, and career goals.
2. The backend sends this prompt to **Ollama DeepSeek R1** through Spring AI.
3. The AI processes the information and generates a professional resume.
4. The user can review and edit the resume before downloading it.

## Requirements

* Java 17 or higher
* Maven
* Ollama setup with DeepSeek R1 model installed
* Web browser for the frontend

## Installation & Setup

1. Clone the repository:

   ```bash
   git clone <your-repo-link>
   cd ai-powered-resume-builder
   ```
2. Configure **Ollama DeepSeek R1** on your local or remote environment.
3. Update application properties in `application.properties` with your AI API details.
4. Build and run the backend:

   ```bash
   mvn spring-boot:run
   ```
5. Open the `index.html` file in your browser to access the frontend.

## Future Enhancements

* Support for multiple resume templates.
* Export to PDF with styling options.
* Multi-language resume generation.

