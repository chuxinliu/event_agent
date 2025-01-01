# AI Networking Agent

An intelligent agent that processes professional networking events and automates follow-up actions. The agent analyzes event interactions and generates meaningful connections through smart processing of contacts and communications.

## Agent Capabilities

### Event Processing Pipeline
- **Pre-Event Analysis**: Initial context gathering and event preparation
- **Event Information Processing**: Intelligent note processing and data extraction
- **Post-Event Actions**: Automated analysis and follow-up generation

### Core AI Features
- Smart LinkedIn connection recommendations
- Automated CRM workflow generation
- Contact information extraction and processing
- Resume analysis and skill matching
- Points of commonality detection
- Intelligent response generation

## Setup

1. Clone the repository:
```bash
git clone https://github.com/chuxinliu/event_agent.git
cd event_agent
```

2. Install dependencies:
```bash
npm install
```

3. Configure agent:
```bash
cp .env.example .env
# Add API keys and AI model configurations
```

## Running the Agent

```bash
# Start agent in development mode
npm run dev

# Test agent behaviors
npm test
```

## Project Structure

```
/
├── event-processing/      # Agent's core processing logic
├── integrations/         # External service connections
└── utils/               # AI utilities and helpers
```
