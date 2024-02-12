# Open Brewery DB API Demo

This is a simple web page that demonstrates how to use the Open Brewery DB API to fetch and display information about breweries in South Korea.

## How to Use

1. Clone this repository or download the `index.html` file.
2. Open `index.html` in a web browser.
3. The page will automatically fetch and display information about breweries in South Korea.

## Description

The web page contains a heading "List of Breweries in South Korea" followed by a section with the id `breweriesList`, where the brewery information is displayed dynamically using JavaScript.

The JavaScript code makes an asynchronous request to the Open Brewery DB API, specifically searching for breweries in South Korea. It then parses the JSON response and dynamically updates the HTML to display relevant information about each brewery, such as name, type, city, state, and website URL.

If no breweries are found in South Korea, a message indicating so is displayed.

## Dependencies

- This web page relies on the Open Brewery DB API for fetching brewery information.

## License

This project is licensed under the [MIT License](LICENSE).
