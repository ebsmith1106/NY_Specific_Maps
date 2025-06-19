# ⛅️SPC Convective Outlook Day 1, 2, or 3 Visualization for New York State

This Python script downloads and visualizes the Storm Prediction Center (SPC) Day 1, 2, or 3 convective outlook shapefile, focusing on New York State. It overlays the SPC risk categories on a map of New York counties to display the expected convective risk areas.

---

## 🗒️Features

- Downloads the latest SPC Day 1-3 convective outlook shapefile automatically.
- Uses a New York State counties shapefile to clip and display only relevant outlook areas.
- Plots different risk categories with distinct colors.
- Provides a clear map with county boundaries and a legend for risk levels.

---

## 🛑Requirements

- Python 3.x
- Packages:
  - geopandas
  - matplotlib
  - requests
  - zipfile (standard library)
  - io (standard library)
  - os (standard library)

---

## ✏️Usage

1. Ensure the New York counties shapefile is available locally. Update the `shapefile_path` in the script if needed.

2. Run the script. It will:
   - Download the SPC Day 1,2, or 3 outlook shapefile.
   - Extract and read the shapefile.
   - Reproject outlook data to match the counties shapefile CRS.
   - Clip outlook polygons to New York State.
   - Plot and display the outlook with risk categories.


