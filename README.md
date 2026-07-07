# business_web_finder
finds businesses in an area that dont have websites via google maps API

# Business Web Finder

Business Web Finder is a browser-based Google Maps tool that helps scan a selected area for businesses and collect useful public business information.

The user can place a circular scan area on the map, resize it, scan nearby businesses, sort/search results, view businesses as map pins, and export the results to a CSV file.

## Features

- Interactive Google Map
- Double-click to place a scan circle
- Resize the scan circle with a menu slider or map handle
- Scan businesses inside the circle
- Adjustable scan density
- Search results by business name and address
- Sort results by name, address, rating, and last review date
- Display businesses as pins on the map
- Export results to CSV
- Mobile-friendly sliding control panel

## Technologies Used

- HTML
- CSS
- JavaScript
- Google Maps JavaScript API
- Google Places API
- GitHub Pages

## Data Collected

For each business, the app tries to collect:

- Business name
- Address
- Phone number
- Website
- Google Maps listing URL
- Rating
- Review count
- Last available review date
- Business status
- Business type/category
- Latitude and longitude

## Important Limitation

Google Places API does not provide the date a business was founded, opened, or added to Google Maps.

Because of that, this project uses the most recent review date available from the Places API.

## How It Works

1. Open the website.
2. Double-click on the map to place a scan circle.
3. Resize the circle if needed.
4. Click **Scan Circle**.
5. The app searches for businesses inside the circle.
6. Results appear in the Business Area Scanner section.
7. Businesses also appear as pins on the map.
8. Results can be searched, sorted, and exported.

## Setup

Clone the repository:

```bash
git clone https://github.com/Mredozubov/business_web_finder.git
