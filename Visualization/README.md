# Interactive Visual Analytics 📍📊

## Overview
This section focuses on building interactive visualizations for analyzing SpaceX Falcon 9 launch data using Folium and Plotly Dash.

## Objectives
- Visualize launch locations geographically  
- Analyze launch success using interactive maps and dashboards  
- Explore relationships between payload, launch site, and landing outcomes  

## Files Included
- lab_jupyter_launch_site_location.jupyterlite.ipynb  
  → Builds interactive maps with launch site markers, landing outcomes, and distance analysis.

- spacex-dash-app.ipynb  
  → Creates an interactive dashboard using Plotly Dash for visual analytics.

## Interactive Map with Folium
- Displayed all SpaceX launch sites on an interactive map  
- Added color-coded markers for successful and failed landings  
- Used marker clustering for better visualization  
- Calculated distances between launch sites and nearby infrastructure:
  - Coastlines
  - Highways
  - Railways
  - Cities

## Interactive Dashboard with Plotly Dash
- Implemented launch site selection using dropdown menus  
- Created pie charts to visualize launch success distribution  
- Added payload range slider for filtering missions  
- Built scatter plots to analyze:
  - Payload mass vs landing success
  - Booster version category vs success outcome

## Key Insights
- Launch success differs across launch sites  
- Payload mass and booster type affect landing success  
- Most launch sites are located near coastlines for operational safety  

## Tools Used
- Folium  
- Plotly Dash  
- Plotly Express  
- Pandas  
- Python  
