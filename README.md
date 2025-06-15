# car-service-ai
A voice agent for car servicing platform that create user profile and book appointment.
## Features

- Conversational voice agent for car service platforms
- VIN(Vehicle Identification Number)-based car information retrieval from the database
- User profile creation for new users without VIN
- Car service appointment booking via voice interaction
- Real-time voice-to-text transcription for user visibility

## Technology Stack

- **Backend:** Flask, LiveKit (for real-time voice agent)
- **Frontend:** Vite, React

## How It Works

1. **Voice Interaction:** Users interact with the agent using voice.
2. **VIN Handling:**
  - If the user provides a VIN, the agent retrieves car information from the database.
  - If the user does not have a VIN, the agent guides the user to create a profile, collects VIN and car info.
3. **Appointment Booking:** The agent books a car service appointment based on the conversation.
4. **Text Display:** All voice interactions are transcribed and displayed to the user in real time.

## Getting Started

### Prerequisites

- Node.js & npm
- Python 3.x
- LiveKit server

### Backend Setup

```bash
cd backend
pip install -r requirements.txt
python app.py
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### LiveKit Setup

Refer to [LiveKit documentation](https://docs.livekit.io/) for server setup.

