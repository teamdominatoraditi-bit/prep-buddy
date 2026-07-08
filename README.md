# Prep Buddy

A client-aware candidate preparation tool for CSMs (Client Services Managers) that helps streamline the interview preparation workflow.

## Features

- **Stage 1 - Prep the CSM**: Generate comprehensive prep briefings with match scores, role snapshots, and talking points
- **Stage 2 - Prep the Candidate**: Create candidate-ready prep emails with interview tips
- **Stage 3 - Debrief**: Analyze post-interview debriefs and learn client patterns

## Tech Stack

- Pure HTML/CSS/JavaScript (no framework dependencies)
- Docker-ready with nginx:alpine
- Demo mode included (no API key required)

## Quick Start

### Option 1: Open directly
Simply open `prep_buddy.html` in your browser.

### Option 2: Docker
```bash
# Build the Docker image
docker build -t prep-buddy .

# Run the container
docker run -d -p 8080:80 prep-buddy

# Open in browser
# http://localhost:8080
```

## Usage

1. Fill in the client name, job description, and candidate resume
2. Click "Generate prep briefing" to see the analysis
3. Continue through stages 2 and 3 as needed
4. All data is saved locally in your browser

## License

MIT License