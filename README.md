# CS35L Final Project: Curdle!

## Description

Curdle is an upgraded version of the viral minigame Wordle with some cool added features. Users can guess with custom word banks, view a global leaderboard, keep track of their personal statistics, and guess words of different lengths!

## Key Features
1. Store user statistics through Firebase/Firestore
2. Dynamically display different sized boards for different length words
3. Search and sort users based on statistics to display a leaderboard
4. Create custom word banks

## Running Curdle
### Prerequisites
The only prerequisite to run the app is Node.js. If you do not have Node.js installed on your machine, you can do so [here](https://nodejs.org/en/download/ "Download Node.js")

### Setup
Using terminal, run these commands:
1. Enter the Curdle directory
```bash
cd path/to/curdle
```

2. Install npm dependencies
```bash
npm install
```

### Running the app
Using the terminal, run these commands:
1. Ensure that you are in the Curdle directory
```bash
cd path/to/curdle
```
2. Start the Node.js server
```bash
npm start
```
Running these will start up a local server to run Curdle, usually at localhost:3000 (displayed on the command line output). Enjoy!
