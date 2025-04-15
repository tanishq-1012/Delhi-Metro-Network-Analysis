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

We had converted the Opening Date column to datetime format for ease of analysis 

