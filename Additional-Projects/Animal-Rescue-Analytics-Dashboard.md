# Animal Rescue Analytics Dashboard

## Project Link
GitHub Repository: [Animal Rescue Analytics Dashboard](https://github.com/NedimM24/animal-rescue-analytics-dashboard)

## Overview
The **Grazioso Salvare Animal Rescue Analytics Dashboard** is an interactive web application built with **Dash, Python, and MongoDB**. It allows users to view, filter, and analyze animal rescue data through interactive tables, charts, and geolocation maps.

Users can filter dogs by rescue type:
- Water Rescue
- Mountain/Wilderness Rescue
- Disaster/Individual Tracking

## Features
- Interactive radio-button filters and reset option
- Sortable and searchable animal data table
- Dynamic breed distribution charts
- Interactive geolocation maps using Dash Leaflet
- Grazioso Salvare branding and logo integration

## Technologies Used

### Python
Used for:
- Data processing with Pandas and NumPy
- Visualization with Plotly
- Dashboard development with Dash

### MongoDB
Used as the database because it:
- Stores flexible JSON-like animal records
- Integrates easily with Python through PyMongo
- Supports future database growth

### Dash Framework
- **View:** Dash components create tables, charts, maps, and controls
- **Controller:** Callbacks update dashboard content based on user input

## Project Process
1. Reviewed dashboard requirements and planned UI components
2. Connected MongoDB data using reusable CRUD operations
3. Built interactive data tables with filtering and sorting
4. Added rescue-type filters and reset functionality
5. Created dynamic charts and maps
6. Integrated branding and tested dashboard functionality

## Challenges Solved
- Fixed logo display issues using relative paths and base64 encoding
- Corrected Dash callback failures caused by component typos (`dcc.Graph`, `html.Div`)

## Installation

Install required packages:

```bash
pip install pandas numpy plotly dash dash-leaflet jupyter-dash pymongo
