# airports-nodejs

A comprehensive library providing easy retrieval of airport data based on IATA, ICAO, city codes, country codes, and continents. Ideal for developers building applications related to aviation, travel, and geography.

## Features

- Retrieve airport data using IATA code.
- Retrieve airport data using ICAO code.
- Fetch data using city codes.
- Fetch data using country codes.
- Retrieve data based on continents.
- Built-in error handling for invalid input formats.
- Efficiently packaged with minimized and gzipped data.
- **Comprehensive Data Access**: Retrieve airport data using IATA code, ICAO code, city codes, country codes, and continents.
- **Unique Link Integration**: The first library to provide direct links to [FlightRadar24](https://www.flightradar24.com/), [Radarbox](https://www.radarbox.com/), and [FlightAware](https://www.flightaware.com/) for each airport, giving users immediate access to live flight tracking and airport data.

## Installation

You can install `airports-nodejs` using npm:

```bash
npm install airports-nodejs
```

## Usage

Here's how you can use the library:

```javascript
const airportData = require('airports-nodejs');

// Retrieve airport data using IATA code
const airportByIATA = airportData.getAirportByIata("AAA");
console.log(airportByIATA);

// Retrieve airport data using ICAO code
const airportByICAO = airportData.getAirportByIcao("NTGA");
console.log(airportByICAO);

// Fetch data using city codes
const airportByCityCode = airportData.getAirportByCityCode("NYC");
console.log(airportByCityCode);

// Fetch data using country codes
const airportByCountryCode = airportData.getAirportByCountryCode("US");
console.log(airportByCountryCode);

// Retrieve data based on continents
const airportByContinent = airportData.getAirportByContinent("AS");
console.log(airportByContinent);
```

## Example Data Fields

For Chennai International Airport:

| Field Name           | Data                                                     |
|----------------------|----------------------------------------------------------|
| IATA                 | MAA                                                      |
| ICAO                 | VOMM                                                     |
| Time Zone            | Asia/Kolkata                                             |
| City Code            | MAA                                                      |
| Country Code         | IN                                                       |
| Name                 | Chennai International Airport                            |
| Latitude             | 12.99                                                    |
| Longitude            | 80.1693                                                  |
| Altitude (in feet)   | 52                                                       |
| State                | Tamil Nadu                                               |
| City                 | Pallavaram                                               |
| County               | Kancheepuram                                             |
| State Code           | Tamil Nadu                                               |
| Airport Type         | large_airport                                            |
| Continent            | AS                                                       |
| State Abbreviation   | IN-TN                                                    |
| International        | TRUE                                                     |
| Wikipedia Link       | [Wikipedia](https://en.wikipedia.org/wiki/Chennai_International_Airport)|
| Official Website     | [Chennai Airport](http://chennaiairport.com)            |
| Location ID          | 12513629                                                 |
| Phone Number         | 044-2340551                                              |
| Runway Length (in meters) | 10050                                               |
| Flightradar24        | [Flightradar24](https://www.flightradar24.com/airport/MAA)|
| Radarbox             | [Radarbox](https://www.radarbox.com/airport/VOMM)       |
| Flightaware Link     | [Flightaware](https://www.flightaware.com/live/airport/VOMM)|

### Singapore Changi Airport:

| Field Name           | Data                                                     |
|----------------------|----------------------------------------------------------|
| IATA                 | SIN                                                      |
| ICAO                 | WSSS                                                     |
| Time Zone            | Asia/Singapore                                           |
| City Code            | SIN                                                      |
| Country Code         | SG                                                       |
| Name                 | Singapore Changi Airport                                 |
| Latitude             | 1.35019                                                  |
| Longitude            | 103.994                                                  |
| Altitude (in feet)   | 22                                                       |
| State                | Singapore                                                |
| City                 | Singapore                                                |
| County               | Singapore                                                |
| State Code           | South East                                               |
| Airport Type         | large_airport                                            |
| Continent            | AS                                                       |
| State Abbreviation   | SG-04                                                    |
| International        | TRUE                                                     |
| Wikipedia Link       | [Wikipedia](https://en.wikipedia.org/wiki/Singapore_Changi_Airport)|
| Official Website     | [Changi Airport](http://www.changiairport.com/)         |
| Location ID          | 12517525                                                 |
| Phone Number         | (65) 6542 1122                                           |
| Runway Length (in meters) | 13200                                               |
| Flightradar24         | [Flightradar24](https://www.flightradar24.com/airport/SIN)|
| Radarbox              | [Radarbox](https://www.radarbox.com/airport/WSSS)       |
| Flightaware           | [Flightaware](https://www.flightaware.com/live/airport/WSSS)|


## Running the Project Locally

1. Clone the repository:

```bash
git clone https://github.com/aashishvanand/airports-nodejs.git
```

2. Change into the cloned directory:

```bash
cd airports-nodejs
```

3. Install the necessary dependencies:

```bash
npm install
```

4. To bundle the source code using Webpack:

```bash
npm run build
```

5. To run tests:

```bash
npm test
```

## License

This project is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/aashishvanand/airports-nodejs/issues).