# AIcademy Frontend
AIcademy is an LMS platform similar to Udemy, where students can access high-quality courses at affordable rates, and teachers can earn by selling their courses. AIcademy acts as a bridge between teachers and students, offering unique AI features to enhance the learning experience.

Looking for project backend? [AIcademy backend repo](https://RosuMihaiAlexandru/aicademy-server-ffmpeg)

## Overview

### Project Specification
AIcademy leverages Retrieval Augmented Generation (RAG) to address students' doubts by referring to the context of the video, ensuring that answers are contextually relevant to the course content.

### Project Requirements
- **Frontend**: React with Vite for tooling
- **State Management**: Redux Toolkit, RTK Query for fetching and caching
- **Backend**: Express.js, Node.js, Nginx
- **Database**: MongoDB with Mongoose as ODM, Qdrant as Vector Database
- **Storage**: AWS S3 (V3 SDK for Node.js) for Adaptive Bitrate streaming for videos
- **Tech Stack**: MERN (MongoDB, Express.js, React, Node.js), Rabbitmq, Langchain

### Features
- AI-powered doubt resolution using RAG
- High-quality courses from world-class teachers
- Affordable pricing for students
- Secure video storage and Adaptive Bitrate streaming
- Efficient course upload process reducing server load


## Getting Started

To get started with the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/RosuMihaiAlexandru/aicademy-client-lms.git
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
Create a .env file in the root directory and add the necessary environment variables as specified in the .env.example file.

4. Start the development server:
   ```bash
   npm run dev
   ```

## Contributing
We welcome contributions to the AIcademy Backend project. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and commit them with a clear message.
4. Push your changes to your fork.
5. Submit a pull request detailing your changes.

## License
This project is licensed under the MIT License.
