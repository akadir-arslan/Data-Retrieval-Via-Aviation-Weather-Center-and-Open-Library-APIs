# Data Retrieval via Aviation Weather Center and Open Library APIs

This project demonstrates the use of APIs from the Aviation Weather Center and Open Library to retrieve data and answer specific questions related to aviation and literature. The goal is to access the required information in JSON format and process it using Python.

## Project Overview

The project is divided into two main sections:

## 1. Aviation Weather Center API

Using the Aviation Weather Center's Data API, this project retrieves following information about the airport with the station ID 'EDDH'. 

- Retrieving the name of the airport
- Finding the IATA code of the airport
- Obtaining the geolocation (longitude/latitude)
- Determining the number of runways at the airport

## 2. Open Library API

Using the Open Library API, this project retrieves following  book and author information.

- Retrieving the title and subtitle of a book by its ISBN '978-1108491457'.
- Identifying the author of the book.
- Finding the top work of author Marko Luksa and the number of books written by him.

## Data Source

- **Aviation Weather Center API**: [Aviation Weather Center API](https://aviationweather.gov/data/api/)
- **Open Library API**: [Open Library API](https://openlibrary.org/developers/api/)

## How to Run

1. Download the datasets by making the appropriate API calls using the provided links.
2. Run the cells in the Jupyter Notebook in order to reproduce the analysis and retrieve the answers.

This project showcases how cloud-based APIs can be utilized to fetch and process data across different domains, demonstrating the power and flexibility of cloud services in Python.
