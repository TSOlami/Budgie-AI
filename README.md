# Budgie AI - Mental Health Support Chatbot

Budgie AI is a friendly mental health coach that provides emotional support through personalized AI conversations. It offers various AI personalities and voice interaction capabilities.

## Technologies Used

### Frontend
- **Next.js 13**: Powers the React-based web application
- **React**: UI components and state management
- **CSS Modules**: Component-level styling with .module.css files
- **localStorage API**: Saves chat history and user preferences
- **React Icons**: Interface icons like microphone and stop buttons

### Backend
- **Django 5.0.7**: Backend framework handling server logic
- **Django REST Framework**: API endpoints for chat functionality
- **AI71 API**: Provides chat completions using the Falcon-180B model
- **SQLite**: Simple database storage

### AI & Voice Features
- **OpenAI Whisper API**: Converts speech to text for voice input
- **OpenAI TTS-1-HD API**: Converts AI responses to voice output
- **MediaRecorder API**: Records user's voice input

### Deployment
- **Vercel**: Hosts the Next.js frontend
- **Render.com**: Hosts the Django backend

## Features

### AI Personalities
Choose from multiple AI personalities including:
- **Empathetic**: Great listener with knowledge in emotional intelligence and therapy
- **Motivator**: Encouraging personality that focuses on positive reinforcement
- **Wise Sage**: Provides thoughtful guidance and philosophical insights
- **Comedian**: Uses humor to help see situations in a lighter way
- **Bestie**: Your supportive friend who's always there to listen

### Voice Interaction
- **Voice Input**: Speak directly to Budgie by clicking the microphone icon
- **Voice Output**: Hear Budgie's responses read aloud in your chosen voice
- **Voice Selection**: Choose from multiple voice options (Alloy, Echo, Fable, Onyx, Nova, Shimmer)

### Chat Features
- **Persistent Chat**: Conversations are saved in your browser
- **Clear Chat**: Option to start fresh conversations
- **Message History**: Review your conversation history
- **Text/Voice Input**: Flexibility to type or speak your messages

## Getting Started

### Frontend Setup
1. Navigate to the frontend directory: `cd frontend`
2. Install dependencies: `npm install`
3. Create a `.env.local` file with:
   ```
   NEXT_PUBLIC_BACKEND_URL=http://localhost:8000/api
   NEXT_PUBLIC_OPENAI_API_KEY=your_openai_api_key
   ```
4. Start the development server: `npm run dev`
5. Open [http://localhost:3000](http://localhost:3000) in your browser

### Backend Setup
1. Create a virtual environment (optional)
2. Navigate to the backend directory: `cd backend`
3. Install requirements: `pip install -r requirements.txt`
4. Create a `.env` file with:
   ```
   AI71_API_KEY=your_ai71_api_key
   SECRET_KEY=your_django_secret_key
   ```
5. Run the server: `python manage.py runserver`

## How It Works

1. **Select a Personality**: Choose which AI personality you want to chat with
2. **Start Chatting**: Type messages or use voice input by clicking the microphone
3. **Receive Responses**: Get thoughtful text responses or listen to them with the voice feature
4. **Change Voices**: Select different voice options for the AI responses

Budgie AI uses advanced AI models to provide supportive, personalized conversations while maintaining a warm, human-like tone. All conversations happen in your browser for privacy.

## Contributors
- Developer: dev_teejay, manjee_minhal, fatima_ibrahim

## License
This project is privately licensed.
