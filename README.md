# Sentiment Analysis Plugin for Unreal Engine

The Sentiment Analysis Plugin for Unreal Engine integrates WebSocket communication with a sentiment analysis service, allowing users to analyze and monitor sentiments of text messages within their Unreal Engine projects.

## Features

- Establish WebSocket connection to a sentiment analysis service.
- Send text messages for sentiment analysis.
- Receive sentiment analysis results in real-time.

## Installation

1. Clone or download this repository.
2. Copy the `SentimentAnalysisPlugin` folder into the `Plugins` directory of your Unreal Engine project.

## Usage

### Connecting to WebSocket

To establish a WebSocket connection to the sentiment analysis service, follow these steps:

1. Ensure the plugin is enabled in your Unreal Engine project.
2. Call the `ConnectWebSocket` function from the `SentimentAnalysisPlugin` category at the appropriate time (e.g., on game start).

### Sending Messages

To send text messages for sentiment analysis, use the `SendMessage` function from the `SentimentAnalysisPlugin` category. Pass the text message as a parameter to this function.

### Receiving Messages

To receive sentiment analysis results, use the `ReceiveMessage` function from the `SentimentAnalysisPlugin` category. This function returns the last received sentiment analysis result from the WebSocket server.


## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please [open an issue](https://github.com/your-repo-name/issues).

## License

This plugin is licensed under the MIT License. See [LICENSE](LICENSE) for more information.
