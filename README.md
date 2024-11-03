# My Family Adventures - Interactive Map Project

## Overview
**My Family Adventures** is an interactive web project that visualizes our family's travels across the world. Using Mapbox and Bootstrap, this project highlights the countries we have visited, showcasing memorable places with an interactive map and a modal display of pictures and details for each location.

## Features
- **Interactive World Map**: Highlights the countries visited by the family using color-coded boundaries.
- **Clickable Markers**: Each visited location features a flag marker, allowing users to click and see more details.
- **Modal Display**: Detailed information about each location, including images, dates, and descriptions, shown in a modal window.
- **User-Friendly Interface**: Utilizes Bootstrap for a responsive and aesthetically pleasing layout.

## Technologies Used
- **HTML5** for structuring the content.
- **CSS3** with embedded custom styling for layout adjustments.
- **JavaScript** for dynamic interactions and map functionality.
- **Mapbox GL JS** for map rendering and geographic features.
- **Bootstrap 5** for styling and responsive components.

## How to Run
1. **Clone or download the repository** and save it to your local machine.
2. **Open the `index.html` file** in a modern web browser.
3. **Ensure an internet connection** to load the external resources such as Bootstrap, Mapbox GL JS, and CSS.

## Configuration
- **Mapbox Access Token**: Ensure that the Mapbox token (`mapboxgl.accessToken`) is valid. Replace the placeholder token with your own if necessary.
- **Country Data**: The `visitedCountries` array contains details of the locations visited, including:
  - ISO country code (`isoCode`)
  - City name (`city`)
  - Date of visit (`date`)
  - Title and description (`title`)
  - Image URL (`imageUrl`)
  - Flag icon URL (`flagIcon`)
  - Geographic coordinates (`coordinates`)

## Usage
- **Interact with the map** by clicking on the markers or the country highlights to display a modal with detailed information and images.
- **Explore different locations** by clicking directly on the marked areas.
- **Hover interactions** change the cursor style for better user feedback.

## Customization
- **Add More Locations**: Extend the `visitedCountries` array with new country data.
- **Change Styling**: Modify the CSS within the `<style>` tags or add a separate stylesheet for more complex changes.
- **Map Settings**: Adjust the map's `center` and `zoom` levels to tailor the initial display.

## Future Enhancements
- Add markers for visited cities to display pictures for each city.


## License
This project is licensed under the MIT License. Feel free to use and modify it for personal projects.

## Acknowledgments
- **Mapbox** for providing the interactive map service.
- **Bootstrap** for making the UI design streamlined and responsive.

---

Enjoy exploring the world through **My Family Adventures**!
