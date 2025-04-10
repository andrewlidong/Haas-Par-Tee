# NEGM Masters Tracker 2025 🏌️‍♂️

A script to automatically update live scores for the NEGM Annual Betting Competition. Works with the [2025 Masters Tournament Tracker](https://docs.google.com/spreadsheets/d/1Ex1aPO8lQ2UyXjRJjSogUQlWMNwPEcftP-oDNSae_Jk/edit?usp=sharing).

## Setup

1. In the Google Sheet:
   - Go to Extensions > Apps Script
   - Copy the contents of `Code.gs` into the editor
   - Save the script
   - No need to change sheet names - it's already configured for this sheet!

2. Deploy:
   - Click "Deploy" > "New deployment"
   - Choose "Web app"
   - Set Execute as: "Me"
   - Who has access: "Anyone with Google Account"
   - Click "Deploy" and authorize when prompted

## Usage

1. Refresh the Google Sheet
2. Look for the new "Masters Live" menu at the top
3. Click "Update Scores" to fetch current scores

The script will automatically:
- Update live scores for GI, OD, and VK picks
- Calculate totals for each player
- Update the "Last Update" timestamp
- Show "Not started" for players who haven't teed off yet

## Score Locations

Scores are updated in these columns:
- Graeme Stewart (GI) scores in Column C
- Paul Odland (OD) scores in Column E
- Vikas Kabra (VK) scores in Column G

## Notes

- Scores are pulled directly from Masters.com
- Updates the "Last Update" timestamp in cell B15
- Automatically calculates totals in row 10
- Shows "Not started" for players who haven't begun
- Shows "Not found" if there's an issue matching a player name

## Props and Side Bets

The script updates only the main player scores. All the fun side action (Green Jacketed Jell Birds, LIV Spare Tire Showdown, etc.) stays manual - keeping the tradition alive! ⛳ 