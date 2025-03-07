# Gowalla Data Processing Notebook

## Overview
This Jupyter Notebook processes and analyzes location check-in data from the Gowalla dataset. The goal is to augment location data with additional attributes, filter user check-ins, and analyze friend network relationships.

## Dataset Description
The dataset used in this notebook is
1. `Gowalla_totalCheckins.txt`, which contains location-based social networking check-in data. It includes the following columns:
- **user**: Unique user ID
- **time**: Timestamp of check-in
- **lat, lon**: Latitude and longitude of the location
- **loc**: Unique location ID
2.  `Gowalla_edges.txt` which contains the friendship edge tuples.

## Processed data URL
You can access the data used in the setup and run agent app section here https://www.mediafire.com/file/l7od1czcaaxhkyt/data.zip/file
