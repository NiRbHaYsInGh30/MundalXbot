# Mundal Bot

A Twitter bot which performs basic functions for now.

### Installation

1. **Install Node.js**: Ensure you have Node.js installed on your machine.

2. **Install Dependencies**: Initialize your project and install the necessary packages.
   ```bash
   npm init -y
   npm install twitter-api-v2 dotenv cron express


### Create an .env File: Load your API keys.

1. Create an app account on [Twitter Developer](https://dev.twitter.com/apps)
2. Sign in with your Twitter account
3. Create a new app account
4. Modify the settings for that app account to allow read & write permissions
5. Generate a new OAuth token with those permissions
6. Following these steps will create 4 tokens that you will need to place in the `.env` file.

Create a file called `.env` and add your keys there:

```plaintext

TWITTER_APP_KEY=your-app-key

TWITTER_APP_SECRET=your-app-secret

TWITTER_ACCESS_TOKEN=your-access-token

TWITTER_ACCESS_SECRET=your-access-secret
```
### Run the Bot: Start the bot by running the following command:

```node index.js```

### Functions to Add
Searching and reposting tweets with certain keywords

Sending a direct message to anyone who follows and following back
