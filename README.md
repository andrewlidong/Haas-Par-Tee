# Masters Golf Fun Tracker 🏌️‍♂️

A simple and fun way to track your Masters golf tournament picks with live ESPN scores. Perfect for keeping up with your Haas buddies' picks during the tournament!

## Quick Start

1. Create a new Google Sheet
2. Go to Extensions > Apps Script
3. Copy the contents of `Code.gs` into the Apps Script editor
4. Run the `onOpen` function to set up the menu
5. Click "Setup Sheet" to create the tracking sheets

## How to Use

1. In the "Player Picks" sheet:
   - Add each participant's name in column A
   - Add their 5 players (comma-separated) in column B
   Example: `Andrew, Tiger Woods, Rory McIlroy, Scottie Scheffler, Jon Rahm, Jordan Spieth`

2. Click "Update Live Scores" to:
   - Fetch the latest scores from ESPN
   - Show everyone's picks with current scores
   - Display scores as "+2" or "-3" relative to par

3. Watch the scores update in real-time!

## Features

- Simple, clean interface
- Live ESPN score updates
- Easy player matching
- Fun golf emoji alerts! 🏌️‍♂️

## Tips

- Update scores whenever you want to check the latest standings
- Player names are matched flexibly (no need for exact spelling)
- Have fun watching the tournament with your Haas buddies! ⛳ 