# NEGM Masters Tracker 🏌️‍♂️

A simple script to automatically update your NEGM Masters pool spreadsheet with live tournament scores. Perfect for tracking those 25-year-running golf bets with the boys!

## Setup

1. Convert your Excel tracker to Google Sheets:
   - Open Google Drive
   - Upload "2025_NEGM_Tracker.xlsx"
   - Right-click > Open with > Google Sheets
   - File > Save as Google Sheets

2. Add the script:
   - In Google Sheets, go to Extensions > Apps Script
   - Copy the contents of `Code.gs` into the editor
   - Update `SHEET_NAME` in the config to match your sheet name (probably "Sheet1")
   - Save the script

3. Deploy:
   - Click "Deploy" > "New deployment"
   - Choose "Web app"
   - Set Execute as: "Me"
   - Who has access: "Anyone with Google Account"
   - Click "Deploy" and authorize when prompted

## Usage

1. Refresh your spreadsheet
2. Look for the new "Masters Tracker" menu at the top
3. Click "Update Live Scores" to fetch current scores

The script will automatically update the score columns for:
- GI picks (Column C)
- OD picks (Column E)
- VK picks (Column G)

## Notes

- Scores are pulled directly from Masters.com
- Player names are matched flexibly (first name, last name, or full name)
- Scores show as "+1" or "-2" relative to par
- If a player isn't found, you'll see "N/A"

## Props and Side Bets

The script currently updates only the main player scores. All those creative prop bets (Green Jacketed Jell Birds, LIV Spare Tire Showdown, etc.) still need manual updating - keeping some of the traditional touch to the 25-year tradition! ⛳ 