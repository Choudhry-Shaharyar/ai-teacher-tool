# AI-Powered Teacher Transition Assistant

## Overview
When a homeroom teacher takes leave, there’s often no structured handover, leading to classroom disruptions, student confusion, and lost learning time. Our AI-powered solution automates the transition process by generating a comprehensive handover report within minutes, ensuring a seamless experience for both students and supply teachers.

## Key Features
- **AI-Powered Handover**: The homeroom teacher has a quick conversation with an AI chatbot, which collects essential information about the class, curriculum, student needs, allergies, and accommodations.
- **Instant Report Generation**: In under 5 minutes, the AI generates a detailed PDF handover report that can be emailed directly to the supply teacher.
- **Seamless Classroom Transition**: The supply teacher arrives fully prepared, ensuring students receive better supervision and uninterrupted learning.

## Technologies Used
- **React & TypeScript**: Provides a robust, scalable front-end framework with type safety.
- **OpenAI Realtime API**: Facilitates real-time conversation processing.
- **Web Audio API**: Captures and plays back audio interactions.
- **WavRecorder & WavStreamPlayer**: Custom utilities for handling audio recording and playback.
- **html2canvas & jsPDF**: Enables PDF generation of the handover report.
- **React-Feather**: Provides UI icons.
- **Sass**: Used for styling components.

## Core Components
The ConsolePage.tsx file is responsible for managing the conversation-based interface where teachers interact with the AI.

- **API Key Management**: Stores OpenAI API keys securely in local storage.
- **Audio Handling**: Uses WavRecorder and WavStreamPlayer for recording and playback.
- **Realtime Client**: Manages the conversation with OpenAI’s Realtime API.
- **Event Logging**: Logs interactions for debugging and reference.
- **Conversation Management**: Tracks and updates conversation history.
- **PDF Generation**: Captures conversation data and formats it into a professional handover report.

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/teacher-transition-ai.git
   cd teacher-transition-ai
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Run the development server:
   ```sh
   npm start
   ```
4. Provide your OpenAI API key when prompted.

## Future Enhancements
- **Mobile App Integration**: Make the tool accessible on mobile devices.
- **Advanced AI Insights**: Provide deeper analytics on student behavior and learning progress.

