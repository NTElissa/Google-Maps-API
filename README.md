# Google Maps API Route Tracking

This is a React application that utilizes the Google Maps API to display a predefined route with multiple stops. It allows real-time tracking of the driver's location and calculates the estimated time of arrival (ETA) to the next stop.

## Features

- Interactive map displaying the entire route with marked stops
- Real-time tracking of the driver's current location
- Calculation and display of the ETA for the next stop, assuming constant average speed
- Marker clustering for better visualization of stops

## Technologies Used

- React.js
- Google Maps API
- `@react-google-maps/api` library

## Live Demo

Want to see the application in action? Click the button below to launch the live demo:

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Launch-green?style=for-the-badge)](https://ntelissa.github.io/Google-Maps-API/)

## Installation

1. Clone the repository:
2. Navigate to the project directory:
3. Install dependencies:
4. Create a `.env` file in the root directory and add your Google Maps API key:
5. Start the development server:
6. Open `http://localhost:5173` in your browser to see the application.

## Usage

1. The map will load with the predefined route and stops displayed.
2. The driver's current location is represented by a draggable marker on the map.
3. Drag the marker to simulate the driver's movement along the route.
4. As the driver approaches a stop, the ETA for that stop will be displayed on the marker.
5. Once the driver reaches a stop (within a certain distance threshold), the next stop will be highlighted, and the ETA will update accordingly.
6. The process continues until the driver reaches the final destination.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Screenshots

Here are some screenshots showcasing the application:
### Figma Design 
![Screenshot 2024-05-07 202827](https://github.com/NTElissa/Google-Maps-API/assets/122989293/7cbff295-8385-4d04-9d78-0ac7c069b0df)

### Initial Route

![coming soon](https://via.placeholder.com/800x450?text=Coming+Soon)

### Approaching a Stop

![Approaching a Stop](https://via.placeholder.com/800x450?text=Coming+Soon)

### Marker Clustering

![Marker Clustering](https://via.placeholder.com/800x450?text=coming+Soon)
