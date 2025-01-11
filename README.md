# Barber Shops Locator using Mappls API

A simple web application to find nearby barber shops using Mappls (previously MapmyIndia) APIs.

## Setup

1. Get your Mappls API credentials:
   - Sign up at [Mappls API Dashboard](https://apis.mappls.com/console/)
   - Create a project and get:
     - API Key
     - Client ID
     - Client Secret

2. Usage:
   - Clone this repository
   - Open `map.html` in your code editor
   - Replace the API credentials in the script tags:
   ```html
   <script src="https://apis.mappls.com/advancedmaps/api/<access_token>/map_sdk?layer=vector&v=3.0&callback=initMap1"></script>
   <script src="https://apis.mappls.com/advancedmaps/api/<access_token>/map_sdk_plugins?v=3.0"></script>
   ```

3. Features:
   - Shows nearby barber shops on map
   - Filters out beauty parlors and salons
   - Click on markers to see shop details
   - Open shop locations in Mappls
   - Responsive sidebar with shop listings

## Security Note

⚠️ IMPORTANT: When uploading to GitHub:
- Do NOT commit your actual API keys
- Create a copy of map.html with placeholder API keys for public sharing
- Add your API keys file to .gitignore

Example .gitignore entry:
```
# API Keys
api-keys.js
.env
```

## Local Development

1. Simply open map.html in a browser
2. Allow location access for nearby search
3. Click markers or list items to see shop details

## Dependencies

- Mappls JavaScript SDK v3.0
- Mappls Nearby Places Plugin
- Modern browser with geolocation support

## License

This project is licensed under the MIT License - see the LICENSE file for details.
