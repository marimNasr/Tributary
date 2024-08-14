# Tributary
Backend infrastructure for Ford's sensor streaming system. it is designed to give drivers real-time insights into their vehicles by processing data collected from engine sensors and then exposing it to the internet.

## Key Features
- /record Endpoint: Periodically called by embedded sensors within a vehicle to post data to the database.
- /collect Endpoint: Used by a user-facing mobile application to retrieve the data.

## Languages and Technologies Used
- Python
- Flask
- Docker
