# GitBrew Dashboard

A real-time monitoring dashboard for potion factory operations with AI-powered insights and analytics.

## Features

- **Real-time Monitoring**: Track cauldron levels, volumes, and fill rates in real-time
- **Network Map**: Visualize the potion transport network with animated courier movements
- **Historical Data**: View historical cauldron volume trends with interactive line charts
- **Discrepancy Detection**: Automatically identify suspicious activity in transport tickets
- **AI Assistant**: Conversational AI assistant powered by Google Gemini with speech-to-text and text-to-speech capabilities
- **Smart Alerts**: AI-powered recommendations and alerts for factory management
- **Route Optimization**: Analyze and optimize transport routes
- **Analytics**: Comprehensive analytics and insights

## Tech Stack

- **Framework**: Next.js 16.0.0
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **AI**: Google Gemini API
- **Text-to-Speech**: ElevenLabs API
- **Charts**: Recharts
- **UI Components**: Radix UI

## Getting Started

### Prerequisites

- Node.js 20 LTS or newer
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/MeddyT/gitBrew.git
cd gitBrew
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory:
```env
# Gemini API Key
GEMINI_API_KEY=your_gemini_api_key_here

# ElevenLabs API Key (optional, for text-to-speech)
ELEVENLABS_API_KEY=your_elevenlabs_api_key_here
```

4. Run the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
gitBrew/
├── app/                    # Next.js app directory
│   ├── api/               # API routes
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Main dashboard page
├── components/            # React components
│   ├── ai-assistant.tsx   # AI assistant widget
│   ├── cauldron-map.tsx  # Network map visualization
│   └── ui/               # UI components
├── data/                  # JSON data files
├── hooks/                 # Custom React hooks
├── lib/                   # Utility functions
└── public/                # Static assets
```

## API Keys Setup

### Gemini API Key
1. Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Create a new API key
3. Add it to your `.env` file as `GEMINI_API_KEY`

### ElevenLabs API Key (Optional)
1. Sign up at [ElevenLabs](https://elevenlabs.io)
2. Get your API key from the dashboard
3. Add it to your `.env` file as `ELEVENLABS_API_KEY`
4. Enable "Text to Speech: Access" and "Voices: Read" permissions

## Features in Detail

### AI Assistant
- Natural language queries about your data
- Speech-to-text input
- Text-to-speech responses
- Contextual help and troubleshooting
- Multi-language support

### Network Map
- Real-time visualization of cauldron network
- Animated courier movements
- Distance labels between nodes
- Topographical layout based on coordinates

### Historical Playback
- Individual line graphs for each cauldron
- Volume over time visualization
- Interactive tooltips with detailed information
- Static axes for consistent viewing

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[Add your license here]

## Author

MeddyT

---

*Built with ❤️ for potion factory monitoring*
