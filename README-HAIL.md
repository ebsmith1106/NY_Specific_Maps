# ⛈️ New York Hail Tracker

This Python project retrieves hail reports from the **NOAA Storm Prediction Center (SPC)**, filters for **New York State**, and plots the hail locations on a NY county map. The output is a visual representation of hail events during a user-defined date range.

---

## 🚀 How to Use

1. Make sure you have the required Python libraries installed:
   ```bash
   pip install pandas geopandas matplotlib requests

2. Get shapefile NYS County shapefile from repository

3. In the script, set your desired date range:
  start_date = datetime.datetime(2025, 4, 1)
  end_date = datetime.datetime.now()

4. Run the script. It will:
Fetch daily hail CSVs from SPC
Filter to include only New York hail reports
Save the data to a CSV (e.g., hail_events_ny.csv)
Plot the hail locations on a NY state map

## 👩‍💻 Author
Elizabeth Smith
Atmospheric Science Student
University at Albany, SUNY

##📌 Features
Retrieves hail report data for any date range
Filters hail events for New York State only
Plots hail locations on a map of NY counties
Outputs a clean CSV with hail location data

##📂 File Structure
hail_events_ny.csv — Output CSV with hail events in NY
NYS_Counties.shp and related files — NY county shapefile (external)
Python script — Main script for data collection and mapping

##🔍 Notes
This project uses data from the SPC’s daily hail reports.
Coordinate system: WGS84 (EPSG:4326)
Skips dates with no hail reports in NY

