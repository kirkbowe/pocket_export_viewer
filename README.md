# Pocket Export Viewer

A web-based tool for viewing and searching through bookmarks exported from getpocket.com. This application allows users to upload their Pocket bookmark exports in CSV format and view them in an organized, searchable card layout.

## Features

- CSV file upload support for Pocket bookmark exports
- Responsive card-based layout
- Search functionality for filtering bookmarks
- Favicon display for each bookmark
- Tag support and display
- Timestamp conversion to readable dates
- Mobile-friendly design

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- Papa Parse (CSV parsing library) -- pulled in from CloudFlare
- Note that favicons are pulled in from Google's favicon cache, so you may wish to modify this based on your preferences

## Getting Started

1. Clone this repository
2. Open `index.html` in a web browser
3. Click the file input button to upload your Pocket bookmarks CSV export
4. Use the search bar to filter through your bookmarks.  This is a free text search so it will find titles, tags, etc.

## Usage

1. Export your bookmarks from getpocket.com as a CSV file
2. Load the exported CSV file using the file input
3. Browse your bookmarks in the card layout
4. Use the search bar to filter bookmarks by title, URL, or tags
5. Click on any bookmark title to open the original URL

## Features Details

### Card Display
- Each bookmark is displayed as a card containing:
  - Favicon as a tiled header image (favicon currently retrieved from Google)
  - Title (clickable link)
  - URL
  - Date added
  - Associated tags

### Search Functionality
- Real-time filtering of bookmarks
- Searches through titles, URLs, and tags

## Contributing

Feel free to submit issues and enhancement requests.

## License

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

