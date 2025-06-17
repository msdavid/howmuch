# How Much

A Singapore salary calculator web application that helps employees understand their daily, hourly, overtime, and holiday rates based on Singapore Employment Act regulations.

## Features

- Calculate daily rate from monthly or hourly salary
- Calculate hourly rate from monthly salary (or vice versa)
- Calculate overtime rate (1.5x hourly rate)
- Calculate rest day rate (2x daily rate)
- Calculate public holiday rate
- Mobile-friendly responsive design
- Progressive Web App (PWA) capability - can be installed on mobile devices
- Direct links to relevant Singapore Employment Act references

## Usage

### Quick Start

1. Open `index.html` in a web browser
2. Enter your basic monthly salary or hourly rate
3. Adjust days per week if needed (default is 5.5 days)
4. View calculated rates instantly
5. Tap any rate card to see the relevant Singapore Employment Act reference

### Running with Local Server

For better performance and to test PWA features:

```bash
# Make the server executable
chmod +x server.py

# Run on default port (6008)
./server.py

# Or specify a custom port
./server.py 8080
```

Then open `http://localhost:6008` (or your chosen port) in your browser.

## Installation as Mobile App

### iPhone/iPad
1. Open Safari browser
2. Navigate to the app
3. Tap the Share button (square with arrow)
4. Scroll down and tap "Add to Home Screen"
5. Name it and tap "Add"

### Android
1. Open Chrome browser
2. Navigate to the app
3. Tap the menu (3 dots) in top right
4. Tap "Add to Home screen"
5. Name it and tap "Add"

## Legal References

The calculations are based on the Singapore Employment Act (Chapter 91):

- **Daily rate**: Part VI, Section 107A (a)
- **Hourly rate**: Fourth Schedule, Paragraph 1
- **Overtime rate**: Part IV, Section 38
- **Rest Day rate**: Part IV, Section 37
- **Public Holiday rate**: Part IX, Section 88

## Disclaimer

The information provided by this application is for general guidance on subjects of interest only. These calculations apply only to Singapore labor laws. The application developer(s) disclaim all liability and responsibility arising from any reliance placed on such materials by any user, or by anyone who may be informed of any of its contents. The information is provided solely on the basis that users will be responsible for making their own assessment of it.

## Technical Details

- Pure HTML/CSS/JavaScript - no external dependencies
- Mobile-first responsive design
- Supports both monthly and hourly salary input
- Input validation for numeric values only
- Instant calculation updates

## Files

- `index.html` - Main application file with all HTML, CSS, and JavaScript
- `server.py` - Simple Python HTTP server for local development
- `README.md` - This documentation file
