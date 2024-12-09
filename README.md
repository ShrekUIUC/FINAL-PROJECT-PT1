# Hockey Player Dashboard

## Overview
The **Hockey Player Dashboard** is an interactive web application built using Dash and Plotly. It visualizes player data from the NHL's Golden Era (1960s) and allows users to explore player statistics, compare attributes, and view geographical distributions of players.

---

## Features
1. **Player Search**: Search for players by name using a dropdown menu.
2. **Player Statistics**: View detailed stats such as team, season, height, weight, and position.
3. **Visual Comparisons**:
   - Scatter plot for height vs. weight comparison.
   - Box plot for BMI distribution by "Elite" status.
4. **Geographical Map**: Interactive map showing player birthplaces categorized by "Elite" status.

---

## Hypothesis
The NHL's Golden Era (1960s) was dominated by a small number of teams with highly talented players, many of whom were concentrated in specific geographical zones.

---

## Methodology
1. **Data Filtering**:
   - Filtered players active during the 1960s using `formatted_year` and selected specific seasons.
2. **Card Construction**:
   - Created Dash cards to display player-specific stats like team, season, height, weight, and position.
3. **Comparison Visuals**:
   - Designed scatter plots and box plots to compare player attributes.
   - Highlighted individual players in visuals using custom markers and annotations.
4. **Geographical Mapping**:
   - Used `geopy` to retrieve latitude/longitude for player birthplaces.
   - Created an interactive map using `scatter_mapbox`.

---

## Challenges Faced
1. **Card Construction**:
   - Building Dash cards was challenging and required following tutorials for proper implementation.
2. **Visual Comparisons**:
   - Highlighting individual players in scatter plots and maps was complex but achieved with annotations and markers.
3. **Box Plot Design**:
   - The box plot still doesn't fully meet expectations for clarity and design.
4. **Callbacks**:
   - Implementing dynamic callbacks was difficult, requiring external resources like the Perplexity API.

