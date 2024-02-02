# Virtual window backend

This is a demo application for the demonstration of smart triggers.

## Installation

Start the Docker container with the following command:
```bash
docker compose up -d
```

You can then establish a websocket connection via ws://localhost:8765 to obtain information about the opening status of the window.

You can open the window with POST localhost:5000/open and close the window again with POST localhost:5000/close.