# Delhi-Metro-Network-Analysis

This project analyzes and visualizes the Delhi Metro network using Python, with the aim to uncover insights such as network expansion, line-specific details, station layouts, and spatial patterns. Interactive maps and charts help to better understand the growth and structure of one of India's largest urban rail networks.

## Project Overview

The Delhi Metro is a vast rapid transit system serving the National Capital Region (NCR) of India. This project focuses on:

- **Mapping metro stations line-wise** using Folium.
- **Analyzing temporal trends** in station openings.
- **Measuring average distances between stations** by line.
- **Exploring structural layouts** of metro stations.

Metro Network Analysis involves examinings the network of metro systems to understand their structure, efficiency, and effectiveness. It typically includes analyzing routes, stations, traffic, connectivity, and other operational aspects.
Analyzing the metro network in a city like Delhi helps improve urban transportation infrastructure, leading to better city planning and enhanced commuters experiences. Below commuter experiences.
Below is the process we can follow for the task of Metro Network Analysis of Delhi:

1. Determine what you want to achieve. It could be optimizing routes, reducing congestion, improving passenger flow, or understanding travel patterns.
2. Collect data on metro lines, stations, connections, and transit schedules.
3. Clean the data for inconsistencies, missing values, or errors
4. Create visual representations of the network, such as route maps, passenger flow charts, or heat maps of station congestion.
5. Analyze how effectively the network handles passenger traffic and meet operational targets.

## Dataset

📁 Dataset

Let's get started with the task of Delhi Metro Network Analysis by importing the dataset:

**Filename:** `Delhi-Metro-Network.csv`

**Features:**
- `Station Name`: Name of the metro station  
- `Line`: Metro line the station belongs to  
- `Latitude` & `Longitude`: Geolocation coordinates  
- `Opening Date`: Date the station was opened  
- `Distance from Start (km)`: Distance from the line’s starting point  
- `Station Layout`: Type of structural layout (Elevated, Underground, etc.)

<img width="770" alt="Screenshot 2025-04-15 at 12 38 03 AM" src="https://github.com/user-attachments/assets/3091d7d4-fe6e-453b-b1c1-c911bee3cb88" />

Now, let's have a look at whether the dataset has any null values or not and then look at the data types:

<img width="416" alt="Screenshot 2025-04-15 at 12 39 30 AM" src="https://github.com/user-attachments/assets/d4510a2e-f1b9-464f-8079-7f5162fcca45" />

**DataTypes**

<img width="416" alt="Screenshot 2025-04-15 at 12 39 42 AM" src="https://github.com/user-attachments/assets/bbebd63e-f11a-48fc-a814-6eb18564beef" />

We had converted the Opening Date column to datetime format for ease of analysis.

## 🌍Geospatial Analysis

### 📍 1. Interactive Metro Map

A city-wide interactive map using **Folium** showing:

- All metro stations
- Colored markers per line
- Tooltip with station and line name

Now, let's start by visualizing the locations of the metro stations on the map. It will give us an insights into geographical distribution of the stations across Delhi. We will use the latitude and longitude data to plot each station.
For this, i'll create a map with markers for each metro station. Each marker will represent a station, and we'll be able to analyze aspects like station density and geographic spread.
Let's proceed with this visualization:

<img width="1140" alt="Screenshot 2025-04-15 at 12 40 23 AM" src="https://github.com/user-attachments/assets/ef79c40d-8d01-485a-a18c-4dc7072196ea" />

Here is the map showing the geographical distribution of Delhi Metro stations. Each marker represents a metro station, and you can hover or click on the markers to see the station name and the metro line it belongs to. This map provides a visual understanding of how the metro stations are spread across in Delhi.

## Temporal Analysis

### 📈 2. Year-wise Station Expansion

Bar chart (using Plotly Express) showing how many stations were added each year:

- Helps visualize rapid expansion years.
- Highlights infrastructure growth phases.

Now, I will analyze the growth of the Delhi Metro network over time. I'll look at how many stations were opened each year and visualize this growth. It can provide insights into the pace of metro network expansion and its development phases.
I'll start by extracting the year from the Opening Date and then count the number of stations opened each year. Following this I'll visualize this information in bar plot. 
Let's proceed with this analysis:

<img width="1107" alt="Screenshot 2025-04-15 at 12 40 44 AM" src="https://github.com/user-attachments/assets/cbf70450-56fd-4dd0-92b8-ac3f60b6a17c" />

The bar chart illustrates the number of Delhi Metro Stations opened each year. This visuakization helps us understand the temporal development of the metro network. Some key observations include:

1. Some years show a significant number of new station openings, indicating phases of rapid network expansion.
2. Conversely, there are years with few or new stations, which could be due to various factors like planning, funding, or construction challenges.
