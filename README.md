# Smash Karts

Smash Karts is a web-based multiplayer game built using JavaScript, HTML, and Firebase. The project integrates various SDKs and utilities to enhance gameplay, analytics, and advertising.

## Features

- Multiplayer gameplay with Firebase integration.
- Poki SDK integration for ads and analytics.
- Custom utilities for handling backlinks and browser compatibility.
- Responsive design for mobile, tablet, and desktop platforms.

## Folder Structure

/workspaces/SmashKarts ├── js/ │ ├── slopegame-gitlab-io.js │ ├── ubg44.js │ ├── ubg98.js │ ├── analytics_ubg_v1_4.js │ ├── ubg235_client_v1_2.js │ ├── main.js │ ├── auth.js ├── patch/ │ ├── js/ │ │ ├── poki-sdk-core-v2.260.1.js │ │ ├── poki-sdk.js │ │ ├── poki-sdk-o.js │ │ ├── poki-unity.js │ │ ├── poki-utils.js ├── index.html


## Prerequisites

To run the application, ensure you have the following installed:

- A modern web browser (e.g., Chrome, Firefox, Edge).
- A local or remote web server (e.g., Apache, Nginx, or a Node.js-based server).
- Internet access for Firebase and Poki SDK dependencies.

## How to Run the Application

### Option 1: Using a Local Web Server

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/SmashKarts.git
   cd SmashKarts

   python3 -m http.server

http://localhost:8000/index.html
