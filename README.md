# Proof of Work Demo

A simple, interactive demonstration of Bitcoin's proof-of-work mining mechanism implemented in JavaScript.

[Live Demo](https://gregsamek.github.io/POWDemo/)

## Overview

This web-based demo visualizes how Bitcoin's mining process works by:
- Mining blocks with adjustable difficulty
- Simulating the difficulty adjustment mechanism
- Displaying real-time block statistics and mining times

## Features

- Adjustable target block time
- Configurable difficulty adjustment interval
- Real-time visualization of block mining times
- Scrollable block chain display
- Dynamic difficulty adjustment based on mining performance

## Usage

1. Open `index.html` in a modern web browser (or click [this link](https://gregsamek.github.io/POWDemo/))
2. Set your desired target block time (in seconds)
3. Set the difficulty adjustment interval (in blocks)
4. Click "Start Mining" to begin the simulation

## Technical Details

- Uses SHA-256 for block hashing
- Implements difficulty adjustment similar to Bitcoin
- Built with vanilla JavaScript and D3.js for visualizations
- Styled with Pico CSS framework

## Requirements

- Modern web browser with JavaScript enabled
- Internet connection (for loading external CSS/JS libraries)

## License

MIT