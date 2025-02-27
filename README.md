
# Weather Web Application

This web application allows users to view current weather conditions and forecasts for a given city. The project was developed using only HTML, CSS, JS and leverages the **MeteoConcept API** to retrieve real-time weather data.

## Features

- Displays current weather conditions for a specified city.
- Short-term weather forecasts (e.g., for the next 3 days).
- Simple and intuitive user interface.

## Technologies Used

- **MeteoConcept API**: External service for fetching real-time weather data.
- **HTML/CSS**: For structuring and styling the user interface.
- **JavaScript**: For client-side interactions, such as form submissions without page reload.

## Installation

### Prerequisites

- Python 3.x
- pip (to install dependencies)

### Installation Steps

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Dany-py/Blue_Meteo.git
   ```

2. Set up the MeteoConcept API by obtaining an API key from [MeteoConcept](https://www.meteo-concept.com/), and add it to your JS file:
   ```js
   const url = "https://api.meteo-concept.com/api/forecast/daily/0?token=YOUR_API_KEYinsee=";
   ```

3. Open the application in your browser at the following address:
   ```
   http://localhost:5500/
   ```

## Contribution

Feel free to fork this repository and submit a pull request if you'd like to contribute.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
