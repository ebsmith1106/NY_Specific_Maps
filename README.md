# 🌀 New York Tornado Tracker

This Python project collects and visualizes tornado reports across **New York State** using data from the **NOAA Storm Prediction Center (SPC)**. It downloads daily tornado reports, filters for NY, and plots them on a map using GeoPandas and Matplotlib.

## 📌 Features

- Downloads tornado event data from SPC for a user-defined date range
- Filters reports to include only those in New York State
- Plots tornado locations over a county-level NY shapefile
- Saves data as a CSV for reuse

---

## 📂 File Structure

- `tornado_events_ny.csv` — Output CSV with NY tornado events
- `NYS_Counties.shp` — New York State county shapefile (external, required, added seperately)
- Python script — Contains the full data collection and plotting logic

---

## 🛠 Requirements

This script uses the following Python libraries:

```bash
pandas
geopandas
matplotlib
requests


In the script, set your desired date range:
start_date = datetime.datetime(2025, 4, 1)
end_date = datetime.datetime.now()

Run the script. It will:
Fetch tornado CSVs from the SPC
Filter and save New York-only data to a CSV (tornado_events_ny.csv)
Plot tornado locations on a NY state county map

👩‍💻 Author
Elizabeth Smith
Atmospheric Science Student
University at Albany, SUNY

