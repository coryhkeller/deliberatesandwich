# Slack Sandwich Bot

🍞 **Slack Sandwich Bot** is a Node.js-based Slack bot that generates a random sandwich every day and posts it to your Slack channel. It also allows users to generate a sandwich on-demand using a slash command `/sandwich`.

## Features
- **Daily Sandwich Updates**: Automatically posts a randomly generated sandwich description to your specified Slack channel every day at 9 AM.
- **On-Demand Sandwich Generation**: Users can generate a new sandwich at any time by typing `/sandwich` in the Slack channel.
  
## Prerequisites
- **Node.js** (v12 or later) and **npm** installed on your machine.
- A **Slack App** with the necessary permissions and a bot token.
- **ngrok** or any other tunneling tool (optional, for local development).

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/slack-sandwich-bot.git
   cd slack-sandwich-bot
