# Twitch Streamer Promotional Message Bot

This bot scrapes information about Twitch streamers from the Twitch API, generates promotional messages using the ChatGPT API, and sends the messages to the streamers via the Twitter API.

## Prerequisites

To use this bot, you need the following:

- A Twitch account with a registered application and client ID
- A Twitch OAuth token with the "helix:users:read" scope
- A ChatGPT API key
- A Twitter account with a registered application and consumer key/secret and access token/secret
- A CSV file with the usernames of Twitch streamers you want to scrape information for (one username per row)

## Installation

1. Clone this repository:


2. Install the required Python packages:


3. Set the following environment variables with your API credentials:



4. Update the `streamers.csv` file with the usernames of Twitch streamers you want to scrape information for.

## Usage

To use this bot, run the following command:


This will scrape information about each streamer in the `streamers.csv` file, generate a promotional message for them using the ChatGPT API, and send the message to the streamer via the Twitter API.

## Acknowledgements

This bot uses the following APIs:

- [Twitch API](https://dev.twitch.tv/docs/api/)
- [ChatGPT API](https://beta.openai.com/docs/api-reference/introduction)
- [Twitter API](https://developer.twitter.com/en/docs)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
