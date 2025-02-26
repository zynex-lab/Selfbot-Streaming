# Discord Rich Presence Bot

A Discord self-bot for creating highly customizable rich presence statuses.

## Setup Instructions

### Local Development
1. Clone the repository
2. Create a `.env` file in the root directory:
```env
TOKEN=your_discord_token_here
PORT=5000
```
3. Install dependencies:
```bash
npm install
```
4. Start the bot:
```bash
npm start
```

### Deployment on Render
1. Fork this repository to your GitHub account
2. Create a new Web Service on Render
3. Connect your GitHub repository
4. Add your Discord token as an environment variable:
   - Key: `TOKEN`
   - Value: Your Discord user token
5. Deploy the service

The bot will automatically stay online 24/7 on Render's web service.

## Important Notes
- Keep your Discord token secret
- Never commit the `.env` file
- The bot uses a keep-alive system to maintain 24/7 uptime
