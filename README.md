# JustWatch Web Scraping Project

This project involved scraping movie and TV show data from the JustWatch website using BeautifulSoup and Python. The data was then filtered and analyzed using Pandas, and the results were exported to a CSV file for further processing.

## Project Description

JustWatch is a popular platform that allows users to search for movies and TV shows across multiple streaming services like Netflix, Amazon Prime, Hulu, and others. This project focused on scraping data directly from the JustWatch website's HTML, without using their APIs. The scraped data included information about movies and TV shows, such as titles, release years, genres, IMDb ratings, and the streaming services where they are available.

## Project Features

### 1. Web Scraping

Using BeautifulSoup, the project scraped the following data:

#### a. Movie Information:
- **Movie title**
- **Release year**
- **Genre**
- **IMDb rating**
- **Streaming services available** (Netflix, Amazon Prime, Hulu, etc.)
- **URL** to the movie page on JustWatch

#### b. TV Show Information:
- **TV show title**
- **Release year**
- **Genre**
- **IMDb rating**
- **Streaming services available** (Netflix, Amazon Prime, Hulu, etc.)
- **URL** to the TV show page on JustWatch

#### c. Scope:
- Scraped data for 100 movies and 100 TV shows.
- The entry point was based on popular movies, specific genres, etc., to ensure a diverse dataset.

### 2. Data Filtering & Analysis

After scraping, the data was filtered and analyzed using Pandas:

#### a. Data Filtering:
- Only included movies and TV shows released in the last 2 years from the current date.
- Only included movies and TV shows with an IMDb rating of 7 or higher.

#### b. Data Analysis:
- Calculated the **average IMDb rating** for the scraped movies and TV shows.
- Identified the **top 5 genres** with the highest number of available movies and TV shows.
- Determined the **streaming service** with the most significant number of offerings.

### 3. Data Export

- The filtered and analyzed data was exported to a CSV file for further use.
- The CSV file was stored in a Google Drive folder, and a shareable link was provided for easy access.
