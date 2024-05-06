# Public Transportation Dashboard for Geneva

This project presents an interactive dashboard showcasing open data on public transportation in Geneva. Leveraging the Voila library for rendering and the Jupyter-flex library for layout, the dashboard offers insights into various aspects of transportation within the city.

## Dashboard
The dashboard can be accessed [here](https://geneva-transports-analysis-c361239af243.herokuapp.com/).

### Preview

![Preview](dashboard/demo.gif)

### Features

The dashboard comprises three main pages, each providing unique insights:

1. **Nombre de montées par arrêt (Number of Boardings per Stop)**: This page includes a heatmap illustrating the volume of individuals boarding vehicles at different stops. Additionally, a corresponding bar chart offers further visualization. Users can conveniently select the month of interest via the sidebar.

2. **Nombre de montées par mois (Number of Boardings per Month)**: This section displays the total number of boardings per month since 2016, providing a comprehensive overview of boarding trends over time.

3. **Plan des arrêts (Stop Map)**: Here, users can explore a map featuring all stops within the Geneva transportation network. By entering an address, the dashboard identifies and displays the closest stops, facilitating navigation and route planning.

## Data Source

The data utilized in this project are sourced from the [Transports Publics Genevois (tpg) Open Data Platform](https://opendata.tpg.ch/). These datasets are made available under the terms and conditions specified by tpg, ensuring transparency and adherence to data usage policies.
