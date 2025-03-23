# Find Your Representative

A lightweight tool to lookup US congressional representatives using the [US Census Geocoding API](https://geocoding.geo.census.gov/geocoder/).

## Features
- Find House representatives and Senators by address
- Display contact information
- Mobile-friendly interface
- CSV-based representative database

## Requirements
- Web server (local or hosted)
- Internet connection (for API calls)

## Setup
**Clone the repository**
   ```bash
   git clone https://github.com/KatahGii/FindMyReps.git
   ```

## Usage
1. Access the site through your web server
2. Enter a US address:
   - Street Address
   - City
   - State (2-letter abbreviation)
   - ZIP Code
3. Click "Search" to view representatives

## File Structure
```
├── index.html         # Main application file
├── styles.css         # Minimal styling
└── Database.csv       # Representative database (create this)
```

## Customization
- **Styling**: Modify `styles.css`
- **Data**: Update `Database.csv` with current representative info
- **Behavior**: Edit the JavaScript in `index.html`

## Data Format Requirements
The CSV file must include these columns in order:
1. `Name` - Representative's full name
2. `Party` - Political affiliation 
3. `Chamber` - "House" or "Senate"
4. `District` - Format: "CA-12" for House, "CA" for Senate
5. `Capitol Phone` - Washington office phone number
6. `Office Address` - Capitol office location

## License
MIT License - See [LICENSE](LICENSE) file

## Credits
- US Census Bureau Geocoding API
- CSV data structure based on public records
````
