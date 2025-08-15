I recently built a backend microservice called GeoAddress API using .NET Core. Its primary function is to take a human-readable address and return precise latitude and longitude coordinates. The workflow is straightforward: a client sends a POST request with an address, my API sends that to the Nominatim geocoding service from OpenStreetMap, and it receives back the geocoded data — including formatted address, lat/lon. I store this result along with the original input and a timestamp in a SQLite database for logging and analytics.

The service is designed to be RESTful, lightweight, and easily integrated into GIS applications or other systems. I also implemented error handling for invalid inputs and external API failures, and the architecture is modular so we can easily add new geocoding providers or features like authentication, rate limiting, or caching. For demos, I use Postman to show the request/response flow and a static map generated from the coordinates so stakeholders can see the location visually.

# GeoAddress API

A backend microservice built with **.NET Core** to geocode addresses into latitude/longitude coordinates using **Nominatim (OpenStreetMap)**.


## 🛠 Tech Stack
- **.NET 6**
- **Entity Framework Core** + **SQLite**
- **Nominatim API**
- **Postman** for testing

## 📥 Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/malneeditejaswini/GeoAddressAPI.git
   cd GeoAddressAPI
