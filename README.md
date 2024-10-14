# Scarborough Neighborhood Analysis and Clustering

This project analyzes and clusters neighborhoods within the Scarborough borough of Toronto, Canada, using Foursquare location data. 

## Project Goal

The main goal is to segment and cluster the neighborhoods of Scarborough based on the types of venues available in each neighborhood. This will provide valuable insights for individuals and businesses looking to understand the characteristics and diversity of neighborhoods in Scarborough.

## Data Sources

1. **Toronto Neighborhood Data:** A CSV file containing information about different neighborhoods in Toronto, including their postal codes, boroughs, latitude, and longitude.
2. **Foursquare Location Data:** The Foursquare API is used to obtain venue data for each neighborhood in Scarborough. This includes information such as the venue name, category, and location.

## Methodology

The project follows a step-by-step approach:

1. **Data Collection:** Retrieve the Toronto neighborhood data and utilize the Foursquare API to collect venue information for each neighborhood in Scarborough.
2. **Data Exploration:** Analyze the collected data to understand the distribution of different venues across neighborhoods.
3. **One-Hot Encoding:** Convert categorical venue categories into numerical data using one-hot encoding.
4. **Feature Selection:** Identify the most relevant features (e.g., venue categories) for clustering.
5. **K-Means Clustering:** Apply the K-Means clustering algorithm to group similar neighborhoods based on their venue characteristics.
6. **Cluster Analysis:** Analyze the resulting clusters to identify distinct patterns and characteristics of each cluster.

## Code Structure

The code is organized into several sections:

1. **Import Libraries:** Includes necessary libraries such as Pandas, NumPy, BeautifulSoup, Folium, and scikit-learn.
2. **Import Dataset:** Reads the Toronto neighborhood data from a CSV file.
3. **Display Map:** Visualizes the location of neighborhoods on a map using Folium.
4. **Scarborough Data:** Isolates the Scarborough borough data from the Toronto dataset.
5. **Scarborough Map:** Displays a map of the Scarborough borough.
6. **Foursquare Crawler:** Defines a function to crawl venue data from Foursquare using the API.
7. **Crawling Scarborough:** Retrieves venue data for different neighborhoods in Scarborough.
8. **Venue Dataset:** Prepares a dataset of venues for each neighborhood.
9. **Neighborhood Display:** Displays information about unique neighborhoods in Scarborough.
10. **Category Display:** Shows the unique categories of venues found in Scarborough.
11. **One Hot Encoding:** Encodes the venue categories using one-hot encoding.
12. **K-Means Clustering:** Applies K-Means clustering to group neighborhoods based on venue characteristics.
13. **Neighborhood Display:** Shows insights about a particular neighborhood in a specific cluster.

## Key Findings

The analysis identifies clusters of neighborhoods that share similar characteristics in terms of venue types. This clustering can inform decision-making for individuals and businesses considering moving to or setting up a business in Scarborough.

## Potential Applications

- **Business Location Selection:** Identifying neighborhoods with a high density of certain venue types (e.g., restaurants, shopping centers) for optimal business location.
- **Neighborhood Comparison:** Comparing different neighborhoods based on their venue characteristics to facilitate informed choices for housing or relocation.
- **Urban Planning:** Utilizing cluster information for urban planning initiatives and identifying areas with potential for development or improvement.

## Disclaimer

This project is for educational and demonstrative purposes only. The analysis results and conclusions should not be considered definitive or comprehensive. 
"""
